# IS2101-InterruptController-NNM24IS219
## Description

This Java program simulates an Interrupt Controller managing interrupts from multiple I/O devices — Keyboard, Mouse, and Printer — with priority-based handling and masking support.
It demonstrates how real systems prioritize interrupts, handle multiple requests, and allow users to enable or disable specific device interrupts during runtime.

Devices can be masked/unmasked to enable or disable interrupts.

Interrupts are handled according to priority: Keyboard > Mouse > Printer.

Interrupt Service Routine (ISR) execution is displayed and can optionally be logged with timestamps.

## Features

Priority-based interrupt handling (High → Medium → Low).

Mask/unmask devices dynamically during simulation.

Multi-threaded simulation for asynchronous behavior.

Clear, descriptive output messages for each interrupt.

Optional ISR log display after simulation.

## How to Compile and Run

1. Compile

Navigate to your project folder (or src directory) and run:

javac InterruptController.java

2. Run
java InterruptController

3. Expected Behavior

Keyboard and Mouse interrupts are enabled.

Printer interrupt is initially masked.

Program runs for a few seconds simulating device interrupts.

Highest-priority unmasked interrupt is always handled first.

ISR execution logs are displayed after simulation.
## Output Screenshot
