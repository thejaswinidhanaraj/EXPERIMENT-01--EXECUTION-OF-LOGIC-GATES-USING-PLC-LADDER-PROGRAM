 # EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM
 # NAME : THEJASWINI D
 # REGISTER NUMBER : 212223110059
 # DEPARTMENT : B.E.CSE(IOT)
 # YEAR : III
 # DATE : 30.01.2026

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:
## AND GATE:
 <img width="327" height="250" alt="image" src="https://github.com/user-attachments/assets/5cf9dd15-a6e2-4d1e-880d-d113ef1f2d0d" />
 
## OR GATE:
 <img width="324" height="254" alt="image" src="https://github.com/user-attachments/assets/1e6935d4-47f8-4452-aecb-05fe4197dac7" />
 
## NOT GATE:
 <img width="214" height="159" alt="image" src="https://github.com/user-attachments/assets/8321a8ed-43b3-4e1b-88de-a151e3f22772" />
 
## NAND GATE:
 <img width="333" height="250" alt="image" src="https://github.com/user-attachments/assets/ebaa3105-cfe5-474e-b809-6c83415a019a" />
 
## NOR GATE:
 <img width="330" height="249" alt="image" src="https://github.com/user-attachments/assets/7fc0c378-9e21-42bb-bd6a-e950b9323c17" />
 
## XOR GATE:
 <img width="326" height="248" alt="image" src="https://github.com/user-attachments/assets/99d7a304-789c-4570-91a9-685e225d0996" />

# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS:
## AND GATE:
<img width="700" height="125" alt="Screenshot 2026-01-27 115053" src="https://github.com/user-attachments/assets/6aa44777-aa4b-472e-a4f4-b5e5a75a0f28" />

## OR GATE:
<img width="701" height="209" alt="Screenshot 2026-01-27 115104" src="https://github.com/user-attachments/assets/95b50144-0418-43c0-8217-f87991c1000b" />

## NOT GATE:
<img width="645" height="141" alt="Screenshot 2026-01-27 115119" src="https://github.com/user-attachments/assets/1b1851ce-4a80-482b-b3ed-8b0c7576c9ec" />

## NAND GATE:
<img width="679" height="133" alt="Screenshot 2026-01-27 115142" src="https://github.com/user-attachments/assets/ebddf1d6-357e-4121-bebf-55332ab2db43" />
<img width="667" height="130" alt="Screenshot 2026-01-27 115154" src="https://github.com/user-attachments/assets/ba24ac62-ee5c-4279-9f4b-c653665b4123" />

## NOR GATE:
<img width="665" height="134" alt="Screenshot 2026-01-27 115205" src="https://github.com/user-attachments/assets/55da8104-35a3-4b6e-8016-5f83f2ab332d" />
<img width="695" height="130" alt="Screenshot 2026-01-27 115213" src="https://github.com/user-attachments/assets/455fb204-f7d7-43a1-8750-41896a74e80a" />

## XOR GATE:
<img width="683" height="246" alt="Screenshot 2026-01-27 115221" src="https://github.com/user-attachments/assets/528f18c9-051f-4dc3-aa55-fa7fe768e961" />

## DEVICE MONITOR TABLE:
<img width="1919" height="1021" alt="Screenshot 2026-01-27 114915" src="https://github.com/user-attachments/assets/185ce13a-8eac-4acd-9dea-bb8799e53ee4" />

<img width="1916" height="1019" alt="Screenshot 2026-01-27 115004" src="https://github.com/user-attachments/assets/bef08a12-aca7-403d-8062-b186a2d63ca8" />

<img width="1906" height="995" alt="Screenshot 2026-01-27 115020" src="https://github.com/user-attachments/assets/7b62d38a-fea6-40d7-859a-a6439f8d2a0b" />

<img width="1919" height="1006" alt="Screenshot 2026-01-27 115041" src="https://github.com/user-attachments/assets/38d3e523-1006-432b-8863-3bcc146582dc" />


# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
