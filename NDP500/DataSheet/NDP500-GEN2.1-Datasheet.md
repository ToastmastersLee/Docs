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



<div style="text-align:center; color:#2B5C9C; font-size:30px;font-weight:bold; ">Q-NEX Networked Digital Podium</div>

 <div style="text-align:center;  color:#2B5C9C; font-size:30px; font-weight:bold;">NDP500 GEN2.1</div>



 <div style="text-align:center;  color:grey; font-size:30px; font-weight:bold;">—— Datasheet ——</div>



<img src="../UserManual/img/NDP500.png" style="zoom: 35%;" />



## 1. Product List



## 2. Desktop Digital Podium 





### NDP500 Interface //临时示意图

The Networked Media Processor (NMP) serves as the central control unit responsible for managing and coordinating various functionalities. 

<img src="./img/image-20250219105417532.png" alt="image-20250219105417532" style="zoom:50%;" />

| No.  | Interface             | Description                                                  |
| ---- | --------------------- | ------------------------------------------------------------ |
| 1    | **IN 1**              | Connected to HDMI Seamless Matrix Switcher (IN 1) for seamless input switch. The source is from NDP500's HDMI IN 1; for example, if a laptop is connected to HDMI IN 1, switching to IN 1 will display the laptop's content. |
| 2    | **IN 2**              | Connected to HDMI Seamless Matrix Switcher (IN 2) for seamless input switch. Similar to IN 1, used for different video sources like a document camera, laptop, etc. |
| 3    | **IN 3**              | Connected to HDMI Seamless Matrix Switcher (IN 3). The input source is from the built-in OPS of NDP500. |
| 4    | **IN 4**              | Connected to HDMI Seamless Matrix Switcher (IN 4), used for NDP500's broadcast functionality. |
| 5    | **OUT 3**             | Output connected to the Seamless Matrix Switcher's OUT 3, used to switch content for NDP500's Interactive Pen Display. |
| 6    | **MIC BASE** (LAN)    | Reserved interface.                                          |
| 7    | **LAN** (Ethernet) *2 | Standard Ethernet port for network connectivity (100Mbps, non-PoE). |
| 10   | **Touch USB 1**       | Works with OUT 1 of the Seamless Matrix for bidirectional touch control on devices (e.g., IFP) and Interactive Pen Display. |
| 11   | **Touch USB 2**       | Works with OUT 2 of the Seamless Matrix for bidirectional touch control on devices (e.g., IFP) and Interactive Pen Display. |
| 12   | **RS232**             | For serial communication to other devices, typically for control or configuration purposes. Pinout sequence is R-G-T. |
| 13   | **CONTROL**           | Dedicated RS232 port for communication between NDP500 and the Seamless Matrix Switcher. Pinout sequence is G-R-T. |
| 14   | **IR-IN**             | NDP500 uses this port to learn infrared control codes from devices. |
| 15   | **IR-OUT**            | IR port for controlling compatible devices remotely (e.g., projector, screen). |
| 16   | **MIC IN 1**          | Input port for microphones or audio sources, supporting various microphone models. |
| 17   | **MIC OUT**           | Output port for routing audio from microphones to other systems or devices. |



### HDMI  Seamless Matrix Switcher //4 *4 还是 3 * 3待定

<img src="../UserManual/img/Seamless_AV_Switcher_Wireframe.png" alt="Seamless_AV_Switcher_Wireframe" style="zoom: 33%;" />

| Sequence | Name                        | Description                                                  |
| -------- | --------------------------- | ------------------------------------------------------------ |
| 1        | HDM HD Matrix               | HDM High Definition Matrix                                   |
| 2        | Input Ports                 | 4x HDMI                                                      |
| 3        | Output Ports                | 4x HDMI                                                      |
| 4        | Device Height               | 1U                                                           |
| 5        | Supported Video Resolutions | 480i, 576i, 480p, 576p, 720p, 1080i, 1080p@24/30/50/60 Hz, 1080P3D@60Hz, 4K*2K@30Hz |
| 6        | Control Interfaces          | 1x RS232 IN, 1x RS232 OUT, 1x RJ45 LAN                       |
| 7        | Protocol Standards          | Supports 4K30Hz, EDID management and erasable, HDCP decoding (HDMI 1.4) |
| 8        | Color Spaces                | Supports RGB444, YUV444, YUV422 color spaces, supports x.v.Color extended color gamut standard |
| 9        | Electrostatic Protection    | Human body discharge mode: ± 6kV (air discharge) ±4kV (contact discharge) |
| 10       | Control Methods             | Standard buttons, RS232, remote switching; optional WEB, APP control |
| 11       | Power Supply                | AC110V-240V 50/60Hz                                          |
| 12       | Input Voltage               | Power supply 12V/2A                                          |
| 13       | Power Consumption           | 8W                                                           |
| 14       | Dimensions (mm)             | 430mm x 45mm x 150mm                                         |
| 15       | Operating Temperature       | 0°C~40°C / 32°F~104°F                                        |
| 16       | Storage Temperature         | -20°C~60°C / -4°F~140°F                                      |
| 17       | Weight                      | 2.45Kg                                                       |





