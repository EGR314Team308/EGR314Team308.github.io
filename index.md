
# Mobile Weather Station Project
## Team 308
## Marla Hawthorne, Andrew Sarrasin, Lina Mayyas, Jeffrey Davis
## January 23, 2023
## Arizona State University
## EGR 314 Spring 2023
## Travis Kelley

<br>
<div>
<p >Table of Contents</p>
<ul>
  <li><a>1 Team Organization</a></li>
<li><a>2 User Needs, Benchmarking, and Requirements</a></li>
<li><a>3 Design Ideation</a></li>
<li><a>4 Selected Design</a></li>
<li><a>5 Block Diagram</a></li>
<li><a>6 Component Selection</a></li>
<li><a>7 Microcontroller Selection</a></li>
<li><a>8 Software Proposal</a></li>
<li><a>9 Hardware Proposal</a></li>
<li><a>10 Presentation</a></li>
</ul>
</div>
<br>

  The goal of this project is to navigate the process of creating systems for serial sensing for a variety of uses for robotics and many others. A responsive system will be created and fabricated to be able to adapt to its environement. By the utilization of sensors, control algorithims, and actuators, an increase of effectives and efficiency will occur. The ultimate goal is to design a system with the ability to detect and respond to changes within the environement. 


  A multidisciplinary approach will be used to provide success in this project, which will combine the knowledge and aspects of both Robotic and Electrical Engineering . The ultimate objective is to develop an intelligent system that will have the ability to enhance human interaction with the environment and pave the way for a more sustainable future. 


<br><br>

[Team Organization](TeamOrganization.md)

Our team first evaluated the needs of the project and assessed the syllabus to consider academic points that will need to be touched base this semester. It is incredibly important that every team member is aware of the requirements of this courses expectations. Therefore, a list of five different team charter points was created to focus on during the semester. Each point ensures the success of each team memeber in this course along with the success as a team. As a team, following these team charter points is very beneficial to the quality and achievement of our course project. We have a set goal that we will work on achieving thorught the semester by implementing our team charter onto our weather monitoring system. The teams main goal is to use our skills and knowledge and implement it into our project. 

<br>
 
[User Needs, Benchmarking, and Requirements](UserNeeds.md)

After carefule consideration of our mission statement and charter, we later moved onto laying out potential user needs and requirements that are needed to the prototype. To create user needs, we used existing customer comments to similiar products to capture thier needs and recognize solutions to thier issues. This allowed us to create the most precise user needs and solutions to create a product that serves customer satisfaction and user friendliness. The user needs collected and created were then organized and tranferred into a clear list that will be focused on thorught the creation of this project. By doing this, it allows us to use engineering skills to enable these needs within our prototype. 
 
<br> 

[Design Ideation](DesignIdeation.md)

After creating a list of user needs and requirements, we created three designs for consideration for the final prototype. Each team member proposed ideas in a general basis and as a team, we created three different ideas that this project could be based off of. Brainstorming together as a team was very beneficial as it inspired new ideas and some designs that were created were combinations of two different ideas. As a team, we were then able to protoype complete draft designs that fit the needs of the project requirement and are possible candidates for a final design concept that will be implemented into a physical protoype by the end of this semester. 

<br>

[Selected Design](SelectedDesign.md)


On choosing a design for our project, our team worked together. With our ideation sessions, we started by thinking and producing a range of design choices. Next, after carefully examining each design, we chose the best one based on its advantages, how well it satisfied the project's criteria, and whether it was within the allotted budget. We gathered the opinions of every team member before making a decision, allowing us to take into account all viewpoints and insights. By involving the whole team in this process, we made sure that everyone had a say and that everyone supported the final design. In the end, we are convinced that the design we have selected will be successful in accomplishing the project's goals.


<br>

[Block Diagram](BlockDiagram.md)

The block diagram is an essential component that will graphically represent the key elements of each subsystem and show how they will work together to create the finished result. This thorough strategy will act as the framework for our project, clearly and succinctly laying out how the work and components will be distributed. We will give a thorough overview of the product, displaying how each component works into the bigger system as well as highlighting its features and potential. With the use of our block diagram, which will be a crucial presentation tool, we will be able to show how each subsystem works in concert with the others to accomplish a shared objective. 

