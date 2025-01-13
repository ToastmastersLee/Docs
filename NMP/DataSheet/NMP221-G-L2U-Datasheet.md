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

 <div style="text-align:center;  color:#2B5C9C; font-size:30px; font-weight:bold;">NMP211-G-L2U</div>



 <div style="text-align:center;  color:grey; font-size:30px; font-weight:bold;">—— Datasheet ——</div>



<img src="./img/NMP211-R-L2T-Main.png" style="zoom: 10%;" />



# NMP211

The Networked Media Processor (NMP) serves as the central control unit responsible for managing and coordinating various functionalities. 

<img src="../../NMP/UserManual/img/NMP211-Interface-Back.png"  style="zoom: 19%;" />

| No.  | Interface                                     | Description                                                  |
| ---- | --------------------------------------------- | ------------------------------------------------------------ |
| 1    | RJ45 * 4                                      | Ethernet ports (100Mbps, non-PoE) for NMP network connectivity; also enables NMP to function as a switch. |
| 2    | HDMI Matrix 3 * 3                             | Consists of 3 HDMI inputs and 3 HDMI outputs, forming the video matrix for NMP. |
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
| 17   | Electric Lock Interface (LOCK) * 1            | Allows integration with electric lock systems, enabling scenarios such as automatic door locking after a specified period post door opening. <br /><img src="../UserManual/img/note.png"  style="zoom:67%;" />Note: <br />Only supports electric locks, not electronic lock systems. |
| 18   | Power Fuse * 1                                | Power fuse for protection against electrical faults.         |
| 19   | External Port (WAGO) * 1                      | External port interface for lighting control and other devices. there are two methods to control lighting and other devices:<br />1. **Direct Connection to NMP-External**: With this mode, users can directly manage lighting control using NMP.<br />2. **Integration with SPDT Switch**: By replacing the existing switch panel with a Single Pole Double Throw (SPDT) switch and connecting it to NMP, both NMP and the switch panel can control the lighting. |
| 20   | NMP Power Supply (WAGO) * 1                   | Power supply for NMP, supporting wide voltage range (110-240 V AC). |

**Networked AV Decoder**

Requires a media server to decode and play networked media content on classroom devices, supporting both scheduled and instant playback.

| No.  | Item                    | Specification                                                |
| ---- | ----------------------- | ------------------------------------------------------------ |
| 1    | Decoding Protocol       | RTMP                                                         |
| 2    | Resolution              | 1080p@30fps (recommended), up to 4K@30fps                    |
| 3    | Media Source            | Media server with Q-NEX streaming service system             |
| 4    | Playback Options        | Instant playback or scheduled playback on classroom media devices |
| 5    | Audio Formats Supported | MP3, WAV, FLAC, Ogg, Opus, and other mainstream audio formats |
| 6    | Video Formats Supported | MP4, MKV, RMVB, RM, MOV, AVI, FLV, WMV, and other mainstream video formats |

**Live AV Streaming**

Supports live video streaming from various sources, including IP cameras, smartphones, PCs (using third-party software like OBS), and audio/video encoders. The RTMP protocol is used to transmit streams to the media server, which the NMP decodes for playback on display devices in classrooms and other locations.

| No.  | Item               | Specification                                                |
| ---- | ------------------ | ------------------------------------------------------------ |
| 1    | Streaming Protocol | RTMP                                                         |
| 2    | Resolution         | 1080p@30fps (recommended), up to 4K@30fps                    |
| 3    | Source             | IP cameras, smartphones with broadcasting software (e.g., OBS), PCs with OBS, audio/video encoders |

**General Specifications**

| No.  | Item              | Specification                                                |
| ---- | ----------------- | ------------------------------------------------------------ |
| 1    | Size \(mm\)       | 440(L)\*292(W)\*50(H)                                        |
| 2    | Weight            | 3.9 Kg                                                       |
| 3    | Design            | Standard 1U rack-mount, suitable for installation in various types of cabinets |
| 4    | Motherboard       | Industrial-grade, high-speed 32-bit CPU with embedded operating system |
| 5    | Push Notification | Displays messages, alerts, and announcements from IT admin or teachers on classroom displays instantly or on schedule |

# Touch Panel

The Touch Panel allows users to access NMP functionalities such as power control, matrix switching, volume adjustment, and Divisible Room operations. Even in LAN-connected environments without Internet access, users still can perform local operations like matrix switching and volume adjustments.

The Touch Panel serves as the primary controlling interface, providing intuitive touch-based controls for the operation of the NMP. 

<img src="./img/NMP-CPL20.png" alt="NMP-CPL20.png" style="zoom: 33%;" />

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

