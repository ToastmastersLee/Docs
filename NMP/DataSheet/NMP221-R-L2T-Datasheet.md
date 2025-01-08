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



<div style="text-align:center; color:#2B5C9C; font-size:30px;font-weight:bold; ">Q-NEX Networked Media Processor</div>

 <div style="text-align:center;  color:#2B5C9C; font-size:30px; font-weight:bold;">NMP211-R</div>



 <div style="text-align:center;  color:grey; font-size:30px; font-weight:bold;">—— Datasheet ——</div>





# NMP211

The Networked Media Processor (NMP) serves as the central control unit responsible for managing and coordinating various functionalities of the digital podium.  

<img src="../../NMP/UserManual/img/NMP211-Interface-Back.png" style="zoom: 15%;" />

 

| No.  | Interface                                     | Description                                                  |
| ---- | --------------------------------------------- | ------------------------------------------------------------ |
| 1    | RJ45 * 4                                      | Ethernet ports (100Mbps, non-PoE) for NMP network connectivity; also enables NMP to function as a switch. |
| 2    | HDMI Matrix 3 * 2                             | Consists of 3 HDMI INs and 3 HDMI OUTs, the HDMI OUT A and HDMI OUT C output same content, forming the 3 x 2 video matrix for NMP. |
| 3    | 2.4G Wi-Fi Antenna Interface * 2              | Built-in 2.4G Wi-Fi RP Transceiver within NMP, allowing wireless device integration and control expansion with Q-NEX's CBX component. |
| 4    | UHF Wireless Microphone Antenna Interface * 1 | Built-in receiver for UHF wireless microphones, supporting one-to-two wireless microphone setups for teaching/meeting scenarios. |
| 5    | Display (WAGO) * 1                            | Provides power output for connected devices, such as projectors, TVs, Interactive Flat Panels (IFP), and smart podiums. |
| 6    | UP-DOWN (WAGO) * 1                            | Offering up, pause, and down functions for connected devices like projector screens and motorized curtains. |
| 7    | RS232 * 1                                     | Allows connection to devices equipped with standard RS232 ports, such as Pan-Tilt-Zoom (PTZ) cameras and Interactive Flat Panels (IFP), etc. |
| 8    | Panel * 1                                     | Interface for connection to mechanical control panels, allowing direct control of basic devices and AV matrix switching without the need for network connectivity. |
| 9    | IR * 2                                        | IR learner port * 1: Used for learning IR remote control codes.<br />IR emitter port * 1: For infrared remote-control functionality. |
| 10   | USB * 2                                       | Reserved for card reader                                     |
| 11   | Touch USB * 3                                 | TOUCH USB IN * 1 :  Receives touch signals from the Interactive Pen Display. <br />TOUCH USB OUT * 2 : Sends touch signals to OPS or Laptop for touch-following functionality. |
| 12   | 6.35mm Wired Microphone In * 1                | Interface for connecting a 6.35mm wired microphone.          |
| 13   | 3.5mm MIC Mixed Out * 1                       | Mixes audio from both the microphone input and the wireless microphones (handheld and lapel) for combined output. |
| 14   | Audio-IN * 2                                  | Two 3.5mm line-in interfaces for connecting external audio devices such as laptops, smartphones etc. |
| 15   | Audio Out                                     | Audio output interface for connecting to speakers or amplifiers. |
| 16   | External Speaker Output                       | The NMP includes an integrated power amplifier, capable of delivering 2*(40w+40w) output, designed to connect with passive speakers.  (Fixed impedance speakers only). |
| 17   | Built-in OPS Control (LOCK Interface) * 1     | Be used to monitor and control the OPS within the Digital Podium, synchronized with NDP power management. |
| 18   | Power Fuse * 1                                | Power fuse for protection against electrical faults.         |
| 19   | External Port (WAGO) * 1                      | External port interface for lighting control and other devices. there are two methods to control lighting and other devices:<br />1. **Direct Connection to NMP-External**: With this mode, users can directly manage lighting control using NMP.<br />2. **Integration with SPDT Switch**: By replacing the existing switch panel with a Single Pole Double Throw (SPDT) switch and connecting it to NMP, both NMP and the switch panel can control the lighting. |
| 20   | NMP Power Supply (WAGO) * 1                   | Power supply for NMP, supporting wide voltage range (110-240 V AC). |



