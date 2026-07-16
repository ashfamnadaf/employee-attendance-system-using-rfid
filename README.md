# Employee Attendance System Using RFID

## Overview
The Employee Attendance System Using RFID is an embedded system project designed to automate employee attendance management using RFID technology. Each employee is provided with a unique RFID card/tag, which is scanned by the RFID reader. The LPC2129 ARM7 microcontroller processes the received RFID data and manages the attendance operation.

## Features
- RFID-based employee identification
- Contactless attendance marking
- Unique ID-based authentication
- Real-time attendance monitoring through UART
- Embedded C firmware implementation

## Hardware Components
- LPC2129 (ARM7) Microcontroller
- UART-based RFID Reader Module
- RFID Tags/Cards
- 16x2 LCD Display
- Power Supply

## Software Requirements
- Embedded C
- Keil µVision IDE
- Flash Magic

## Communication Protocol Used
- **UART (Universal Asynchronous Receiver Transmitter)** – Used for serial communication between the RFID module and LPC2129 ARM7 microcontroller to receive RFID card identification data.
- **I2C (Inter-Integrated Circuit)** – Used for interfacing the Real-Time Clock (RTC) module to maintain accurate date and time information for attendance records.

## Working Principle
1. The employee scans the RFID card/tag near the RFID reader.
2. The RFID module reads the unique identification number stored in the card.
3. The RFID reader sends the card ID data to the LPC2129 controller through UART communication.
4. The controller processes the received RFID data.
5. The attendance status is displayed on the LCD and monitored through UART.

## System Flow

| Step | Module | Function |
|------|--------|----------|
| 1 | RFID Card | Employee identification through unique RFID tag |
| 2 | UART RFID Module | Reads RFID card data and sends it to controller |
| 3 | LPC2129 ARM7 Microcontroller | Processes RFID data and controls system operation |
| 4 | RTC Module (I2C) | Provides real-time date and time information |
| 5 | LCD Display | Displays attendance status with date and time |
| 6 | UART Communication | Monitors system data through serial terminal |

## Applications
- Employee attendance systems
- Office access management
- College/school attendance monitoring
- Industrial workforce tracking

## My Contribution
- Developed embedded firmware using Embedded C.
- Interfaced UART-based RFID module with LPC2129.
- Implemented UART communication for RFID data reception.
- Processed RFID identification data and displayed attendance status.

## Tools Used
- Keil µVision IDE
- Embedded C
- LPC2129 ARM7 Development Board

