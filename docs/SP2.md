---
marp: true
title: Virtual Conveyor System Simulation
theme: default
paginate: true
---

## Virtual Conveyor System Simulation - Austin Shelton

---

## Project Problem

Modern manufacturing relies heavily on conveyor systems for efficient product movement.  
However, physical testing and operator training can be expensive and risky.

---

## Sprint 2 Deliverables

Sprint 2 Goals:

- Continue development of the conveyor system for full integration
  - Complete the remaining conveyor segments and material flow logic
  - Ensure all sensors, actuators, and item tracking are synchronized
  - Verify rung logic across conveyor zones for start/stop and transfer states

---

- Start HMI work for virtual control stations
  - Design the HMI layout, including remote start/stop, mode selection, and status indicators
  - Build interactive screens for conveyor control, fault reset, and process visualization
  - Add live feedback for sensor states, motor status, and item positions

--- 

- Enable user interaction between PLC logic and FactoryTalk
  - Set up communication between the PLC project and FactoryTalk runtime
  - Map PLC tags to HMI controls and display values from the conveyor system
  - Test operator inputs from FactoryTalk and confirm PLC responds correctly

---

## Sprint 2 Focus

Key areas:
- Finalize PLC and conveyor integration with complete zone handoff logic
- Build interactive HMI controls that reflect real-time system state
- Test communication paths between PLC logic and FactoryTalk reliably
- Improve usability, simulation realism, and operator feedback
- Add fault detection and recovery workflows for more robust testing

---

## Project Requirements

LoC: 1200 lines of code / 19 Routines 

Features planned: 8/8

Requirements targeted: 8/8

---


## Status Notes

What to watch:
- Integration testing across systems
- Full HMI control response and feedback
- Fault handling during user interaction

---

# Questions?

Thank you for your time!
