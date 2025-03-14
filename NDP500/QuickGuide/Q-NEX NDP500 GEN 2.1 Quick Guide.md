---
title: Q-NEX Desktop Digital Podium NDP500 User Manual
author: Q-NEX team
version: GEN 2.1
date: 2025-03-13
status: Progressing
tags: [NDP500, Quick Guide, Q-NEX]
---

<style>
table th {
    font-weight: bold;
    color: white; /* 字体颜色为白色 */
    background-color: #1f4e79; /* 背景颜色为蓝色 */
    padding: 6px 13px;
    text-align: center;
}
</style>




<img src="../../NMP/UserManual/img/Q-LOGO.png" style="zoom: 10%;" />



<div style="text-align:center; color:#2B5C9C; font-size:30px;font-weight:bold; ">Q-NEX Desktop Digital Podium</div>

 <div style="text-align:center;  color:#2B5C9C; font-size:30px; font-weight:bold;">NDP500 GEN2.1</div>



 <div style="text-align:center;  color:grey; font-size:30px; font-weight:bold;">—— User Manual ——</div>



<img src="../UserManual/img/NDP-500_GEN2.png" style="zoom: 35%;" />



# 1. Introduction 

The NDP500 is a versatile podium engineered for seamless integration into a variety of professional and educational environments. This quick guide provides an overview of the device, its connections, and key interfaces to facilitate initial setup and understanding.

## 1.1 Device Connection Diagram 

The following diagram illustrates the typical connections between the NDP500 and external devices. Refer to this diagram for a visual representation of the input and output ports and their corresponding connections.

<img src="../UserManual/img/NDP500GEN21_Device_Conn.png" style="zoom: 50%;" />





# 2. Understanding the Podium

This section provides a comprehensive overview of the NDP500, detailing its physical attributes, key features, and the functionality of its various interfaces.



## 2.1 Dimensions //等诗雨



## 2.2 Overview for NDP500

<img src="../UserManual/img/NDP500-GEN2-OV.png" alt=" " style="zoom: 67%;" />







## 2.3 Interface

This subsection details the NDP500's interfaces from front, left, right, and rear views, which are essential for connecting external devices.

### Front View 

<img src="../UserManual/img/NDP500-GEN2-FrontView.png" alt=" " style="zoom: 33%;" />

| No.  | Interface                | Description                                                  |
| ---- | ------------------------ | ------------------------------------------------------------ |
| 1    | Display Indicator        | Display status of the NDP500. The indicator has two states:<br />- Red (No signal source)<br />- Green (Signal source present) |
| 2    | Card Reader Area         | Allows users to authenticate using a swipe card for access control and logging in. |
| 3    | Hidden Antenna           | UHF for wireless microphones<br />2.4G Wi-Fi for CBX         |
| 4    | Mic Pairing Indicator    | Wireless microphone receiver indicator. Blinks during pairing, solid when paired. |
| 5    | IR Pairing Receiver      | Infrared pairing receiver for wireless microphones.          |
| 6    | Active Capacitive Stylus | Active capacitive stylus for NDP500. Magnetically attaches to the right-side slot for storage. |



### Left View

| No.  | Interface    | Description                                                  |
| ---- | ------------ | ------------------------------------------------------------ |
| 1    | OPS Slot * 1 | Supports the insertion and removal of Euro-standard OPS (Open Pluggable Specification) modules. |



### Right View

| No.  | Interface        | Description                                                  |
| ---- | ---------------- | ------------------------------------------------------------ |
| 1    | HDMI IN 1        | Connects to devices such as laptops. For Interactive Pen Display and IFP reverse touch control, USB HOST connection is also required. |
| 2    | USB-HOST         | USB-TYPE B 2.0. Paired with HDMI IN 1 to enable reverse touch control and other interactive functions. |
| 3    | HDMI IN 2        | Acts as the third input source for the NDP500.               |
| 4    | MIC IN-2 (3.5mm) | Line-in interface for connecting external microphones or audio devices. |



### Rear View

