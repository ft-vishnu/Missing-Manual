# Multi-Drone Swarming and Coordination with Tello

Learn how to coordinate multiple Tello drones using Python and DJITelloPy. Build simple swarm programs, synchronize flight sequences, experiment with geometric formations, and complete coordinated drone challenges.

This course introduces multi-drone programming through hands-on activities designed around the capabilities and limitations of Tello drones.

## Course Objectives

By completing this course, learners will be able to:

- Understand the basic concepts of drone swarming.
- Connect and manage multiple Tello drones using Python.
- Send commands to individual drones and coordinate their actions.
- Execute synchronized and sequential flight commands.
- Plan simple geometric formations.
- Implement basic leader-follower behaviour.
- Assign different tasks to different drones.
- Build and test coordinated multi-drone missions.

## Course Syllabus

### 01. Introduction to Tello Swarming

- What is drone swarming?
- How multiple drones can work together
- Applications of educational drone swarms
- Single-drone control vs. multi-drone control
- Introduction to Tello swarm programming
- Understanding the capabilities and limitations of Tello drones
- Exploring the DJITelloPy swarm example

**Practical activity:** Simulate a group of drones performing a coordinated movement sequence.

### 02. Preparing Multiple Tello Drones

- Setting up Python and DJITelloPy
- Understanding Tello Wi-Fi connections
- Connecting multiple drones to a computer
- Understanding drone IP addresses and connection settings
- Assigning names or identifiers to drones in Python
- Establishing and testing individual connections
- Understanding network limitations and connection failures

**Practical activity:** Write a program that maintains separate references to multiple Tello drones and checks their connections.

*Hardware note: Multi-Tello connectivity depends on the drone models, Wi-Fi adapters, network configuration, and computer. Verify that your setup can maintain the required connections before attempting coordinated flight.*

### 03. Controlling Multiple Drones with Python

- Managing multiple Tello objects
- Sending commands to a selected drone
- Reusing functions for multiple drones
- Taking off and landing individual drones
- Sending different movement commands to different drones
- Executing commands sequentially
- Understanding delays and command-response timing

**Practical activity:** Program two drones to perform different movement sequences.

### 04. Coordinated and Synchronized Flight

- Understanding coordinated movement
- Starting flight sequences in a planned order
- Coordinating takeoff and landing
- Executing shared movement sequences
- Using timing to coordinate commands
- Understanding sequential execution vs. simultaneous command dispatch
- Handling delayed responses and failed commands

**Practical activity:** Program two drones to take off, perform a planned movement sequence, and land in a coordinated mission.

*Synchronization is approximate unless the hardware and software provide reliable timing and feedback. Sending commands together does not guarantee perfectly simultaneous physical movement.*

### 05. Formation Planning

- What is a drone formation?
- Representing drone positions on a 2D grid
- Understanding relative positions
- Planning a line formation
- Planning a V-shaped formation
- Planning triangle and square arrangements
- Assigning each drone a target position
- Converting simple formation plans into flight commands

**Practical activity:** Create a formation planner that assigns target positions to two or more simulated drones.

Physical formation exercises should begin with stationary or widely separated target positions before attempting any movement.

### 06. Leader-Follower Flight

- Understanding leader-follower behaviour
- Assigning leader and follower roles
- Planning a leader's movement sequence
- Defining follower movement sequences
- Maintaining approximate relative positions
- Coordinating turns and directional movements
- Understanding the limitations of open-loop following

**Practical activity:** Program a leader drone and one follower drone to execute a predefined sequence with suitable spacing.

This module uses predefined commands rather than advanced autonomous tracking or continuous formation control.

### 07. Multi-Drone Challenges

- Assigning different tasks to different drones
- Dividing a mission into checkpoints
- Coordinating routes and movement sequences
- Planning simple search patterns
- Performing sequential area visits
- Combining individual and shared commands
- Tracking mission progress in Python

**Practical activity:** Assign two drones different checkpoints and coordinate their movements to complete a shared mission.

### 08. Introduction to the Tello Swarm Example

- Exploring the DJITelloPy `simple-swarm.py` example
- Understanding the swarm class and its purpose
- Connecting to a group of drones
- Sending commands through the swarm interface
- Understanding shared commands and sequential commands
- Adapting example code for simple missions
- Debugging connection and execution problems

**Practical activity:** Run, understand, and modify a basic swarm program for a small coordinated mission.

### 09. Final Project: Tello Swarm Mission

Build a Python program that coordinates multiple Tello drones through a predefined mission.

The project should include:

- Identifying and connecting to the participating drones
- Assigning each drone a role
- Coordinating takeoff and landing
- Executing a sequence of planned movements
- Creating a simple formation or checkpoint mission
- Monitoring mission execution
- Handling basic communication failures
- Providing a clear landing and shutdown procedure

Learners should first test the program using simulated drone positions or a no-flight command-planning mode, then test individual commands, and finally attempt a carefully controlled multi-drone mission.

## Learning Resources

- [DJITelloPy GitHub Repository](https://github.com/damiafuentes/DJITelloPy)
- [DJITelloPy Documentation](https://djitellopy.readthedocs.io/en/latest/)
- [DJITelloPy Examples](https://github.com/damiafuentes/DJITelloPy/tree/master/examples)
- [DJITelloPy Simple Swarm Example](https://github.com/damiafuentes/DJITelloPy/blob/master/examples/simple-swarm.py)
- [Tello SDK Documentation](https://dl-cdn.ryzerobotics.com/downloads/tello/20180910/Tello%20SDK%20Documentation%20EN_1.3.pdf)

## Prerequisites

- Basic Python programming knowledge.
- Familiarity with functions, loops, lists, and dictionaries.
- Completion of Drone Fundamentals and Autonomous Flight Programming is recommended.
- Two or more compatible Tello drones for physical swarm activities.

Learners can complete the formation-planning and command-coordination exercises without owning multiple drones by using simulated positions and mission sequences.

## Safety Guidelines

- Test every drone individually before attempting group flights.
- Begin with simple, low-risk movements in a spacious, controlled area.
- Maintain sufficient separation between drones.
- Keep all drones within visual contact.
- Check batteries, Wi-Fi connectivity, and landing areas before takeoff.
- Provide a clear way to land each drone if coordination fails.
- Avoid close-proximity formations until basic movements have been tested reliably.


**Connect multiple drones. Coordinate their movements. Build your first drone swarm.**