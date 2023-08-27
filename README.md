# Active-Disturbance-Rejection-Control-of-PMSM
MATLAB Simulation of Active Disturbance Rejection Control of PMSM
Please find the Mathworks-excellence-in-innovation  project-207 details from [here](https://github.com/mathworks/MathWorks-Excellence-in-Innovation/tree/main/projects/Disturbance%20Rejection%20Control%20for%20PMSM%20Motors).

## Documentation:-

### Overview 
ADRC actively estimates and compensates for uncertainties and disturbances in PMSM models and drive systems using an extended state observer and nonlinear feedback control. This enables robust torque and speed regulation for PMSMs despite model inaccuracies, parameter variations, changing loads, and other uncertainties. The simple tuning and structure makes ADRC suitable for practical PMSM drive implementations. 

### Summary
It is an advanced robust control technique of PMSM. It includes ADRC block, PWM generator etc.


### Functionality 
The ADRC block in MATLAB is used to design and implement controllers for permanent magnet synchronous motors (PMSMs) that are subject to disturbances. The block uses a model-free approach to control the PMSM, which means that it does not require a detailed model of the motor. Instead, the block uses an observer to estimate the disturbance and then generates a control signal to cancel the effect of the disturbance. ADRC block will automatically design and implement a controller for the PMSM motor.


### Operation-
Here the reference speed is taken in rps. The gain for the adrc block is calculated using numerical analysis. Universal Bridge Converter block is used for the three phase inverter operation. Reference speed should less than 150 rps for better performance. ***I have updloaded the upadated version of this project in which I have also used ADRC for current controlling.***


## Skills:-
+ Matlab and Simulink
+ Power Electronics
+ Control System
+ Electric Machine
