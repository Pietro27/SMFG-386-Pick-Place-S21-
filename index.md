# SMFG 386 – Pick and Place Project
Spring 2021, California State University, Chico

## Table of Contents
1. Project Team
2. Project Management
3. Requirements
4. Brainstorming
5. Software
6. Hardware
7. System
8. Simulation and Digital Twin

## 1. Project Team
#### Project Advisor:
Hasan Sinan Bank

#### Team Members:
Pietro Ruggiero, Justin Bos, Esiah Smith, Dave Gorans, Clint Holister

## 2. Project Management
#### Executive Summary
As the world continues to advance technologically and almost everything containing computer components, the manufacturing of PCBs and their components needs to continue and evolve to keep up with the demand.
In this project, the team will design a pick and place machine to pick components for building electronic prototyping boards. This machine will automate, simplify, and speed up the production process while minimizing the potential errors. These types of machines are specifically used to pick up and place surface-mounted devices onto a printed circuit-board.

#### PM @ RD Project Preparation
The project manager will organize the team to ensure that requirements and deadlines are met. He will ensure that their in constant and clear communication between team members as to avoid any errors or delays.

#### Project Documentation and Preparation of Infrastructure
For this project, we plan to control the robot using an Arduino. The coding will be designed using CodeSys.
The CAD and physical structure of the robot were prepared for the team by our project advisor.

#### The Completion of the Project Setup
blank blank blank blank blank blank blank blank blank blank

## 3. Requirements
#### 2.1 System Specific Requirements
2.1.1 Identify and engineer the HW and SW requirements
- Able to move in the X, Y, Z axis
- Able to lift a component securely and place it on a board gently

2.1.2 Identify and engineer the requirements of the fabrication
- A secure structure able to house the desired robot
- Location that will hold the board and desired components

#### 2.2 System Test Plan
2.2.1 Scenario Definition
- The scenario for this project would consist of a circuit board being placed on one base and the components on a different base. The robot would then come down, pick up the component, move up and over the board, come down, and gently place the component onto the board to then later be soldered.

2.2.2 Integration Test Plan
- blank blank blank

## 4. Brainstorming
A gantry style pick and place machine consists of three stepper motors and it will be used to move the end-effector along the X, Y, and Z axis of the machine. As indicated in the physical system diagram below, there is a vacuum nozzle attached to the end-effector that picks up each component and then moves them over the designated position on the electronic prototyping board. The components are then gently placed onto the board at which point, once completed, the user will remove the board and place a new one in its place along with additional components if needed.

The design of the pick and place machine incorporates two bases with designated slots for each individual component and boards. On the left side of the machine would sit the components in specified locations and on the right side would sit the boards. By doing so, we are able to simplify the system requirement by preprogramming the end-effector to always return to and move to designated locations. Various other machines can be integrated with this one in order to reduce the amount of human interaction if needed. 

### Conceptual Physical System
##### Top View
![image](https://user-images.githubusercontent.com/80643856/119094644-275cfa00-b9c6-11eb-9089-6bfad969cbe6.png)

##### Side View
![image](https://user-images.githubusercontent.com/80643856/119094677-32178f00-b9c6-11eb-9908-a240ad9cdfb5.png)

## 5. Software
Code code code code code

## 6. Hardware
#### Bill of Materials
[BOM Download](https://github.com/Pietro27/SMFG-386-Pick-Place-S21-/files/6519613/Bill.of.Materials.xlsx)

##### Isometric View
![image](https://user-images.githubusercontent.com/80643856/119072661-b7884880-b9a0-11eb-9a16-bb77ba2844f7.png)

##### Front View
![image](https://user-images.githubusercontent.com/80643856/119072715-ce2e9f80-b9a0-11eb-8946-a5f0d813f139.png)

##### Right View
![image](https://user-images.githubusercontent.com/80643856/119072761-e999aa80-b9a0-11eb-8f9c-c39de218aac9.png)

##### Top View
![image](https://user-images.githubusercontent.com/80643856/119072821-03d38880-b9a1-11eb-8797-b3a022a31a48.png)

## 7. System
##### Program Logic
![image](https://user-images.githubusercontent.com/80643856/119096993-18c41200-b9c9-11eb-901a-a3f4067b143b.png)

##### Flow of Machine Operation
![image](https://user-images.githubusercontent.com/80643856/119097068-2d080f00-b9c9-11eb-9773-c669b6cf02c5.png)

##### Physical Viewpoint
![image](https://user-images.githubusercontent.com/80643856/119097375-7e180300-b9c9-11eb-8c60-9d1b21d82c73.png)

##### Capabilities Database
![image](https://user-images.githubusercontent.com/80643856/119102337-c4bc2c00-b9ce-11eb-957e-f4dc23e2498c.png)

## 8. Simulation
#### CAD Model
[OnShape Pick-and-Place CAD Model](https://cad.onshape.com/documents/6252e15e970ac1938780f928/w/20633151d95dba67da3a3823/e/bd24fccf74d4b5e793805942)

----------------------------------------------------------------------------------------------------------
**Bold** and _Italic_ and `Code` text


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
