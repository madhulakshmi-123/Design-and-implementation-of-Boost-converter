# Design-and-implementation-of-Buck-converter
📌 Project Overview

This project presents the design and simulation of a DC-DC Boost Converter using MATLAB/Simulink (Simscape Power Systems).
The converter steps up a low DC input voltage to a higher output voltage using switching techniques and PWM control.

The model is designed for applications such as:

Electric Vehicles (EV)

Renewable Energy Systems

Battery-powered systems

DC microgrids

⚙️ Software Used

MATLAB

Simulink

Simscape Electrical

Powergui (Discrete mode)

🔧 System Components

DC Voltage Source

Inductor

IGBT/MOSFET Switch

Diode

Output Capacitor

Resistive Load

PWM Pulse Generator

Voltage Measurement Blocks

Scope & Display

🔁 Working Principle

The boost converter operates in two modes:

1️⃣ Switch ON Mode

Inductor stores energy from the DC source

Diode becomes reverse biased

2️⃣ Switch OFF Mode

Inductor releases stored energy

Energy adds to input voltage

Output voltage increases

The output voltage is controlled by adjusting the duty cycle of the PWM signal.

📊 Simulation Parameters

Solver Type: Discrete

Sample Time: 5e-05 s

Switching controlled using Pulse Generator

Output voltage observed using Scope & Display

📈 Results

Output voltage is boosted higher than input voltage

Stable waveform observed after transient period

Output voltage depends on duty cycle
