# RP2040 Neural Network

This project demonstrates a simple neural network implemented on two Raspberry Pi Pico (RP2040) microcontrollers. 
The neural network is trained collaboratively using the two devices, with one device generating data, 
training the network, and the other demonstrating the output through physical components like LEDs.

## Project Structure
- `code/`: Contains the code for neural network training and Pico-Pico communication.
- `hardware/`: Contains hardware diagrams and wiring information.
- `docs/`: Contains detailed explanations, requirements, and project documentation.

## Getting Started
1. Set up two Raspberry Pi Pico boards as described in the hardware section.
2. Flash the firmware and the neural network code to the boards.
3. Observe as the devices collaboratively train and demonstrate a simple pattern recognition model.

## Features
- Neural network implementation with hidden layers
- Real-time communication between two RP2040 boards via UART
- LED control based on neural network output