| No.  | Interface         | Description                                                  |
| ---- | ----------------- | ------------------------------------------------------------ |
| 1    | HDMI Ports        | IN x 4, OUT x 1, HD AUDIO x 1  <br />Handles seamless switching via the HDMI Seamless Matrix Switcher. See **[2.4 Seamless Matrix Wiring Instructions](#2.4 Seamless Matrix Wiring Instructions)** for details. |
| 2    | MIC BASE (LAN)    | Reserved interface.                                          |
| 3    | LAN (Ethernet) *2 | Standard Ethernet port for network connectivity (1000Mbps, non-PoE). |
| 4    | Touch USB 1       | Works with OUT 1 of the Seamless Matrix for bidirectional touch control on devices (e.g., IFP) and Interactive Pen Display. |
| 5    | Touch USB 2       | Works with OUT 2 of the Seamless Matrix for bidirectional touch control on devices (e.g., IFP) and Interactive Pen Display. |
| 6    | RS232             | For serial communication to other devices, typically for control or configuration purposes. Pinout sequence is R-G-T. |
| 7    | CONTROL           | Communication port for the Seamless Matrix. See **[2.4 Seamless Matrix Wiring Instructions](#2.4 Seamless Matrix Wiring Instructions)** for details. Pinout sequence is G-R-T. |
| 8    | IR                | IR-IN: NDP500 uses this port to learn infrared control codes from devices.<br />IR-OUT: For controlling compatible devices remotely (e.g., projector, screen). |
| 9    | MIC IN 1          | Input port for microphones or audio sources, supporting various microphone models. |
| 10   | MIC OUT           | Output port for routing audio from microphones to other systems or devices. |
| --   | ---               | ---                                                          |
| 1    | AUDIO OUT         | 3.5mm port for audio output to speakers or amplifiers.       |
| 2    | SPEAKER * 2       | Terminal block with 4-pin for connecting two pairs of passive speakers. Integrated dual-channel amplifier, with 40W and 4-8Ω load per channel. |
| 3    | UP-DOWN           | C13 outlet offering up, pause, and down functions for connected devices like projector screens and motorized curtains.  (110~220V AC, 300W) |
| 4    | DISPLAY           | C13 outlet used for power control of connected display devices like IFPs and projectors, supporting delayed power off. (110~220V AC, 1200W) |
| 5    | EXTERNAL          | C13 outlet, acts as a switch for controlling external devices such as lighting. Can be directly connected to NDP500-External or integrated with an SPDT switch. (110~220V AC, 1200W, This power does not count towards Digital's total power consumption) |
| 6    | POWER             | C14 inlet for powering the entire NDP500 unit, including the 23.8-inch display, 10.1-inch control screen, and internal OPS. (110~220V AC, 2000W) |
| 7    | POWER SWITCH      | Switch for powering the NDP500 unit on and off.              |



## 2.4 Seamless Matrix Wiring Instructions

Below is the wiring diagram for the connection between the NDP500 and the Seamless Matrix Switcher. 

<img src="../UserManual/img/NDP500-Switcher-Conn-v2.jpg" alt=" " style="zoom: 67%;" />

Follow the table for step-by-step connections:

| **NDP500**      | **Matrix Switcher** | **Description**                                              |
| --------------- | ------------------- | ------------------------------------------------------------ |
| IN1             | IN1                 | Connected to the Seamless Matrix Switcher (IN1) for seamless switching. The source comes from NDP500's side HDMI IN1, e.g., a laptop. |
| IN2             | IN2                 | Connected to the Seamless Matrix Switcher (IN2) for seamless switching. The source comes from NDP500's side HDMI IN2, e.g., a document camera. |
| IN3             | IN3                 | Connected to the Seamless Matrix Switcher (IN 3). The input source is from the built-in PC of NDP500. |
| IN 4            | IN4                 | Connected to the Seamless Matrix Switcher (IN 4), used for NDP500's broadcast functionality. |
| OUT3            | OUT 3               | Connected to the Seamless Matrix Switcher's OUT3 to enable seamless switching for NDP500's Interactive Pen Display |
| HD AUDIO        | OUT1-AUDIO          | Analog Audio Signal Output                                   |
| CONTROL (G R T) | RS232 OUT           | Dedicated RS232 port for communication between NDP500 and the Seamless Matrix Switcher. Pinout sequence is G-R-T. |

Follow the wiring overview above to complete the connections. 



