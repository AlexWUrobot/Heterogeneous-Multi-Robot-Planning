# Optimizing the Number of Working Robots

During a major accident, various rescue teams from surrounding cities may possess different types of robots. 
Both the total energy and rescue time are typically constrained. Optimizing the allocation of working robots can be framed as an Unbounded Knapsack Problem (UKP). 
To address this, a dynamic programming method is introduced and detailed in Algorithm

Users have the ability to input parameters such as the total battery capacity ($\Omega$) on USV equipped with mobile chargers, and the characteristics of the robots. These robot parameters include individual battery capacities ($\omega$), maximum traveling distance, and the range of vision. The range of vision can be adjusted by altering the camera of AUVs or the flight height of UAVs. The total coverage range ($\nu$) is determined by multiplying the maximum traveling distance and the range of vision. A set of hypothetical parameters is illustrated in 
