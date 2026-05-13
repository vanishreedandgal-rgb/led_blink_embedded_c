# led_blink_embedded_c
#  LED Blink using Embedded C

##  Project Overview

This project demonstrates a basic **LED blinking application** developed using **Embedded C** on an AVR microcontroller platform.
The program controls a GPIO pin to periodically toggle an LED, helping beginners understand **microcontroller I/O configuration**, **register-level programming**, and **hardware and software interaction**.

---

## Hardware Requirements

* AVR Microcontroller (ATmega328P / ATmega16 / ATmega32)
* LED
* 220Ω Current Limiting Resistor
* Breadboard
* Connecting Wires

---

##  Software Requirements

* Microchip Studio / Atmel Studio
* AVR-GCC Compiler
* Proteus Simulator (Optional)

---

##   Circuit Connection

* LED **Anode (+)** → **PORTB Pin 0 (PB0)**
* LED **Cathode (−)** → **220Ω Resistor → GND**

---

##  Working Principle

1. The PB0 pin is configured as an **Output** using the DDRB register.
2. The microcontroller sets the output pin HIGH to turn ON the LED.
3. A software delay of 1 second is generated.
4. The output pin is cleared (LOW) to turn OFF the LED.
5. The process repeats continuously inside an infinite loop.

---

## Project Structure

```
embedded-c-led-blink/
│
├── main.c        # Embedded C source code
├── README.md     # Project documentation

```

---

##

---

##  Expected Output

The LED connected to **PB0** blinks with a time interval of **1 second ON** and **1 second OFF** continuously.

---

##   Learning Outcomes

* Understanding microcontroller GPIO architecture
* Register-level hardware programming
* Basics of embedded firmware development
* Practical interfacing between hardware and software

---

##

---

