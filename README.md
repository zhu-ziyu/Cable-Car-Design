# Cable Car Design Project

Welcome to the Cable Car Design Project repository! This project uses AutoDesk Inventor to design a cable car that travels along a 1/8-inch diameter steel cable at a speed of 7 ft/s. This project is part of our school assignment and will be completed in groups of two.
The final version is determined by numbers – the higher the number, the newer the version.
---

## Team Members

- **Sam**
- **Haniyah**

---


## DR
https://docs.google.com/document/d/1cQCYeWfgsGGdHgYkLYSboqoXo5m43t7FvCb4pFESDME/edit?tab=t.0
---


## Table of Contents

- [Project Overview](#project-overview)
- [Project Goals](#project-goals)
- [Design Process (S.P.I.C.E.)](#design-process-spice)
- [Project Timeline](#project-timeline)
- [Resources & References](#resources--references)
- [To-Do List](#to-do-list)
- [License](#license)

---

## Project Overview

In this project, our goal is to design and build a cable car system that:
- Travels along a 1/8-inch (0.125 in) steel cable.
- Moves at a constant speed of 7 ft/s.
- Balances properly on the cable, ensuring that the center of gravity and the centroidal axis are correctly aligned.
- Incorporates a gear train mechanism that includes meshing gears, ball bearings for reduced friction, and other necessary components (some parts can be 3D printed from GCode files).

The project will be carried out over approximately 4 weeks, with roughly 3 hours of design work allocated per week. In the final stage, the designs will be 3D printed, assembled, and tested to produce a functional prototype.

---

## Project Goals

- **Speed:** Achieve a cable car speed of 7 ft/s.
- **Balance:** Ensure the cable car maintains balance on a 1/8-inch diameter steel cable.
- **Gear Train:** Design and assemble a gear mechanism that meshes together smoothly, using ball bearings to reduce friction.
- **3D Printing:** Produce essential custom parts via 3D printing (uploading GCode files to the designated folder).
- **Travel Distance:** Allow the cable car to move 30 cm in both directions during testing.

---

## Design Process (S.P.I.C.E.)

We will follow the S.P.I.C.E. model for our design process:

1. **S - Situation**  
   - Understand the project requirements and constraints.
   - Identify key parameters such as cable diameter, cable car speed, and balance considerations.

2. **P - Problem Definition**  
   - Define the design challenges.
   - Establish initial specifications for gear ratios, center of gravity, and material properties.

3. **I - Ideation**  
   - Brainstorm multiple design ideas and sketch initial concepts.
   - Compare options and select the most feasible approach.

4. **C - Create**  
   - Develop detailed designs using AutoDesk Inventor.
   - Prepare files for 3D printing and begin assembling prototypes.

5. **E - Evaluate**  
   - Test the prototype on the cable.
   - Identify improvements and iterate on the design.
   - Finalize the design report based on testing and feedback.

---

## Project Timeline

### March

- **March 18:** Project kick-off, team formation, and project introduction.
- **March 19:** Explore the Kidder Parts kit; complete the S and P sections of the design report.
- **March 20-28:** Begin ideation phase; develop initial sketches and conceptual models.

### April

- **Early April:** Transition to the Create phase, start detailed 3D modeling and 3D printing essential parts.
- **Mid-April:** Assemble and test the cable car; refine designs based on performance.
- **Late April:** Finalize the design report and prepare for the project presentation.

---

## Resources & References

- **Example Cable Car Video:** [Watch Here](#)
- **Cable Car Assignment Sheet:** [Read Here](#)
- **Engineering Design Process Video (Taco Party):** [Watch Here](#)
- **S.P.I.C.E. Prezi Presentation:** [Watch Here](#)
- **IRHS Student Work – Cable Car Example:** [View Here](#)
- **IRHS Student S.P.I.C.E. Report:** [View Here](#)

*Additional resources and parts list can be found in the repository.*

---

## To-Do List

- [ ] **Read and Understand Project Requirements**
  - Review the assignment sheet and watch the provided videos.
- [ ] **Team Coordination**
  - Confirm group members (Sam and Haniyah) and share initial ideas.
- [ ] **Initial Design Report (S & P)**
  - Document the Situation and Problem Definition sections.
- [ ] **Brainstorming & Ideation**
  - Create sketches and initial design concepts.
- [ ] **3D Modeling and Printing**
  - Develop detailed models using AutoDesk Inventor.
  - Prepare and upload GCode files for 3D printing.
- [ ] **Assembly and Testing**
  - Assemble the prototype and test balance and speed on the cable.
- [ ] **Final Report and Presentation**
  - Compile the S.P.I.C.E. report and prepare the final presentation.

---

## License

This project is for educational purposes. Please feel free to use and modify the materials provided here for learning and collaborative development. If you use any part of this project, kindly attribute the original source.

---

# High School Cable Car Project - Concept

Welcome to the concept documentation for our high school cable car project. This project demonstrates basic mechanical principles using a small DC motor, gears, and pulleys. The system is designed to run along a 3mm steel cable that spans across the classroom.

---

## Team Members

- **Sam**
- **Haniyah**

---

## Project Overview

The cable car project is built around a simple yet effective design:
- A **3mm steel cable** is stretched tightly across the classroom.
- **Two pulleys** are used to interface with the cable:
  - A **drive pulley** connected to a shaft, which is powered by a DC motor via a gear train.
  - An **idler pulley** that stabilizes the cable car on the cable.
- A **small DC motor** drives a gear train that increases torque and controls the movement of the cable car.
- The design focuses on achieving smooth movement along the cable with minimal friction and reliable traction.

---

## System Components

### 1. Pulley Mechanism
- **Drive Pulley:** 
  - Attached to the drive shaft.
  - Designed with a groove that matches the 3mm cable, ensuring proper grip.
- **Idler Pulley:**
  - Freely rotates to maintain cable alignment and support the cable car's weight.
- Both pulleys are aligned parallel to each other to ensure stable movement.

### 2. Drive Mechanism
- **DC Motor:**
  - A small DC motor (6–12V) provides the required rotational power.
  - Can be controlled via a basic on/off switch or a more advanced motor driver for speed control.
- **Gear Train:**
  - A small pinion gear on the motor shaft meshes with a larger spur gear on the drive shaft.
  - The gear reduction increases torque and ensures that the drive pulley rotates with sufficient power.
- **Drive Shaft:**
  - Connects the gear train to the drive pulley.
  - Bearings or bushings are used at the shaft's mounting points to reduce friction.

### 3. Structural Design
- **Chassis/Frame:**
  - A lightweight frame houses the motor, gears, and battery pack.
  - Designed to maintain a low center of gravity to prevent tipping.
- **Cable Interface:**
  - The chassis is built to allow the cable car to hang freely from the 3mm steel cable.
  - Ensures minimal friction and proper alignment during movement.

---

## Operation & Control

### Power Supply
- A battery pack (e.g., 6V or 9V) or a bench power supply powers the DC motor.
- Optional components include an H-Bridge or PWM controller for more advanced motor control, enabling forward/reverse movement or speed regulation.

### Control System
- **Basic Control:** 
  - A simple switch to turn the motor on or off.
- **Advanced Control (Optional):**
  - A motor driver can be added to allow for variable speed control or reversing the motor’s direction.
  - Limit switches may be incorporated at the cable endpoints to stop or reverse the cable car automatically.

---

## Safety & Practical Considerations

- **Center of Gravity:**  
  Ensure that heavy components (motor, battery) are placed low within the chassis to maintain balance.
  
- **Material Selection:**  
  Use lightweight yet sturdy materials (e.g., 3D-printed plastics, thin plywood, or acrylic) to construct the chassis and pulley supports.

- **Maintenance:**  
  Design the system so that gears, pulleys, and the drive shaft can be easily accessed for adjustments, lubrication, or replacement if needed.

---

## Final Thoughts

This project serves as an engaging hands-on experiment to explore:
- Mechanical power transmission (via gears and pulleys).
- Basic DC motor control and circuitry.
- The importance of structural balance and material selection.

Feel free to adjust or expand upon this concept to better suit your classroom’s resources and learning goals.

---

Happy designing!

