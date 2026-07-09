# STACK Sandbox Environment

This repository contains a local sandbox environment for testing and developing mathematical questions using the [STACK](https://github.com/maths/moodle-qtype_stack) assessment system. 

It is pre-configured to run with desktop Maxima and wxMaxima on macOS.

## Contents
- **wxMaxima Sandbox (`sandbox.wxm`)**: A pre-configured wxMaxima batch file that loads all required STACK Maxima libraries (such as assessment, descriptive, intervals, etc.).
- **STACK Source**: Contains the full STACK Maxima libraries and configuration files needed to evaluate algebraic expressions locally without needing a Moodle server.

## Getting Started

1. Ensure you have **Maxima**, **wxMaxima**, and **gnuplot** installed. 
   *(On macOS, this can be done via `brew install wxmaxima gnuplot`)*.
2. Open `sandbox.wxm` in wxMaxima.
3. If necessary, configure your Maxima path in wxMaxima Preferences (`/opt/homebrew/bin/maxima`).
4. Select **Cell -> Evaluate All** to load the STACK libraries and run your test cases!
