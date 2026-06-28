# Python Fundamentals for DevOps Automation

## Project Overview
This repository contains a structured laboratory series designed to master core Python programming components. From a DevOps and Cloud Infrastructure perspective, it bridges the gap between basic programming and practical automation—demonstrating how core data structures, algorithms, and logical conditions are applied to handle system configurations, process automation variables, parse dynamic network resources, and manage cloud state elements.

## Architecture Diagram

```text
+----------------------------------------------------------------------------+
|                          AUTOMATION LOGIC FLOW                             |
+----------------------------------------------------------------------------+
|                                                                            |
|  [ Developer ] ---> Writes Python Scripts (Variables, Loops, Conditions)   |
|                                     |                                      |
|                                     v                                      |
|  [ Input Data ] --> AWS Regions, Target IPs, Configuration Dictionaries    |
|                                     |                                      |
|                                     v                                      |
|  [ Core Logic ] --> 1. Data Type Validation (String, Integer, Float)       |
|                     2. Structural Execution (Loops, If/Else Conditions)     |
|                     3. Modular Automation (Functions, OOP Classes)         |
|                                     |                                      |
|                                     v                                      |
|  [ Output ]    ---> Validated Infrastructure Metrics & Automation States   |
|                                                                            |
+----------------------------------------------------------------------------+

## Tools Used
- **Language:** Python 3.x
- **Development Tooling:** Git & GitHub
- **Core Libraries:** Native Python Built-ins (Strings, Numerics, Lists, Dictionaries)

## Features
- **Data Infrastructure Basics:** Comprehensive handling of core data types (`str`, `int`, `float`, `bool`) mapped to infrastructure variables (e.g., AWS Region tags, target IP parsing, branch strings).
- **Control Flow & Automation Logic:** Implementations of conditional checks, arithmetic evaluation, comparison blocks, and complex logical operators mimicking system health-checks.
- **Dynamic Data Structures:** Manipulation of arrays and configuration tables via native Python lists and dictionary types.
- **Modularity & OOP:** Reusable script design featuring object functions, functional execution blocks, and object-oriented class instances mimicking real-world platform assets.

## Local Setup
To run these exercises locally and inspect the programmatic output, use the following execution steps:

1. Clone the repository to your environment:
   ```bash
   git clone [https://github.com/shehabkazi-blip/python-genius.git](https://github.com/shehabkazi-blip/python-genius.git)
   cd python-genius
Navigate to the exercises directory:

Bash
cd Lab-Exercises
Execute any specific module directly using the python interpreter:

Bash
python 1.data-types-basics.py
python 3.dictionary-data-type.py
Deployment Steps
Script Validation Workflow
While these scripts run locally as system administrative or operational logic, their syntax consistency can be validated inside an orchestration pipeline:

Push structural logic changes up to the remote staging/production repositories.

An integrated CI runner evaluates the script suite for standard syntax correctness using native interpreter testing.

Once validated, verified administrative scripts can be securely baked into custom system automation jobs, server boot hooks, or Cron utilities.

Environment Variables
(No production credentials or secret authorization tokens are required to evaluate this local logic suite.)

Screenshots
Tip: Run a script in your local environment, capture a terminal output image showing the parsed variables, and save it in your images/ directory.

1. Script Parsing & Output Verification
Troubleshooting Notes
Problem: SyntaxError: invalid syntax

Root Cause: Attempting to evaluate Python 3 code blocks utilizing an older, legacy Python 2 executable stack.

Solution: Explicitly invoke the modern runtime wrapper directly on your interface by triggering python3 script_name.py.

Problem: FileNotFoundError during subdirectory execution

Root Cause: Running an absolute script reference without properly stepping into the nested Lab-Exercises/ file group.

Solution: Always target your relative workspace index by running cd Lab-Exercises before executing targeted automation modules.

What I Learned
Developing this matrix of logical components refined my proficiency in treating infrastructure purely as programmable components. I learned how to cleanly isolate dynamic cloud attributes within custom configurations, manage environmental criteria checks, structure parsing routines for high-velocity logs, and establish predictable operational scripts essential for production system configurations.
