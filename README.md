# Multi-Robot Decentralized Task Execution
![Simulation](https://drive.google.com/file/d/1HU592h4OLqM12wYCD61ifTxnxWl7uplL/view?usp=drive_link)

Designed and implemented control strategies for a multi-robot system to autonomously complete complex tasks, including formation initialization, dynamic room coverage, return navigation, and refueling. Developed and tested algorithms such as edge-tension-based formation control, distributed formation graph topologiesand time-varying density (TVD-D0) for efficient task execution, ensuring obstacle avoidance, connectivity maintenance, and collision-free operation. Optimized system performance by addressing challenges like boundary constraints and formation stability in dynamic environments. Successfully validated the approach in a real world environment (robotarium) with real-time execution.

![Mission Complete](https://drive.google.com/file/d/1IaF9MFYslUa_cLaenJ1qdyXPNdGxgaWC/view?usp=sharing)
### Mission scenarios including:
- Initial Deployment: Ensured network connectivity and obstacle avoidance while navigating through predefined waypoints.
- Room Disinfection: Devised strategies to achieve >85% domain coverage using Voronoi cell-based coordination.
- Return to Refueling Station: Planned safe navigation while surveying hospital areas for future disinfection.
- Refuel: Configured robot formations based on adjacency matrix specifications at the refueling station.

### Key Features:
Implemented graph-based connectivity maintenance using weighted adjacency matrices.
Designed collision-free navigation leveraging range sensors and ∆-disk neighbor detection.
Conducted simulations to validate designs and deployed successful implementations on the Robotarium platform.
