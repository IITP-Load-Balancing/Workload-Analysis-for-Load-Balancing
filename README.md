# Preliminary Design of Hybrid Simulation Framework for Workload Analysis in Automotive Edge Computing
가상환경 기반 네트워크 트래픽/컴퓨팅의 시공간 분포에 대한 트레이닝 데이터 개발

# Abstract
Many vehicular tasks shall be completed in a timely manner as they move. 
In automotive edge computing, a vehicle can offload such tasks to an edge server in proximity to process them faster than using the cloud computing model. 
However, such an edge server has limited communication coverage and relatively smaller computing power compared to the general cloud server, it is important to distribute the offloaded workloads appropriately. 
One needs to understand such workload patterns and quantitatively analyze them for such workload distribution. 
We propose a preliminary hybrid simulation framework that generates compute workloads via a combination of the virtual vehicular traffic and the physical edge-server platforms.

# A Framework for Collecting Realistic Workloads
The framework is divided into a *virtual* traffic generator and a *physical* computing load generator.
* Traffic Generator
* Workload Model
* Computing Load Generator


<img src="https://github.com/user-attachments/assets/9f408fbf-d957-47c8-b441-cca6c9cd3d0e" width= "500" height="350">

<img src="https://github.com/user-attachments/assets/3a01362e-cb97-453f-b05e-8b9026161b1d" width= "550" height="250">

# Result
We quantitatively analyzed the relationship between the computing load types and the offloaded task sizes, which generally depend on the road geometry and the volume of vehicles occurring in the area covered by each edge server. 
Traffic data was collected by implementing an actual road in VISSIM, and realistic computing load data was collected using the physical hardware. 
Our preliminary analysis shows that as the number of vehicles increases and the offloading interval decreases, more computing loads are imposed on the edge server. 
More in-depth analysis is necessary in the future to rigorously design a load-balancing technique.

![스크린샷 2024-11-29 162352](https://github.com/user-attachments/assets/bd53e6eb-5894-4366-9d3f-11db384e3ebd) |![스크린샷 2024-11-29 162653](https://github.com/user-attachments/assets/a825a681-0c40-41a7-8982-519d5e5b55a6)
--- | --- | 
