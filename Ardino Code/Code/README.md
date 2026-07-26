# Li-Fi Communication System

This repository contains the firmware and documentation for a two-way Li-Fi (Light Fidelity) communication system built with Arduino.

## Project Overview
The hardware is symmetric, meaning the same Arduino code works on both Node A and Node B. Each node acts as both a transmitter (using a laser) and a receiver (using a light detector).

## Features
* **Two-way communication:** Send and receive text via light.
* **LCD Display:** Real-time printing of received messages on a 16x2 LCD.
* **Serial Monitor:** Type messages to transmit via the Arduino Serial Monitor.

## Hardware Requirements
* 2x Arduino Uno (or compatible boards)
* 2x Laser modules (Transmitter - Pin 12)
* 2x Light detectors / Photodiodes (Receiver - Pin 11)
* 2x 16x2 LCD Displays
