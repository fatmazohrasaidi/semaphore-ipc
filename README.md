# Urban Waste Collection Simulation (UNIX)  
This project simulates an urban waste collection system using UNIX process management tools. For more details about the project, the project documentation is provided in the attached PDF.  
## Core Concepts   
**Processes:** One controller + N trucks.  
**Synchronization:** Managed via semaphores.  
**Communication:** Done using message queues.  
**Shared Memory:** Stores the state of bins and system variables.  

## System Specs  
**Bins (M):** 20   
**Trucks (N):** 5   
**Fuel Capacity (CP):** 300  
**Max Missions:** 12  
**Fuel Threshold (Min):** 70  
**Fuel Consumption:** C × distance (C = 2)  
**Distances:** ≤ 20  

## How to Run  
1- Compile tp2.c file with:  gcc -o tp2.c main.exe  
2- Run the executable: ./main.exe  
3- The program prints logs to simulate the behavior of the trucks and controller.  
