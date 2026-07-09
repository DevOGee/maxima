# STACK Sandbox Environment

This repository contains a local sandbox environment for testing and developing STEM, Computer Science, and mathematical workflows using the [STACK](https://github.com/maths/moodle-qtype_stack) assessment system. 

Beyond core mathematics, this environment acts as an exploratory platform for computational logic, algorithmic design, JavaScript integrations, data parsing, and other computer science applications using algebraic computational models. It is pre-configured to run with desktop Maxima and wxMaxima on macOS.

## Contents
- **wxMaxima Sandbox (`sandbox.wxm`)**: A pre-configured wxMaxima batch file that loads all required STACK libraries (such as assessment algorithms, logic models, descriptive data structures, etc.).
- **STACK Source**: Contains the full STACK source code and configuration files needed to evaluate algebraic expressions, execute parsing algorithms, and test computational logic locally without needing a remote Moodle server.

## Getting Started

1. Ensure you have **Maxima**, **wxMaxima**, and **gnuplot** installed. 
   *(On macOS, this can be done via `brew install wxmaxima gnuplot`)*.
2. Open `sandbox.wxm` in wxMaxima.
3. If necessary, configure your Maxima executable path in wxMaxima Preferences (`/opt/homebrew/bin/maxima`).
4. Select **Cell -> Evaluate All** to compile the STACK libraries and run your test scripts/code cases!