###  Wireless Reciver Module

| No.  | Specification             | Details                                                      |
| ---- | ------------------------- | ------------------------------------------------------------ |
| 1    | **RF Transceiver**        | “Wi-Fi friendly” 2.4 GHz spread spectrum 2-way RF (2400 to 2483 MHz) |
| 2    | **RF Transmitting Power** | 13.5dBm                                                      |
| 3    | **Range**                 | < 30 m, support to connect up to 4 units of control box for extended RS232/IR/Relay control |



### Networked AV Decoder

Requires a media server to decode and play networked media content on classroom devices, supporting both scheduled and instant playback.

| No.  | Item                    | Specification                                                |
| ---- | ----------------------- | ------------------------------------------------------------ |
| 1    | Decoding Protocol       | RTMP                                                         |
| 2    | Resolution              | 1080p@30fps (recommended), up to 4K@30fps                    |
| 3    | Media Source            | Media server with Q-NEX streaming service system             |
| 4    | Playback Options        | Instant playback or scheduled playback on classroom media devices |
| 5    | Audio Formats Supported | MP3, WAV, FLAC, Ogg, Opus, and other mainstream audio formats |
| 6    | Video Formats Supported | MP4, MKV, RMVB, RM, MOV, AVI, FLV, WMV, and other mainstream video formats |

### Live AV Streaming

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

### Touch Panel

The Touch Panel allows users to access ndp500 functionalities such as power control, matrix switching, volume adjustment.

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





## 3. Microphone 

#### Wireless Mic Receiver (Built-in NDP500)

| No.  | Item                  | Specification                                        |
| ---- | --------------------- | ---------------------------------------------------- |
| 1    | Power Supply          | 12V                                                  |
| 2    | Frequency Bandwidth   | 300 kHz                                              |
| 3    | Frequency Response    | 30 Hz – 16 kHz                                       |
| 4    | Frequency Range       | Low: 642 MHz – 672 MHz <br />High: 674 MHz – 702 MHz |
| 5    | Maximum Channels      | 40 channels (20 per band)                            |
| 6    | Receiving Sensitivity | -96 dBm                                              |
| 7    | SNR                   | 94 dB                                                |
| 8    | Audio Output Level    | Max 0.9 Vrms                                         |
| 9    | Distortion (THD+N)    | < 0.1%                                               |
| 10   | Latency               | 4 ms (2.2 ms with frequency shift off)               |
| 11   | Operating Temperature | -20°C to 80°C                                        |



#### Wireless Microphone WX-D11

| No.  | Item                       | Specification                                    |
| ---- | -------------------------- | ------------------------------------------------ |
| 1    | Receiving Sensitivity      | -96 dBm                                          |
| 2    | Receiver Working Current   | 150 mA                                           |
| 3    | Frequency Range            | Low: 642 MHz – 672 MHz / High: 674 MHz – 702 MHz |
| 4    | Sensitivity                | -96 dBm                                          |
| 5    | Frequency Response         | 30 Hz – 16 kHz                                   |
| 6    | Microphone Type            | Unidirectional                                   |
| 7    | SNR                        | 94 dB                                            |
| 8    | Transmit Power             | 10 dBm                                           |
| 9    | Distortion (THD+N)         | < 0.1%                                           |
| 10   | Effective Distance         | ≤30 m                                            |
| 11   | Latency                    | 3 ms                                             |
| 12   | Operating Temperature      | -20°C to 80°C                                    |
| 13   | Power Supply               | 4.2V 800mAh 14500 Li-ion Battery                 |
| 14   | Microphone Working Current | 120 mA                                           |
| 15   | Battery Runtime            | Up to 6 hours                                    |



## 4. Media Server (Optional)

<img src="../UserManual/img/note.png" style="zoom: 87%;" />**Note**:

<font color=red> Media Server is a recommended option that works with NMP 211-G for AV Broadcasting and media files storage.</font>

The table below shows the minimum recommended specifications:

| No.  | Item         | Specification       |
| ---- | ------------ | ------------------- |
| 1    | Storage Type | ECC                 |
| 2    | RAM          | 16G                 |
| 3    | HDD Storage  | 4T * 4 SATA         |
| 4    | CPU          | 4-core 8-thread CPU |
| 5    | System       | Windows Server OS   |



## 5. Lite Media Server (Optional)

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

<img src="../UserManual/img/note.png" style="zoom:67%;" />**Note:** 

The Lite Media Server is intended for demonstration. For practical use, it is strongly recommended to choose a formal Media Server.



## 6. Control Box

The Control Box (CBX) wirelessly connects to a NDP500 using Wi-Fi 2.4G. Placed near devices like air conditioners, displays, lights, or smart curtains, the CBX acts as a bridge, enabling wired control of these devices without extensive cabling.

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

