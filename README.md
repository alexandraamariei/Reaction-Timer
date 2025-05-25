# Reaction-Timer
This repository contains the implementation of a simple reaction game on an FPGA device, using SystemVerilog. The game measures the user's reaction time to an LED turning on, displaying the result on a screen.

This project implements a digital reaction game on an FPGA board. The game works as follows:
1. The user presses a button to start the game.
2. After a random (or fixed, configurable) waiting period, an LED turns on.
3. The user must press the button as quickly as possible after the LED lights up.
4. The reaction time is calculated and displayed on a screen.
It practically functions as a stopwatch.
