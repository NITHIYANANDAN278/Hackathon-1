Name : NITHIYANANDAN N
Reg. No: 212222230099

Aim:
To design and simulate a traffic light controller for an intersection of three main roads, where each road has equal priority. The controller should regulate the traffic flow efficiently, ensuring safety and smooth movement of vehicles while diverting the traffic to path 1 direction and disabling control in other directions.
Apparatus Required:
1.	Hardware Description Language (HDL) simulation environment such as Verilog or VHDL.
2.	Simulation software like ModelSim for testing and verification.
3.	FPGA development board (optional) for hardware implementation.
Procedure:
1.	Define the State Machine
2.	Implement the State Machine in HDL
3.	Simulate the Design
4.	Test the Design
5.	Optimize and Refine

State Table :
•	To define the states, inputs, outputs, and state transitions. 
•	Let's denote the three main roads as MR1, MR2, and MR3. 
•	Each road can have three possible states for its traffic light: Red, Yellow, and Green. Here's the state table:
   
•	Each row represents a state transition along with the corresponding outputs for each main road.
•	The "Counter" column indicates the counts for each state before transitioning to the next state.
•	The "Current State" column represents the current state of the state machine.
•	The "Next State" column indicates the state to transition to after completing the counts.
•	The "MR1", "MR2", and "MR3" columns specify the traffic light states for each main road in the current state.
•	"Red", "Yellow", and "Green" denote the states of the traffic lights.
•	The counter counts from 0 to 9, where each count corresponds to one clock cycle.
Code: 


![image](https://github.com/NITHIYANANDAN278/Hackathon-1/assets/121784636/17ead845-cabf-4ff4-b9f3-9890a63afc41)


![image](https://github.com/NITHIYANANDAN278/Hackathon-1/assets/121784636/5ef5f68f-e7d4-4826-a374-331a8f864632)


![image](https://github.com/NITHIYANANDAN278/Hackathon-1/assets/121784636/0b829041-3c95-49b5-bcc5-10b5d7854b19)



![image](https://github.com/NITHIYANANDAN278/Hackathon-1/assets/121784636/aa853548-0400-4274-a8fc-65a8d1813cec)




RTL Schematic View


![image](https://github.com/NITHIYANANDAN278/Hackathon-1/assets/121784636/f43f7dd7-27ef-4626-ae16-56370464e420)

 


Output Waveforms



![image](https://github.com/NITHIYANANDAN278/Hackathon-1/assets/121784636/5c98b2ba-2069-41cf-b64f-39647f14b266)




