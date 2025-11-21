# Practica Investigativa 1 — CrossDot in Maude

## Overview
This repository contains the formal specification of the **CrossDot** game using the Maude specification language. The project includes the game model, several strategy modules, and a test file with example commands for simulation and verification.

## Requirements
- **Maude** (latest stable version)  
  Download: https://github.com/maude-lang/Maude

## Repository Structure
/maude

CROSSDOT-SYNTAX.maude # Core game specification
CROSSDOT-PROPERTIES # Commands to run the verifiable properties
CROSSDOT-STRATEGIES # Strategy module, strategies defined by rewriting rules 
Test.maude # Example commands (simulation, search, etc.)

## How to Run
1. Open Maude in your terminal.
2. Load the "load" file:
   load load.maude
3. Run any of the example commands included inside "Test.maude"

## Notes
- The **Test.maude** file provides ready-to-run commands for exploring the model.  
- All strategies and configurations are modular, allowing easy extension.
   
