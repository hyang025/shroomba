## Members
Haoxuan Yang, Electrical Engineering Student (2027)
hyang025@vt.edu

## Mentor
MENTOR NAME HERE

## Current Status
PROPOSAL

## Project Overview

Shroomba is a control system for gourmet mushroom growing at home. The system provides an ideal environment for mushrooms by controlling temperature, humidity and carbon dioxide concentration. The system will include a control PCB, sensors and actuators which are vent fans, a ultrasonic mister, a LED light strip, servos, and a peltier cooler. The system should be integrated with Home Assistant OS allowing remote control and monitoring over the internet. 

The goal of the project is to build a functional prototype that can automatically regulate the growing environment while also collecting useful data for future improvements.

## Educational Value Added

This project will help the student learn PCB design, noise filtering, collecting data with sensors, powering and working with actuators, programming embedded systems, low power optimization, 3D printing and modeling, building and controlling physical systems.

## Tasks
- Research environmental requirements for selected mushroom species. Initial targets are king oyster, lion’s mane and hen of the woods in progressing difficulty.
- Research safety practices regarding potential mold and spores exposure and using electrical components in a humid environment.
- Define target ranges for temperature, humidity, CO2 concentration, and lighting.
- Select sensors for temperature, humidity, and CO2 measurement.
- Select actuators for ventilation, vent opening control, humidification, lighting, and cooling.
- Design the system architecture, including power distribution, microcontroller selection, sensor interfaces, and actuator drivers.
- Design a custom PCB for the controller.
- Develop embedded firmware for sensor reading, actuator control, safety guardrails, and communication.
- Integrate the controller with Home Assistant using MQTT, ESPHome, or another suitable method.
- Design and 3D print mechanical parts such as sensor mounts, fan ducts, vent flaps, and mister mounts.
- Build a prototype growing chamber in a insulated styrofoam box
- Test each subsystem individually before full integration.
- Experiment and adjust control logic for humidity, temperature, and CO2 regulation.
- Grow mushrooms, log data and evaluate system performance over time such as its ability to keep the parameters within desired range.
- Document design decisions, failures, revisions, and results for future improvement.

## Design Decisions
Function
- The system uses one storebought pre-colonized block of a single kind of mushroom at a time.
- The system is powered with a storebought 12V DC power supply unit that uses 120V AC, building a reliable 120V AC-DC converter is out of scope for this project.
- The control system should be tested on a breadboard and the power system tested with a secure wiring before being integrated on a PCB.
- The system is placed indoors with assumed room temperature of 24 degrees celcius.
- A Peltier cooler is used because it is compact, low-voltage, and practical for the scale of the project.
Performance
- The system should prioritize power saving and consume as little power as possible during idle.
- The system should use actuators only when needed to reduce unnecessary power consumption.
- The system should use intermittent ventilation instead of constant ventilation to reduce cooling and humidity loss.
- The system should log temperature, humidity, and CO2 data so performance can be evaluated over time.
Safety
- Main control electronics should be placed outside the humid growing chamber when possible.
- Electronic components should be protected from moisture, condensation and spores.
- The system should be protected from current and voltage spikes from actuators.
- The system should include fuses or current protection for actuator power lines.
- The system's firmware should detect and report common failure patterns and enter a safe state in the event of a potential short or actuator blockage.
- Ventilation system should be filtered to contain spores and prevent containmination.
- <more..> 

## Design Misc
- Buy a premade buck converter to drop 12V PSU output down to 5V rail for MCU for prototyping, build it later.
<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Steps for Documenting Your Design Process

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## BOM + Component Cost

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Timeline

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Useful Links

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Log

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->
