# AnanyaS-Active_Suspension_Control

**Project Summary**

This project focuses on designing an Active Suspension Control System using a PID controller to improve vehicle stability and passenger comfort. The suspension system was modeled using a transfer function and analyzed under both open-loop and closed-loop conditions. The main objective was to reduce vibrations caused by road disturbances, minimize oscillations, and improve damping characteristics of the vehicle suspension system.

**Software and Tools Used**

The project was implemented using MATLAB and Simulink. MATLAB was used for transfer function modeling, PID controller design, simulation, performance analysis, and generation of response plots. Simulink was used to create a visual block-diagram representation of the active suspension system for simulation and demonstration purposes. The Control System Toolbox was also used for advanced analysis such as Root Locus, Pole-Zero Mapping, Bode Plot, and Gain Margin evaluation.

**Implementation Stages**

The project was carried out in multiple stages. Initially, the suspension system was mathematically modeled and its open-loop response was analyzed to understand the baseline system behavior. A PID controller was then designed and connected in a closed-loop configuration to improve system performance. Comparative analysis was performed between the uncontrolled and PID-controlled systems, followed by disturbance testing using a simulated road bump introduced at 2 seconds to evaluate disturbance rejection capability.

**System Design Flow**

The system operates by taking a road disturbance input and passing it through a PID controller before entering the suspension model. The controller continuously adjusts the suspension response using proportional, integral, and derivative actions to reduce vibrations and improve damping behavior. The resulting vehicle body displacement response is then analyzed using performance metrics and control-system analysis techniques.

**Observations and Outcomes**

The open-loop suspension system was stable but showed slower settling and weaker disturbance rejection capability. After implementing the PID controller, the system achieved significantly faster stabilization with reduced oscillations and improved damping performance. The disturbance analysis demonstrated that the controlled system recovered much faster after encountering a road bump, proving the effectiveness of the PID-based active suspension control system.
