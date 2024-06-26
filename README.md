# Dickinson College Course Time-Slot Scheduling Optimization

This repository contains the source code for a research project that optimizes the course time-slot schedule at Dickinson College. I worked on this project for whole 2023-2024 academic year with Professor Dick Forrester.

## Project Background

Dickinson College has relied on the same course time slots, which define the allowable days and times courses can be offered, for nearly two decades. While this schedule has served the college well, there's a desire to explore possibilities for increasing the number of 75-minute time slots and common meeting hours. For more information, please read the Research Document.

## Solution

This project aims to create and implement a linear integer programming model to generate alternative optimal course time-slot schedules. The model incorporates constraints that enforce existing college scheduling rules. The follow picture is a sample schedule generated by the implementation of the model:
<img src="https://github.com/infantlikesprogramming/College-Course-Time-Slot-Scheduling/blob/main/sample%20output.png" alt="sample schedule" width="900"/>


## Dependencies
* Currently the Jupyter Notebook file only runs on Windows. If you want to run it in MacOS please install and import the MacOS version of Tkinter
* Python, Jupyter Notebook
* Since the model is solved using Gurobi Optimizer, it should be installed in your machine. You may use this link for guidance: "https://support.gurobi.com/hc/en-us/articles/4534161999889-How-do-I-install-Gurobi-Optimizer". You will also need a license to run our model. You may consult the following link for that: "https://support.gurobi.com/hc/en-us/articles/12684663118993-How-do-I-obtain-a-Gurobi-license".
* You will need to install gurobipy, tkinter, numpy, and ImageGrab (if you plan to automatically take screenshot).

## Installation

```bash
# gurobipy
pip install gurobipy

# tkinter
pip install tkinter

# numpy
pip install numpy

# ImageGrab
pip install ImageGrab
