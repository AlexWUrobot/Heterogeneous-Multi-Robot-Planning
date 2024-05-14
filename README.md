# Optimizing the Number of Working Robots

During a major accident, various rescue teams from surrounding cities may possess different types of robots. 
Both the total energy and rescue time are typically constrained. Optimizing the allocation of working robots can be framed as an Unbounded Knapsack Problem (UKP). 
To address this, a dynamic programming method is introduced and detailed in Algorithm

Users have the ability to input parameters such as the total battery capacity ($\Omega$) on USV equipped with mobile chargers, and the characteristics of the robots. These robot parameters include individual battery capacities ($\omega$), maximum traveling distance, and the range of vision. The range of vision can be adjusted by altering the camera of AUVs or the flight height of UAVs. The total coverage range ($\nu$) is determined by multiplying the maximum traveling distance and the range of vision. A set of hypothetical parameters is illustrated in 

The dynamic programming method takes these inputs and calculates the maximum coverage area for different numbers of heterogeneous vehicles. In Fig.\ref{fig:dp_uav}, the x-axis represents the varied total battery capacity in the mobile chargers (USV), while the left side of the y-axis in Fig.\ref{fig:dp_auv} indicates the numbers of different types of working robots. The right side of the y-axis denotes the estimated total coverage mission range.


Currently, we separately optimize the path planning and the number of workers. In future work, we plan to merge this algorithm to monitor the total remaining battery levels of mobile chargers and change the robots' schedules in real time.

![Dynamic programming optimizes the number of AUVs under various battery capacities](https://github.com/AlexWUrobot/Heterogeneous-Multi-Robot-Planning/blob/main/AUV_cover_v4.png)


<p>
  <img src="https://github.com/AlexWUrobot/Heterogeneous-Multi-Robot-Planning/blob/main/AUV_cover_v4.png" alt="">
  <em>Dynamic programming optimizes the number of AUVs under various battery capacities</em>
</p>
![Dynamic programming optimizes the number of UAVs under various battery capacities](https://github.com/AlexWUrobot/Heterogeneous-Multi-Robot-Planning/blob/main/UAV_cover_v4.png)