**General Specifications**

| No.  | Item              | Specification                                                |
| ---- | ----------------- | ------------------------------------------------------------ |
| 1    | Size \(mm\)       | 440(L)\*292(W)\*50(H)                                        |
| 2    | Weight            | 3.9 Kg                                                       |
| 3    | Design            | Standard 1U rack-mount, suitable for installation in various types of cabinets |
| 4    | Motherboard       | Industrial-grade, high-speed 32-bit CPU with embedded operating system |
| 5    | Push Notification | Displays messages, alerts, and announcements from IT admin or teachers on classroom displays instantly or on schedule |



# Touch Panel

| No.  | Item             | Specification                                                |
| ---- | ---------------- | ------------------------------------------------------------ |
| 1    | Model            | CPL20                                                        |
| 2    | CPU              | Quad-core, Main frequency 1.6GHz                             |
| 3    | GPU              | Quad-core                                                    |
| 4    | RAM              | 2G                                                           |
| 5    | ROM              | 16G                                                          |
| 6    | O.S.             | Android 10                                                   |
| 7    | Screen           | 10-inch 1280*800 IPS                                         |
| 8    | Dimension (mm)   | 244(L)\*171.5(H)\*28(W)                                      |
| 9    | Touch            | Capacitive screen with tempered glass, 10-point touch <br>Optical bonding |
| 10   | I/O Port         | RJ45*1 (PoE supported) <br>USB2.0 *3 <br>Type-C OTG *1 <br>Audio (3.5mm) *1 <br>DC (12V) *1 |
| 11   | Physical Button  | Power *1                                                     |
| 12   | IC               | Supported                                                    |
| 13   | Working          | -20°C to 70°C                                                |
| 14   | Working Humidity | <85%                                                         |
| 15   | Installation     | Desktop stand                                                |





# Microphone

## Handheld Microphone

<img src="/Users/leewang/Documents/Githubs/IQ/Docs/NMP/DataSheet/img/image-20250108111102060.png" alt="image-20250108111102060" style="zoom:67%;" />

| **Specification**                      | Specification                |
| -------------------------------------- | ---------------------------- |
| Matching models                        | Q-NEX NMP                    |
| Frequency Response                     | 40-16K (Hz)                  |
| Directivity                            | Capacitive Uni-Directional   |
| Sensitivity                            | -44 (dB)                     |
| Frequency Range                        | 2400-2482 MHz                |
| Modulation Mode                        | GFSK                         |
| Power supply                           | 3.7V / 800mA lithium battery |
| Battery life                           | >8-12H                       |
| RF power                               | 0 dBm                        |
| Maximum wireless transmission distance | 10-15m                       |
| Size                                   | 160\*15mm                    |



## Lapel Microphone

<img src="/Users/leewang/Documents/Githubs/IQ/Docs/NMP/DataSheet/img/image-20250108111130629.png" alt="image-20250108111130629" style="zoom:67%;" />

| **Specification**                      | **V220-B**                   |
| -------------------------------------- | ---------------------------- |
| Matching models                        | Q-NEX NMP                    |
| Frequency Response                     | 40-16K (Hz)                  |
| Directivity                            | Capacitive Uni-Directional   |
| Sensitivity                            | -46 (dB)                     |
| Frequency Range                        | 2400-2482 MHz                |
| Modulation Mode                        | GFSK                         |
| Power supply                           | 3.7V / 800mA lithium battery |
| Battery life                           | >6-8 H                       |
| RF power                               | 0 dBm                        |
| Maximum wireless transmission distance | 15-20m                       |
| Size                                   | 57\*24\*27mm                 |

