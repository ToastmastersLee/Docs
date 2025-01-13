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

 <div style="text-align:center;  color:#2B5C9C; font-size:30px; font-weight:bold;">NMP211-G-L2</div>



 <div style="text-align:center;  color:grey; font-size:30px; font-weight:bold;">—— Datasheet ——</div>







# NMP211

The Networked Media Processor (NMP) serves as the central control unit responsible for managing and coordinating various functionalities. 

<img src="/Users/leewang/Documents/Githubs/IQ/Docs/NMP/DataSheet/img/NMP211-R-L2.png" alt="image-20250113151610686" style="zoom: 25%;" />

| No.  | Interface                          | Description                                                  |
| ---- | ---------------------------------- | ------------------------------------------------------------ |
| 1    | RJ45 * 4                           | Ethernet ports (100Mbps, non-PoE) for NMP network connectivity; also enables NMP to function as a switch. |
| 2    | HDMI Matrix 3 * 3                  | Consists of 3 HDMI inputs and 3 HDMI outputs, forming the video matrix for NMP. |
| 3    | Display (WAGO) * 1                 | Provides power output for connected devices, such as projectors, TVs, Interactive Flat Panels (IFP), and smart podiums. |
| 4    | UP-DOWN (WAGO) * 1                 | Offering up, pause, and down functions for connected devices like projector screens and motorized curtains. |
| 5    | RS232 * 1                          | Allows connection to devices equipped with standard RS232 ports, such as Pan-Tilt-Zoom (PTZ) cameras and Interactive Flat Panels (IFP), etc. |
| 6    | Panel * 1                          | Interface for connection to mechanical control panels, allowing direct control of basic devices and AV matrix switching without the need for network connectivity. |
| 7    | IR * 2                             | IR learner port * 1: Used for learning IR remote control codes.<br />IR emitter port * 1: For infrared remote-control functionality. |
| 8    | USB * 2                            | Reserved for card reader                                     |
| 9    | Touch USB * 3                      | TOUCH USB IN * 1 :  Receives touch signals from the Interactive Pen Display. <br />TOUCH USB OUT * 2 : Sends touch signals to OPS or Laptop for touch-following functionality. |
| 10   | 6.35mm Wired Microphone In * 1     | Interface for connecting a 6.35mm wired microphone.          |
| 11   | 3.5mm MIC Mixed Out * 1            | Mixes audio from both the microphone input and the wireless microphones (handheld and lapel) for combined output. |
| 12   | Audio-IN * 2                       | Two 3.5mm line-in interfaces for connecting external audio devices such as laptops, smartphones etc. |
| 13   | Audio Out                          | Audio output interface for connecting to speakers or amplifiers. |
| 14   | External Speaker Output            | The NMP includes an integrated power amplifier, capable of delivering 2*(40w+40w) output, designed to connect with passive speakers.  (Fixed impedance speakers only). |
| 15   | Electric Lock Interface (LOCK) * 1 | Allows integration with electric lock systems, enabling scenarios such as automatic door locking after a specified period post door opening. <br /><img src="../UserManual/img/note.png"  style="zoom:67%;" />Note: <br />Only supports electric locks, not electronic lock systems. |
| 16   | Power Fuse * 1                     | Power fuse for protection against electrical faults.         |
| 17   | External Port (WAGO) * 1           | External port interface for lighting control and other devices. there are two methods to control lighting and other devices:<br />1. **Direct Connection to NMP-External**: With this mode, users can directly manage lighting control using NMP.<br />2. **Integration with SPDT Switch**: By replacing the existing switch panel with a Single Pole Double Throw (SPDT) switch and connecting it to NMP, both NMP and the switch panel can control the lighting. |
| 18   | NMP Power Supply (WAGO) * 1        | Power supply for NMP, supporting wide voltage range (110-240 V AC). |

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

<img src="./img/NMP-CPL20.png" alt="NMP-CPL20" style="zoom: 33%;" />

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
