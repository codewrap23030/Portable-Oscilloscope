# Portable Oscilloscope

## Overview
This repository documents the development of a **Portable Oscilloscope** as part of the **Electronic System Design** coursework. The project aims to create a compact, battery-powered oscilloscope capable of visualizing input signals on an OLED display. The system is built around an **STM32 microcontroller**, integrating essential components such as an **ADC, waveform generator, battery management system, and rotary encoder-based controls**.

## System Architecture and  Components & Functionality
### 1. *Input Signal*
   - The oscilloscope captures analog signals through an input channel.

### 2. *Analog-to-Digital Converter (ADC)*
   - Converts the analog input signal into a digital format for processing by the STM32 microcontroller.

### 3. *STM32 Microcontroller*
   - Core processing unit responsible for signal acquisition, processing, and display.
   - Interfaces with multiple peripherals for enhanced functionality.

### 4. *Power Management* (in discussion stage currently)
   - Li-Ion / Li-Po Battery Pack: Provides portable power.

### 5. *User Interface & Control*
   - Rotary Encoder + Buttons: Allows users to navigate settings, adjust signal parameters, and control the oscilloscope functionality.

### 6. *Output & Display*
   - OLED Output Screen: Displays the waveform of the input signal.
   - Function Generator Output: AD9833 waveform generator provides an output signal for testing.

*Currently in the planning phase, focusing on efficient and compact design for field measurements.*
