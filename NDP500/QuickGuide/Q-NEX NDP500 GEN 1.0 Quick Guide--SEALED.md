---
title: Q-NEX Networked Digital Podium NDP500 User Manual
author: Q-NEX team
version: GEN 1.0
date: 2025-03-05
status: SEALED
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



# Q-NEX NDP500 Quick Guide

<img src="../UserManual/img/NDP500.png" alt="771717585960_" style="zoom:67%;" /> 



# 1. Introduction 



## 1.1 Device Connection Diagram 



<img src="../UserManual/img/NDP500-DeviceConnection.png" alt="Six Views for NDP500" style="zoom: 67%;" />





# 2. Understanding the Podium



## 2.1 Dimensions

<img src="../UserManual/img/Six-Views.png" alt="Six Views for NDP500" style="zoom: 67%;" /> 



## 2.2 Overview for NDP500

<img src="../UserManual/img/NDP500-Overview.png" alt="Six Views for NDP500" style="zoom: 67%;" /> 





## 2.3 Interface 



### Front View 

<img src="../UserManual/img/image-20240705102715413.png" alt="image-20240705102715413" style="zoom: 33%;" /> 

| No.  | Interface        | Description                                                  |
| ---- | ---------------- | ------------------------------------------------------------ |
| 1    | Indicator Light  | Display the operational status of the NDP500. The indicator has two states:<br />- Red (No signal source)<br />- Green (Signal source present) |
| 2    | Card Reader Area | Allows users to authenticate using a swipe card for access control and logging in. |
| 3    | Hidden Antenna   | UHF for wireless microphones<br />2.4G Wi-Fi for CBX         |





### Left View

| No.  | Interface    | Description                                                  |
| ---- | ------------ | ------------------------------------------------------------ |
| 1    | OPS Slot * 1 | Supports the insertion and removal of Euro-standard OPS (Open Pluggable Specification) modules. |





### Right View

![image-20240702135726288](../UserManual/img/image-20240702135726288.png)  

| No.  | Interface        | Description                                                  |
| ---- | ---------------- | ------------------------------------------------------------ |
| 1    | HDMI IN 1        | Connects to devices such as laptop. For Interactive Pen Display and IFP reverse touch control, USB HOST connection is also required. |
| 2    | USB-HOST         | USB-TYPE B 2.0. Paired with HDMI IN 1 to enable reverse touch control and other interactive functions. |
| 3    | HDMI IN 2        | Acts as the third input source for the NDP500.               |
| 4    | AUDIO-IN (3.5mm) | Line-in interface for connecting external audio devices.     |



### Rear View

<img src="../UserManual/img/image-20240702135811050.png" alt="image-20240702135811050" style="zoom:77%;" /> 

<img src="../UserManual/img/image-20240702135821939.png" alt="image-20240702135821939" style="zoom:77%;" /> 

| No.  | Interface    | Description                                                  |
| ---- | ------------ | ------------------------------------------------------------ |
| 1    | LAN * 3      | 10M / 100M RJ45 ports for network connectivity. Does not support PoE. Can be used for connecting external devices like laptops. One port must be connected to a router to assign an IP address to the NDP500. |
| 2    | HDMI OUT B   | Serves as an output source for the NDP500. Can be connected to classroom IFPs or other display devices. For interactive touch functionality on IFPs, it must be paired with USB DEVICE B. |
| 3    | USB DEVICE B | USB Type A 2.0 port for touch control of external display devices. Works with HDMI OUT B as an output pair. |
| 4    | HDMI OUT A   | Serves as an output source for the NDP500. Can be connected to classroom IFPs or other large display devices. For interactive touch functionality on IFPs, it must be paired with USB DEVICE A<br /><br />Special feature: <br />1.The display on the NDP500 (Interactive Pen Display) is always synchronized with HDMI OUT A (firmware-level binding) <br />2. Can separate digital audio signal for IFPs with built-in speakers. |
| 5    | USB DEVICE A | USB Type A 2.0 port for touch control of external display devices. Works with HDMI OUT A as an output pair. |
| 6    | RS232        | 3-pin (R, G, T) for controlling devices like PTZ cameras, IFPs, and recording cameras. |
| 7    | RS485        | 3-pin (G, B, A) for controlling devices with RS485 interface, such as PTZ cameras. |
| 8    | IR IN        | Infrared learning port for capturing IR control codes from devices like air conditioners and TVs. |
| 9    | IR OUT       | Infrared control port for sending IR signals to control devices like air conditioners and TVs. |
| 10   | MIC IN       | 6.35mm port for connecting a wired microphone for clear audio reinforcement during instruction or conferences. |
| 11   | MIC OUT      | 3.5mm port for mixing audio from both the microphone input and wireless microphones for combined output. |
| 12   | AUDIO OUT    | 3.5mm port for audio output to speakers or amplifiers.       |
| 13   | SPEAKER * 2  | Terminal block with 4-pin for connecting two pairs of passive speakers. Integrated dual-channel amplifier, with 40W and 4-8Ω load per channel. |
| 14   | UP-DOWN      | C13 outlet offering up, pause, and down functions for connected devices like projector screens and motorized curtains.  (110~220V AC, 300W) |
| 15   | DISPLAY      | C13 outlet used for power control of connected display devices like IFPs and projectors, supporting delayed power off. (110~220V AC, 1200W) |
| 16   | EXTERNAL     | C13 outlet, acts as a switch for controlling external devices such as lighting. Can be directly connected to NDP500-External or integrated with an SPDT switch. (110~220V AC, 1200W, This power does not count towards Digital's total power consumption) |
| 17   | POWER        | C14 inlet for powering the entire NDP500 unit, including the 23.8-inch display, 10.1-inch control screen, and internal OPS. (110~220V AC, 2000W) |
| 20   | POWER SWITCH | Switch for powering the NDP500 unit on and off.              |

