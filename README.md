# CAN-Relay-Controller-16CH

A high-performance CAN-to-Relay adapter board designed to control 16-channel relay modules over a robust CAN bus network. This board is ideal for industrial automation, home automation, and distributed control systems where long-distance communication and reliability are paramount.

## Features

* **Microcontroller:** STM32F103C6T6 (Cortex-M3) providing high-speed processing and native CAN support.
* **CAN Transceiver:** TJA1051T/3 high-speed CAN transceiver, offering excellent EMC performance and 3.3V logic compatibility.
* **Relay Support:** Optimized for standard 16-channel relay modules (active low/high configurable via wiring).
* **Connectivity:** * **RJ45 Connector:** Standardized cabling for long-distance CAN bus runs.
    * **Screw Terminals:** For secure power and relay signal distribution.
* **Power Input:** Wide range input support (typically 5V-12V depending on regulator choice).
* **Status LEDs:** Onboard indicators for Power, CAN Activity, and MCU Heartbeat.
* **Dimension:** L - 74mm and W - 32.7mm
## Hardware Specifications

| Component | Specification |
| :--- | :--- |
| MCU | STM32F103C6T6 |
| CAN Transceiver | TJA1051T/3 |
| Interface | RJ45 (CAN_H, CAN_L, GND) |
| Output | 16-Channel GPIO Header |
| Communication Protocol | CAN 2.0B |
| Operating Voltage | 5V / 3.3V Logic |

## Connector Pinout (RJ45)

To ensure compatibility with existing CAN-over-Ethernet standards:

1. CAN_L
2. CAN_H
3. NC
4. NC
5. VDD
6. VDD
7. GND
8. GND

## Programming

The board can be programmed using the **SWD (Serial Wire Debug)** interface. Compatible with:
* STM32CubeIDE
* Keil MDK
* PlatformIO


## Image
<img width="458" height="846" alt="Screenshot 2026-04-18 185036" src="https://github.com/user-attachments/assets/239acae9-594f-414c-9f7a-773f91ed73a2" />
<img width="866" height="550" alt="Screenshot 2026-04-18 185323" src="https://github.com/user-attachments/assets/2051b2c8-ca14-4414-ac35-fbcd72c8467e" />
<img width="831" height="461" alt="Screenshot 2026-04-18 185303" src="https://github.com/user-attachments/assets/9c590d5f-2c52-466a-96c4-a6ed179aaa6a" />
<img width="941" height="576" alt="Screenshot 2026-04-18 185251" src="https://github.com/user-attachments/assets/e2277abb-ee0a-422a-988f-40c8ea1d9ef7" />
<img width="873" height="631" alt="Screenshot 2026-04-18 185229" src="https://github.com/user-attachments/assets/005e3152-4d96-4f76-ba3b-3ceea2258dc2" />
<img width="405" height="850" alt="Screenshot 2026-04-18 185210" src="https://github.com/user-attachments/assets/e19dd02a-3d3e-4d13-b791-356c02f347ff" />
<img width="427" height="837" alt="Screenshot 2026-04-18 185201" src="https://github.com/user-attachments/assets/86da190c-27cf-4c01-b0ea-6fc2a20cf89e" />
<img width="419" height="844" alt="Screenshot 2026-04-18 185145" src="https://github.com/user-attachments/assets/3bffb41b-603d-4952-ad40-e94551307dc7" />
<img width="431" height="838" alt="Screenshot 2026-04-18 185133" src="https://github.com/user-attachments/assets/0419161a-d7bd-41ed-9c95-fe2fc28f8d6e" />
<img width="389" height="822" alt="Screenshot 2026-04-18 185100" src="https://github.com/user-attachments/assets/f7c01d8d-1ad6-4672-ac1a-1479faefa16f" />
<img width="1392" height="697" alt="Screenshot 2026-04-18 184855" src="https://github.com/user-attachments/assets/74cc2a6a-21cd-4633-8012-46cfe5e42a16" />

