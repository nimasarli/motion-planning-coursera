# Motion Planning for Self-Driving Cars
## Objectives
The goal of the project are as follows:
- Use a Conformal Lattice Planner to generate paths to avoid static obstacles
- Generea velocity profiles to avoid dynamic vehicles
- Develop a state machine for behavior planning
- Write a planner to navigate a given scenario of ubran driving that includes avoiding a static obstacle (a parked vehicle in the lane), following a lead vehicle, decelerate to stop at a stop sign, ..


## Path Planner

## Path Collision Checking
$$\delta = atan\left(\frac{2 \\, L \\, sin(\alpha)}{l_d}\right)$$
where $\delta$ is the steering angle, $L$ is the wheel-base length, $\alpha$ is the look-ahead angle and $l_d = k_{dd} \\, v$ is the look-ahead distance set to 
a multiple of vehicle speed. 


## Velocity Profile Generation


## Behavioral Planner

## Results
The following shows the results in CARLA simulator.