<br>

[Component Selection](ComponentSelection.md)

Our team had to carefully study and assess numerous important components for each subsystem as part of the component selection process. Our team chose the components with an uncompromising focus on quality, a sharp eye for detail, and a well-thought-out justification that guaranteed their ideal performance and compatibility with the system. It is important to note that the microcontroller selection procedure was carried out independently and will be covered in a separate section. 
These components are mostly set in stone. Each person in the group is free to choose another component as long as it is represented in the current documents. As the team sees it, this portion of the project is complete, because all persons on the team have made individual schematics and combined them into the hardware proposal, which you may direct to or ask about.
<br><br>

**Motor 505-AD8630ARZ-ND:**
<br><br>
![Pro](ComponentMotor.JPG)
<br>

This motor is a terrific option for applications that need accurate and effective motor control because it has outstanding torque and speed ratings. Its small size makes it perfect for use in space-constrained small and lightweight applications. The motor is also energy-efficient, making it possible for it to run on little power, which is essential for portable and battery-powered applications.

Here are the specifications for this component:
 
1. Supply voltage range: ±2.5 V to ±18 V
2. Input offset voltage: 0.5 mV (maximum)
3. Input bias current: 0.5 nA (maximum)
4. Input voltage range: ±Vs-1.5 V (maximum)
5. Gain bandwidth product: 12 MHz (typical)
6. Slew rate: 5 V/μs (typical)
7. Input noise voltage density: 4.5 nV/√Hz (typical)
8. Input noise current density: 0.9 pA/√Hz (typical)
9. Output voltage swing: ±13.5 V (minimum)
10. Operating temperature range: -40°C to +125°C.


**OpAmp BD1321G-TR: **
<br><br>
![Pro](ComponentOpAmp.JPG)
<br>

This OpAmp can function across a certain voltage range. It is the perfect option for projects with complex setups due to its small size and simplicity of interaction with other parts and systems. In addition, the BD1321G-TR offers constant voltage output, which contributes to its high level of dependability and ensures the proper operation of the complete system. Due to its low power consumption, it is an energy-efficient solution that can aid in lowering the project's overall power usage.

Here are the specifications for this component:

1. Input voltage range: 2.5 V to 5.5 V
2. Output voltage: 1.2 V to 5.5 V
3. Maximum output current: 150 mA
4. Dropout voltage: 100 mV (typical) at 100 mA output current
5. Line regulation: 0.02%/V (typical)
6. Load regulation: 0.05%/mA (typical)
7. Quiescent current: 20 μA (typical)
8. Overcurrent protection: 200 mA (typical)
9. Thermal shutdown protection
10. Operating temperature range: -40°C to +85°C

**Analog-to-digital converter (ADC) 595-ADS8924BRGET:**
<br><br>
![Pro](ComponentADC.JPG)
<br>

For tasks that need for accurate and exact data gathering, this high-speed ADC is the best option because of its superb accuracy and precision. Maximum versatility is provided by its highly adjustable operating modes, which may be tailored for various applications. The ADC's high level of dependability also ensures that the data acquisition system performs as planned. It is the best option for projects that call for compact and energy-efficient solutions because to its tiny size and low power usage.

Here are some of its key specifications:

1. Resolution: 16 bits
2. Number of channels: 4
3. Sampling rate: Up to 2 MSPS (mega samples per second)
4. Input voltage range: ±5 V, ±10 V, 0-5 V, and 0-10 V
5. Input impedance: 20 kΩ differential
6. Power supply voltage: 3.3 V
7. Power consumption: 118 mW at 2 MSPS and 3.3 V
8. Operating temperature range: -40°C to +85°C
9. Package: 24-pin VQFN


**Low-dropout regulator MCP1700T-3102E/TT: **
<br><br>
![Pro](ComponentVoltageRegulator.JPG)
<br>

