---
layout: page
permalink: /Research/index.html
title: Research
---

Latest Update: 20th Oct 2023&nbsp; 

During my professional experience with enterprise-level automated vehicle projects, I specialized in multidimensional data analysis. This involved not only extracting and processing large datasets from real vehicles but also integrating and analyzing eye-tracking data of drivers. Such comprehensive data handling equipped me with a unique perspective on human-machine interaction, specifically in understanding and optimizing takeover behavior in autonomous driving.

## Journal Paper

- Zhenhua Yu, <font color='red'>Gerui Xu</font>, Kang Jiang, Zhongxiang Feng, Shan Xu. (2023). Constructing the behavioral sequence of the takeover process—TOR, behavior characteristics and phases division: A real vehicle experiment. Accident Analysis & Prevention, 186, 107040. [<font color='red'>Access article</font>](https://doi.org/10.1016/j.aap.2023.107040)

  <figure style="text-align:center;">
  <div style="display: inline-block; text-align: center;">
  <img src="https://GeruiXu.github.io/mypaper/Projects/paper0.png" style="max-width: 100%; max-height: 600px;" alt="Behavioral sequence">
  <figcaption>Behavioral sequence</figcaption>
  </div>
  </figure>
  <br>

---

## Graduate Research 

###  Stage1  Real Vehicle Experiment I ——Constructing phase-based behavioral features for the takeover process

> ### Purpose
>
> - The study focuses on human-machine co-driving scenarios in autonomous driving, especially situations where the driver needs to take over control in complex circumstances.
> - Previous studies have mainly concentrated on static behavior indicators and the primary stages at the onset of takeover, but this study aims to construct a behavioral sequence based on the dynamic changes in behavior characteristics during the takeover process.
> - The research investigates the influence of different types of auditory cues on the timing of takeover operations and driving performance at various stages.
>
> ### Experiment Design
>
> - The subjects were 20 professional drivers who performed non-driving related tasks (NDRT) under real road conditions and took over the vehicle to perform evasive maneuvers after receiving auditory cues.
> - The experiment tested the drivers' takeover performance using different types of auditory cues, such as actual sounds, alarm tones, and electronic voice.
> - The study analyzed the performance of operational behaviors, visual transfer, and attention throughout all stages of the takeover.
>
> <figure style="text-align:center;">
> <div style="display: inline-block; text-align: center;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/Graduate/E1.0.png" style="max-width: 100%; max-height: 600px;" alt="Procedure of the experimental design">
> <figcaption>Procedure of the experimental design</figcaption>
> </div>
> </figure>
> **Results**:
>
> 1.**Behavioral Characteristics and Phase Division**: The study demonstrates that the behavioral characteristics of drivers during the takeover process in autonomous vehicles can be used to divide different behavioral stages, revealing the dynamic changes in attention allocation, visual transition, and operational responses during takeover operations.
>
> <figure style="text-align:center;">
><div style="display: inline-block; text-align: center;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/paper1.png" style="max-width: 100%; max-height: 600px;" alt="Procedure of the experimental design">
> <figcaption>Time distribution of key features</figcaption>
> </div>
> </figure>
> 2.**Impact of Audio Cue Types**: Different types of audio cues, such as actual sounds, alarm tones, and electronic voices, significantly impact the timing and performance of the driver's takeover operations. Some types of cues can improve response speed and operational efficiency, while others may lead to reduced takeover efficiency.
> 
><div style="text-align:center;">
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
><img src="https://GeruiXu.github.io/mypaper/Projects/paper2.png" style="width:100%; height:auto;">
> <figcaption>The operations in the whole takeover process</figcaption>
> </figure>
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/paper3.png" style="width:100%; height:auto;">
> <figcaption>Temporal distribution and transfer of visual attention.</figcaption>
> </figure>
> </div>
> 3.**Time Series Analysis of Takeover Operations**: Through time series analysis of operational behaviors during the takeover process, the study reveals behavior patterns and operational characteristics at different stages. This helps in understanding how to design more effective audio cues in various stages to enhance the driver's takeover performance.

###  Stage2 Real Vehicle Experiment II——Establishment of real-time driving incentives for autonomous driving

> ### Purpose
>
> In order to construct a driver takeover behavior model (such as the discrimination and prediction of professional driving behavior), we collect data on the long-term manual driving behavior and takeover behavior of drivers with different characteristics as our dataset.
>
> - **Takeover behavior prediction**: Based on behavioral sequence to establish a behavior prediction mechanism.
> - **Takeover correction strategies:** Design takeover behavior modification evaluation system.
> - **Takeover Assistance Effectiveness Validation**: Validating the effectiveness of post-takeover decision assistance based on behavioral sequences.
>
> ### Experiment Design
>
> **1.Data collection consists of two main components:**
>
> - The first part involves subjects engaging in manual driving operations for an extended period, which includes normal driving behavior and behavior to avoid objects while driving normally. 
>
> - The second part involves subjects being in a distracted state and engaging in avoidance behavior during unexpected situations while driving manually.
> - **Data on effective takeovers collected over a long period by 40 professional drivers is used for modeling.**
>
> <div style="text-align:center;">
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/Graduate/exp5.png" style="width:100%; height:auto;">
> <figcaption>Different takeover scenarios (Front Cameras)</figcaption>
> </figure>
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/Graduate/exp6.png" style="width:100%; height:auto;">
> <figcaption>Highway environment (Side Cameras) </figcaption>
> </figure>
> </div>
> **2.Constructing the takeover assistance model**:
>
> <figure style="text-align:center;">
> <div style="display: inline-block; text-align: center;">
> <img src="https://GeruiXu.github.io/mypaper/modeling/model1.png" style="max-width: 100%; max-height: 600px;" alt="Procedure of the experimental design">
>  <figcaption>Single optimization</figcaption>
> </div>
> </figure>
>
> This section will combine the reliance on behavioral sequences and focus on the interaction of decision-making behaviors after model application takeover, in order to verify the effectiveness of behavioral optimization post-takeover.
>
> <div style="text-align:center;">
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/Graduate/exp7.png" style="width:100%; height:auto;">
> <figcaption>Autonomous driving (Frount Cameras)</figcaption>
> </figure>
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/modeling/model2.png" style="width:100%; height:auto;">
> <figcaption>Behavioral modification interaction</figcaption>
> </figure>
> </div>
>
> ### Publicly available results
>
> - In the post-takeover behavioral optimization tests with subjects, 80% positive feedback was collected.



### Stage3 Real Vehicle Experiment III——Takeover Model Practical Validation

> ### Purpose
>
> - Design takeover modification human-machine interaction form.
> - Real Validation VS. Virtual Simultaneous —— Model Experiments
>
> <div style="text-align:center;">
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/Graduate/exp3.png" style="width:100%; height:auto;">
> <figcaption>L3 automated vehicle practical validation</figcaption>
> </figure>
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/Graduate/exp4.png" style="width:100%; height:auto;">
> <figcaption>Virtual simultaneous</figcaption>
> </figure>
> </div>
>
> <font color='red'>[Coming soon ......]</font>

### Level-4 Automated Vehicles Urban Road Tests

> ### Urban Road Tests in Different Cities (Wuhan & Hefei)
>
> [<font color='red'>**One road testing record in Wuhan (Modevol format)**</font>](https://www.modevol.com/episode/clfgnhndb7fv901lr9pob7fk9) or [***Bilibil***](https://www.bilibili.com/video/BV13c41177E9/)
>
> ### Overview
>
> The Apollo Moon (Polar Fox) autonomous vehicle, equipped with a safety operator in the front passenger seat, is responsible for ensuring the safety of the journey along the test route.
>
> <div style="text-align:center;">
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/L4test1.png" style="width:100%; height:auto;">
> <figcaption>Apollo Moon</figcaption>
> </figure>
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/L4test3.1.png" style="width:100%; height:auto;">
> <figcaption>Global monitoring perspective</figcaption>
> </figure>
> </div>
>
> <div style="text-align:center;">
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/L4test3.png" style="width:100%; height:auto;">
> <figcaption>Wuhan road tests</figcaption>
> </figure>
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/CT1.png" style="width:100%; height:auto;">
> <figcaption>Hefei road tests</figcaption>
> </figure>
> </div>
>
> ### Analysis of  emergency situations
>
> #### 1. Factors Contributing to Traffic Congestion
>
> <div style="text-align:center;">
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/L4test4.png" style="width:100%; height:auto;">
> <figcaption>Traffic Congestion</figcaption>
> </figure>
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/L4test4.1.png" style="width:100%; height:auto;">
> <figcaption>Traffic Congestion</figcaption>
> </figure>
> </div>
>
> ##### Inability to Change Lanes
>
> Comprehensive monitoring has revealed no significant operational anomalies in autonomous vehicles. However, under the conditions of high traffic flow at intersections, these vehicles failed to execute a planned right lane change, thereby entering a congested area along the straight lane and missing the opportunity to switch lanes.
>
> ##### Excessive Caution in Evasion 
>
> The autonomous driving system adopts a conservative strategy for yielding to all incoming vehicles and pedestrians. In practical scenarios, this policy has led to missed lane-changing opportunities due to prioritizing right-of-way, followed by a halt after slowing down to avoid vehicles from behind. The system replans the route when the original lane change is deemed unfeasible.<br>Analysis indicates that the vehicle attempted multiple times to follow the predetermined route but failed due to the inherent avoidance logic programmed into it. Impatient reactions and aggressive lane-changing behavior of drivers from behind exacerbated the congestion.
>
> In summary, this incident highlights the strategic limitations of the autonomous driving system in specific, unforeseen circumstances.<br>Factors Contributing to Traffic Congestion
>
> #### 2. Hazardous Incident: Running a Red Light
>
> <div style="text-align:center;">
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/L4test5.png" style="width:100%; height:auto;">
> <figcaption>Hazardous Incident</figcaption>
> </figure>
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/L4test5.2.png" style="width:100%; height:auto;">
> <figcaption>Red Light</figcaption>
> </figure>
> </div>
> 
>
> ##### Failure to Synchronize with Traffic Signals
> Initially, from a global monitoring perspective, it was evident that the autonomous vehicle failed to receive information from the traffic lights upon approaching the intersection. This deviates from standard operations, as vehicles in previous monitoring footage were able to receive and display traffic light signals in advance.
>
> Subsequently, even as the vehicle approached the vicinity of the pedestrian crossing, the system could only display information about surrounding vehicles and road conditions, failing to recognize the red light signal. Despite the radar's recognition range far exceeding the display range of the human-machine interface, the vehicle appeared to have suddenly lost its perceptual capabilities regarding road infrastructure in this instance.
>
> ##### Navigating an Unfamiliar Route
> This route was recently updated, and the vehicle had never traversed it before, resulting in an absence of corresponding information in the database. Had it not been for the previous traffic congestion, the vehicle was originally planned to make a right turn onto Hanyang Avenue. However, due to the congestion, the system replanned a route involving a left turn and a U-turn, leading the vehicle to enter this unfamiliar route for the first time.
>
> Confronted with this newly updated and database-absent route, the vehicle had to rely on the information it could perceive for decision-making. In this unknown scenario, due to the inability to connect with road infrastructure, the vehicle misjudged the absence of traffic lights at the intersection and continued its course.
>
> Ultimately, the safety officer took emergency control and averted a major accident by forcibly braking the vehicle.

------

## Graduate Projects

### Jun 2022 – Present **"Dynamic Transfer Patterns of Takeover Behavior in Autonomous Driving and Methods for Enhancing Takeover Performance"**

**National Natural Science Foundation of China** (Grant Nos. 52172344)————Supervised by ***Prof. Kang Jiang***

> - **Development of a Takeover Assistance Model:** Conducted takeover experiments with professional drivers in real road scenarios. Applied time series deep learning for modeling takeover decisions and tendencies.
>- **Development of a Driver Assistance System:** Established a corrective evaluation system for takeover behaviors and developed a multimodal human-machine interaction form based on the takeover assistance model.
> - **Model Application and Validation:** Developed a real-time interaction platform in experimental vehicles, verifying the model’s effectiveness in optimizing takeover behavior in real-road conditions.

### Sep 2021 – Dec 2022 **"Mechanism of Visual Focus Transfer and Method of Human-Computer Interaction of Wake-up Attention As Take-over in Highly Automated Driving"** 

**National Natural Science Foundation Youth Fund** (Grant Nos. 51905142) ————Supervised by ***Dr. Zhenhua Yu***

> - **Takeover Behavior Sequence:** Developed a four-stage behavioral model for autonomous driving takeover, integrating visual and operational data based on behavioral spectrum principles.
>
> - **Behavioral Process Analysis:** Utilized time series and MANOVA for analyzing the dynamic process in autonomous driving takeover.
>
> - **Audio Feedback Effect Analysis:** Investigated the impact of various audio feedback types on driver performance, offering dynamic, interaction-based safety solutions for autonomous systems.
>
>   <figure style="text-align:center;">
>   <div style="display: inline-block; text-align: center;">
>   <img src="https://GeruiXu.github.io/mypaper/Projects/Graduate/Meinexp.png" style="max-width: 100%; max-height: 600px;" alt="Procedure of the experimental design">
>    <figcaption>In debugging equipment, the person in red attire is me</figcaption>
>   </div>
>   </figure>

### Aug 2022 – Present  **"Spatial Object Recognition and Tracking Localization Based on Augmented Reality"** 

Corporation Foundation (2022JSKF1064) ————Supervised by ***Prof. Kang Jiang***

> - **Sensor Technology Integration and Data Fusion:** Integrated multi-sensors with IMU inertial navigation systems and developed a fusion algorithm, significantly improving system positioning accuracy in dynamic environments<br>
>- **Data Analysis and Visualization:** Responsible for processing fused data, extracting key features for statistical analysis, and developing a data visualization interface.<br>

------

## Undergraduate Outstanding Projects

### May 2018 – Aug 2019  "Ergonomically Designed Multifunctional Intelligent Medical Bed"<br>

> <font color='red'>Team Leader</font><br> Supervised by *Dr. Zhenhua Yu*<br>
> Team members' majors: Mechanical Design Manufacturing and Automation, Industrial Engineering, Software Engineering, Information Management and Information Systems, .
>
> ### Overview<br>
>
> This project innovatively develops an **advanced medical care bed** by integrating **human factor engineering**, **big data analytics**, and **artificial intelligence** into existing medical and nursing bed designs.
>
> It combines **mechanical structure** with **electronic control** based on the **human-machine integrated model** to achieve **flexible and intelligent posture adjustment** using the human body posture parameters from the model. This allows the medical bed to provide functions like **massage**, **lifting**, and **vital signs monitoring**.
>
> <div style="text-align:center;">
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/Undergraduate/Medical bed1.1.png" style="width:100%; height:auto;">
> <figcaption>Conceptual Diagram</figcaption>
> </figure>
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
> <img src="https://GeruiXu.github.io/mypaper/Projects/Undergraduate//Medical bed0.png" style="width:100%; height:auto;">
> <figcaption>Mechanical schematic</figcaption>
> </figure>
> </div>
>
> ### My Contributions
>
> #### 1.Key Innovations
>
> The bed surface consists of a **matrix of actuators** evenly distributed to effectively disperse pressure on the human body. 
>
> * When a patient lies on the bed, **pressure sensors** embedded in the actuators can collect and feedback real-time user position data to the cloud. 
> * The actuators are **designed based on human factor** principles to precisely conform to different body parts. 
>
> Underneath, **multiple stepper motors** drive cams and gears to translate continuous rotation into orderly actuator movements. **By rising and lowering at differential speeds**, the actuators induce continuous motions on specific body parts.
>
> #### 2.Enabling Mechanisms
>
> * **Motors** also power the primary and secondary shafts to enable the bed's functions. 
>     * The primary shaft goes through a belt and bevel gear to change direction, allowing **axial rotation** of the bed. 
>     * The secondary shaft connects to a **gear train** for orbital motion around the bed.
> * **Inclination** of the bed is enabled by the tilt mechanism on the bed frame, working with a linear actuator and motor. 
> * Additionally, an incomplete large spur gear combined with a rack actively lifts and lowers groups of actuators for targeted adjustment according to body needs.
>
> <div style="text-align:center;">
>     <figure style="display:inline-block; margin: 0 10px; max-width:30%;">
>         <img src="https://GeruiXu.github.io/mypaper/Projects/Undergraduate/Medical bed2.1.png" style="width:100%; height:auto;">
>         <figcaption>Base and bed frame model</figcaption>
>     </figure>
>     <figure style="display:inline-block; margin: 0 10px; max-width:30%;">
>         <img src="https://GeruiXu.github.io/mypaper/Projects/Undergraduate/Medical bed2.2.png" style="width:50%; height:auto;">
>         <figcaption>Gear and push rod assembly</figcaption>
>     </figure>
>     <figure style="display:inline-block; margin: 0 10px; max-width:30%;">
>         <img src="https://GeruiXu.github.io/mypaper/Projects/Undergraduate/Medical bed2.3.png" style="width:100%; height:auto;">
>         <figcaption>Bed frame state diagram</figcaption>
>     </figure>
> </div>

### Jun 2018 – May 2019  "Intelligent Robots——Combat Robot "<br>

> ### Overview <br>
>
> <font color='red'>Program designer</font> <br>As a member of the intelligent robot project team (only 3 candidates), I was fully involved in the development of a sophisticated combat robot named "Pioneer." As the chief software architect of this project, I spearheaded the entire programming and functional implementation of the robot, with a particular emphasis on the development of its core logic: autonomous patrolling, enemy detection and attack strategies, and evasion and disguise mechanisms. Ultimately, we fabricated two prototypes of "Pioneer" and participated in the finals of the Intelligent Robotics Competition.
>
> <div style="text-align:center;">
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
>   <img src="https://GeruiXu.github.io/mypaper/Projects/Undergraduate/Robot1.png" style="width:100%; height:auto;">
>   <figcaption>Camouflage in dark conditions</figcaption>
> </figure>
> <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
>   <img src="https://GeruiXu.github.io/mypaper/Projects/Undergraduate/Robot2.png" style="width:100%; height:auto;">
>   <figcaption>Safety zone patrol</figcaption>
> </figure>
> </div>
> ### My Contributions
> 1. Architected the software system and hardware-software integration for Pioneer based on key competition requirements like the arena dimensions, weight limits, and scoring mechanics. This involved close collaboration with the mechanical and electrical engineers in the team.
> 2. Created autonomous control algorithms enabling Pioneer to intelligently navigate around the arena without falling off, using data from infrared and analog sensors. The algorithms had to be robust to sensor noise and uncertainties.  
> 3. Developed opponent search-and-attack logic by fusing inputs from multiple infrared rangefinders to reliably detect and lock on to enemy robots. This included aiming routines to align our robot's shovel perfectly for maximum pushing power.  
> 4. Optimized the software for real-time performance and responsiveness during battles. This was challenging due to the complex state transitions required between exploration, attack, and self-preservation modes.
> 5. Led the strategy for integrating and testing the complete robotic system. Coordinated with team members to troubleshoot issues like PCB failures or mechanical alignment problems.  
>
> <div style="text-align:center;">
>  <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
>      <img src="https://GeruiXu.github.io/mypaper/Projects/Undergraduate/Robot3.png" style="width:100%; height:auto;">
>      <figcaption>Camouflage in dark conditions</figcaption>
>  </figure>
>  <figure style="display:inline-block; margin: 0 10px; max-width:45%;">
>      <img src="https://GeruiXu.github.io/mypaper/Projects/Undergraduate/Robot4.png" style="width:100%; height:auto;">
>      <figcaption>Safety zone patrol</figcaption>
>  </figure>
> </div>
>
> ### Outcome
>
> In the competition, "Pioneer" excelled, reliably exploring over 90% of the arena and defeating two opposing robots with coordinated attack logic using just one unit. Our emerging team stood out amidst fierce competition from seasoned teams nationwide, reaffirming the efficacy of the software system I developed for "Pioneer." This project enhanced my skills in robot algorithms, software architecture, hardware-software integration, and leading engineering teams.