| No.  | Item                       | Specification                  |
| ---- | -------------------------- | ------------------------------ |
| 1    | Receiving Sensitivity      | >=85dBm                        |
| 2    | Receiver Working Current   | 5V/180mA                       |
| 3    | Frequency Range            | 640MHz ~ 690MHz                |
| 4    | Sensitivity                | 51dB ± 3dB (0dB = 1V/Pa 1 KHz) |
| 5    | Frequency Response         | 50Hz ~ 15KHz                   |
| 6    | Microphone Type            | Dynamic cardioid microphone    |
| 7    | SNR                        | >=65dB                         |
| 8    | Transmit Power             | >20dBm                         |
| 9    | Distortion                 | <0.5%                          |
| 10   | Effective Distance         | <40m                           |
| 11   | Latency                    | <5ms                           |
| 12   | Operating Temperature      | -25°C ~ 60°C                   |
| 13   | Power Supply               | 2 * AA batteries               |
| 14   | Microphone Working Current | 100mA @ 3V                     |
| 15   | Battery Lifetime           | 12 Hours                       |



## Lapel Microphone

| No.  | Item                       | Specification                  |
| ---- | -------------------------- | ------------------------------ |
| 1    | Receiving Sensitivity      | >=85dBm                        |
| 2    | Receiver Working Current   | 5V/180mA                       |
| 3    | Frequency Range            | 640MHz ~ 690MHz                |
| 4    | Sensitivity                | 51dB ± 3dB (0dB = 1V/Pa 1 KHz) |
| 5    | Frequency Response         | 50Hz ~ 15KHz                   |
| 6    | Microphone Type            | Condenser microphone           |
| 7    | SNR                        | >=105dB                        |
| 8    | Transmit Power             | 16 ~ 25dBm                     |
| 9    | Distortion                 | <0.5%                          |
| 10   | Effective Distance         | <40m                           |
| 11   | Latency                    | <5ms                           |
| 12   | Operating Temperature      | -25°C ~ 60°C                   |
| 13   | Power Supply               | 2 * AA batteries               |
| 14   | Microphone Working Current | 200mA @ 3V                     |
| 15   | Battery Lifetime           | 5 Hours                        |



# Media Server (Optional)

<img src="/Users/leewang/Documents/Githubs/IQ/Docs/NMP/DataSheet/img/note-6757382.png"  />**Note**:

<font color=red> Media Server is a recommended option that works with NMP 211-G for AV Broadcasting and media files storage.</font>

The table below shows the minimum recommended specifications:

| No.  | Item         | Specification       |
| ---- | ------------ | ------------------- |
| 1    | Storage Type | ECC                 |
| 2    | RAM          | 16G                 |
| 3    | HDD Storage  | 4T * 4 SATA         |
| 4    | CPU          | 4-core 8-thread CPU |
| 5    | System       | Windows Server OS   |



# Lite Media Server (Optional)

| No.  | Item               | Specification                                                |
| ---- | ------------------ | ------------------------------------------------------------ |
| 1    | Processor          | Intel® Core™ i5 4200M 2.5GHz                                 |
| 2    | RAM                | 4GB DDR3                                                     |
| 3    | Storage            | 256G SSD                                                     |
| 4    | Network Card       | 1 × RJ45 LAN 10/100/1000M                                    |
| 5    | WiFi               | IEEE 802.11 a/g/n/ac                                         |
| 6    | Power Supply Input | 19V                                                          |
| 7    | Dimension          | 180mm (L) x 195mm (W) x 42mm (H)                             |
| 8    | Temperature        | Operating temperature: 0°C ~ 50°C <br> Storage temperature: -20°C ~ 70°C |
| 9    | Humidity           | 5% ~ 90% No condensation                                     |

<img src="/Users/leewang/Documents/Githubs/IQ/Docs/NMP/DataSheet/img/note-6757382.png"  />**Note:** 

The Lite Media Server is intended for demonstration. For practical use, it is strongly recommended to choose a formal Media Server.



# Control Box

The Control Box (CBX) wirelessly connects to a NMP using Wi-Fi 2.4G. Placed near devices like air conditioners, displays, lights, or smart curtains, the CBX acts as a bridge, enabling wired control of these devices without extensive cabling.

<img src="../../NMP/UserManual/img/CBX/CBX200-Interface.png"  style="zoom: 33%;" />

| No.  | Interface         | Description                                                  |
| ---- | ----------------- | ------------------------------------------------------------ |
| 1    | Power Supply (DC) | 12V,1A                                                       |
| 2    | Reset Button      | Resets the CBX to its default factory settings               |
| 3    | Link Indicator    | Displays the connection status between the CBX and the NMP   |
| 4    | DIP Switch        | Used for configuration settings and adjustments of the CBX   |
| 5    | RS232             | Allows wired communication and control with RS232-compatible devices. |
| 6    | IR                | Enables IR communication for controlling devices with infrared signals. |
| 7    | Relay             | Provides control over devices using relay switches for on/off functions. |