This low-dropout regulator is simple to integrate into projects that call for a steady and dependable power supply. For the appropriate operation of the entire system, it ensures that the power supply works within the necessary range thanks to its outstanding voltage regulation. The MCP1700T-3102E/TT is a great option for applications that call for long-term continuous use because it is also extremely energy-efficient and uses little power while in use.

Here are its key specifications:

1. Output voltage: 3.1 V
2. Dropout voltage: 178 mV at 250 mA
3. Maximum output current: 250 mA
4. Input voltage range: 2.7 V to 13.2 V
5. Quiescent current: 2 µA (typical)
6. Line regulation: 0.1% (typical)
7. Load regulation: 0.4% (typical)
8. Operating temperature range: -40°C to +125°C
9. Package: SOT-23


**Motor Driver IFX9201SGAUMA1:**
<br><br>
![Pro](ComponentMotorDriver.JPG)
<br>

The great efficiency of this high-performance motor driver makes it the perfect option for applications that need for energy-saving solutions. Maximum versatility is provided by its highly adjustable operating modes, which may be tailored for various applications. The IFX9201SGAUMA1 is also very dependable, making sure that the power management system performs as planned. It is the best option for projects that call for compact and energy-efficient solutions because to its tiny size and low power usage.

Here are its key specifications:

1. Input voltage range: 2.5 V to 5.5 V
2. Output voltage: 1.8 V to 5.0 V, selectable in 100 mV steps
3. Maximum output current: 150 mA
4. Quiescent current: 9 µA (typical)
5. Dropout voltage: 80 mV at 150 mA
6. Power supply rejection ratio (PSRR): 60 dB at 1 kHz
7. Operating temperature range: -40°C to +85°C
8. Package: SOT-23-5 


Overall, these components offer high performance, energy efficiency, dependability, and ease of integration, which is why we selected them for our project. Each component was carefully chosen to match the demands of our project, guaranteeing that it will perform as efficiently and dependably as possible.

<br>

[Microcontroller Selection](MicrocontrollerSelection.md)

The process of choosing the best microcontroller was a crucial part of our project, therefore our team had to be extremely attentive and diligent in their selection. We thoroughly and rigorously evaluated all of the solutions on the market, taking into account things like performance, power usage, cost, and system compatibility. After reducing the list of potential choices, our team settled on the microcontroller we think will provide the best performance and functionality for our project. This section offers a thorough and informative overview of our microcontroller selection procedure. 

<br>

[Software Proposal](SoftwareProposal.md)

Our project proposal calls for the creation of a software proposal that will be in charge of directing and coordinating the various elements of our hardware system. The program will be created to operate on a microcontroller and be in charge of reading, analyzing, and utilising data from sensors to control different actuators in the system. Capabilities for error handling and debugging were also included to make sure the software can run consistently and effectively. The goal of this software proposal is to offer a complete solution that exemplifies the capability and adaptability of our microcontroller in managing and coordinating our hardware system.

<br>

[Hardware Proposal](HardwareProposal.md)

The design and development of a hardware system that exemplifies the seamless integration of several components working together is part of our project proposal. Our system's electrical design is essential to ensuring that all the parts work together smoothly and efficiently. In order to create a completely functional and effective system, we want to show how various hardware elements, including  microcontrollers, sensors, actuators, and power sources, interact with one another. In addition to putting a strong emphasis on effective power management and signal processing, our design also takes reliability and safety into account. With this hardware design, we hope to offer a thorough and useful solution that can be used in a variety of industries, from automation to robotics and beyond.

<br>


[Presentation 1](Presentation1.md)

Our team produced a professionally recorded video of our project presentation in order to give a thorough overview of the development of our project and the design procedures we used. This video serves as a helpful summary of our previous work, displaying the thorough and original methods we used to develop our designs. The presentation gives a thorough breakdown of every design element and how it was created by our team, showcasing our artistic vision and technical proficiency. By presenting our product in this manner, we hope to highlight the effort and commitment that went into its development while simultaneously giving readers a clear idea of its features and usefulness.
<br>
<iframe width="640" height="360" src="https://www.youtube.com/embed/FvTgKpSFzp8" title="EGR 314 Checkpoint 1 Team 308" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<br>

[Appendix A: Team Organization](Appendix.md)
