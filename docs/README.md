# GoPro Labs

## Firmware

Labs offers experimental firmware program that uses QR codes to control your camera and extend your camera’s functionality beyond stocks features. 
It is especially useful in situations where settings can’t be communicated via voice, where WiFi is not available, where app pairing is not established, 
or in advanced setups, such as multiple cameras time synchronization or delayed camera triggers. You will not lose any pre-existing modes or features on 
your GoPro—this update simply adds more features.  Safe to install, safe to use, only the extended feature are experimental and they are all off by default. 

Download the GoPro Labs firmware for current shipping cameras:
- [HERO12 Black](https://bit.ly/LABS_H12_1_10_70) - v1.10.70, September 2023
- [HERO11 Black](https://bit.ly/LABS_H11_2_12_70) - v2.12.70, August 2023
- [HERO11 Black Mini](https://bit.ly/LABS_M11_2_30_70) - v2.30.70, May 2023
- [HERO10 Black](https://bit.ly/LABS_H10_1_50_70) - v1.50.70, January 2023
- [GoPro MAX](https://bit.ly/LABS_MAX_2_00_75) - v2.00.75, April 2023

Download and install for older cameras:
- [HERO9 Black](https://bit.ly/LABS_H9_1_72_70) - v1.72.70, June 2022
- [HERO8 Black](https://bit.ly/LABS_H8_2_51_75) - v2.51.75, July 2022
- [HERO7 Black](https://bit.ly/LABS_H7_1_90_71) - v1.90.71, January 2021
- [HERO5 Session](https://bit.ly/LABS_H5S_2_51_72) - v2.51.72, May 2021

**By downloading any of the public updates provided to you on, from, or through this page or the GoPro website you signify your agreement to [these terms of participation (the "Terms”)](https://gopro.com/content/dam/help/gopro-labs/Beta_Participation_Terms_and_Conditions.pdf).**

Follow the [manual firmware update instructions](install).

See updates and changes in the [Release Notes](https://gopro.github.io/labs/control/notes/)

Need help, or an have Labs questions, we have a dedicated [forum for Labs users](https://github.com/gopro/labs/discussions)

Learn more information about the program on [GoPro.com](https://gopro.com/info/gopro-labs).

### Labs Camera Control
 
GoPro QR code generator for basic [camera settings](https://gopro.github.io/labs/control/custom) changes

### Advanced Commands Overviews

- [Camera Macros](https://gopro.github.io/labs/control) e.g. motion or sound level triggers, long form time-lapses, etc.
- [Camera Extensions](https://gopro.github.io/labs/control/extensions) e.g. bit-rate enhancements or exposure tweaks

### New: Visual Scripting Tool for Labs cameras since HERO11
- [Visual Script Tool](https://gopro.github.io/labs/build/)

### Primer on Labs actions, scripting and command sets

- [Action Commands](https://gopro.github.io/labs/control/actions)
- [Setting Commands](https://gopro.github.io/labs/control/settings)

### Overview of Labs functionality and device compatibility: 

| Feature                                                                            | HERO11/Mini | HERO10/Bones | HERO9 | HERO8 | HERO7 | MAX |
|------------------------------------------------------------------------------------|-------------|--------------|-------|-------|-------|-----|
| [24.0Hz capture vs 23.976](https://gopro.github.io/labs/control/extensions)                 | Yes     | Yes     |       |       |       |     |
| [Adobe-compatible proxies](https://gopro.github.io/labs/control/proxies)                    | Yes     | Yes/No  |       |       |       |     |
| [Altered File Naming](https://gopro.github.io/labs/control/basename)                        | Yes     | Yes     | Yes   | Yes   | Yes   | Yes |
| [Archive Mode](https://gopro.github.io/labs/control/archive) (locked settings)              | Yes     | Yes     | Yes   | Yes   | Yes   | Yes |
| [Audio Channels Gain/Solo/Mute](https://gopro.github.io/labs/control/extensions)            | Yes     | Yes     | Yes   |       |       |     |
| [Audio Disable](https://gopro.github.io/labs/control/extensions)                            | Yes     | Yes     | Yes   |       |       |     |
| [Bitrate Controls](https://gopro.github.io/labs/control/extensions)                         | Yes     | Yes     |       |       |       |     |
| [Boot Command](https://gopro.github.io/labs/control/extensions)                             | Yes     | Yes     |       | Yes   |       |     |
| [DaVinci-compatible proxies](https://gopro.github.io/labs/control/proxies)                  | Yes     |         |       |       |       |     |
| [Exposure Display](https://gopro.github.io/labs/control/extensions) current ISO and shutter | Yes     |         |       |       |       |     |
| [Exposure Damping](https://gopro.github.io/labs/control/extensions) control                 | Yes     | Yes     |       |       |       |     |
| [Exposure Curve](https://gopro.github.io/labs/control/extensions) custom log encoding       | Yes     |         |       |       |       |     |
| [Exposure Min/Max Times](https://gopro.github.io/labs/control/extensions)                   | Yes     |         |       |       |       |     |
| [Extra Long time-lapse](https://gopro.github.io/labs/control/longtimelapse)                 | Yes/No  | Yes     | Yes   | Yes   | Yes   | Yes |
| [GPS time sync](https://gopro.github.io/labs/control/gpssync)                               | Yes/No  | Yes/No  | Yes   |       |       |     |
| [Guidelines Display](https://gopro.github.io/labs/control/extensions) on rear LCD           | Yes/No  |         |       |       |       |     |
| [HDMI display settings](https://gopro.github.io/labs/control/extensions)                    | Yes/No  | Yes     | Yes   |       |       |     |
| [Hindsight Timeout Extension](https://gopro.github.io/labs/control/extensions)              | Yes     | Yes     |       |       |       |     |
| [Histogram](https://gopro.github.io/labs/control/extensions) (on display)                   | Yes     | Yes     | Yes   | Yes   |       |     |
| [Histogram Position/Size](https://gopro.github.io/labs/control/extensions) (either screen)  | Yes/No  |         |       |       |       |     |
| [Large Chapter](https://gopro.github.io/labs/control/chapters) Support (12GB)               | Standard| Yes     | Yes   | Yes   |       | Yes |
| [Live Stream Initiation](https://gopro.github.io/labs/control/rtmp)                         | Yes     | Yes     | Yes   | Yes   |       |     |
| [LRV Disable](https://gopro.github.io/labs/control/extensions)                              | Yes     | limited |       |       |       |     |
| [LTC Time support](https://gopro.github.io/labs/control/ltc) (via MediaMod)                 | Yes/No  | Yes/No  | Yes   |       |       |     |
| [Max Shutter Angle](https://gopro.github.io/labs/control/maxshut) exposure control          | Yes     | Yes     | Yes   | Yes   | Yes   | Yes |
| [Metadata Injections](https://gopro.github.io/labs/control/extensions)                      | Yes     | Yes     | Yes   | Yes   | Yes   | Yes |
| [Noise Reduction](https://gopro.github.io/labs/control/extensions) control                  | Yes     |         |       |       |       |     |
| [Overlay - Burn-ins](https://gopro.github.io/labs/control/overlays) e.g. Time/Date          | limited | limited | Yes   | Yes   |       |     |
| [Overlay - Color Bar](https://gopro.github.io/labs/control/extensions)                      | limited | limited | Yes   | Yes   |       |     |
| [Overlays - Logo Burn-In](https://gopro.github.io/labs/control/logo)                        | limited | limited | Yes   |       |       |     |
| [Overlays - Luma Sweep](https://gopro.github.io/labs/control/extensions)                    | limited | limited | Yes   | Yes   |       |     |
| [Owner Information](https://gopro.github.io/labs/control/owner)                             | Yes     | Yes     | Yes   | Yes   | Yes   | Yes |
| [QR decoding while recording](https://gopro.github.io/labs/control/extensions)              | Yes     | Yes     | Yes   | Yes   | Yes   | Yes |
| [SD card speed test](https://gopro.github.io/labs/control/extensions)                       | Yes     | Yes     | Yes   | Yes   |       |     |
| [Spirit Level Display](https://gopro.github.io/labs/control/extensions) on rear LCD         | Yes/No  |         |       |       |       |     |
| [Sunrise/Sunset starts](https://gopro.github.io/labs/control/solartimelapse)                | Yes     | Yes/No  | Yes   | Yes   | Yes   | Yes |
| [Time delayed Starts](https://gopro.github.io/labs/control/custom)                          | Yes     | Yes     | Yes   | Yes   | Yes   | Yes |
| [Time/date/timecode QR Code](https://gopro.github.io/labs/control/precisiontime)            | Yes     | Yes     | Yes   | Yes   | Yes   | Yes |
| [Tone Mapping Controls](https://gopro.github.io/labs/control/extensions)                    | Yes     | Yes     |       |       |       |     |
| [Trigger - Accelerometer](https://gopro.github.io/labs/control/imutrigger)                  | Yes     | Yes     | Yes   | Yes   | Yes   | Yes |
| [Trigger - GPS speed](https://gopro.github.io/labs/control/speedtrigger)                    | Yes     | Yes/No  | Yes   | Yes   | Yes   | Yes |
| [Trigger - Gyroscope](https://gopro.github.io/labs/control/imutrigger)                      | Yes     | Yes     | Yes   | Yes   | Yes   | Yes |
| [Trigger - IMU Motion](https://gopro.github.io/labs/control/imutrigger)                     | Yes     | Yes     | Yes   | Yes   | Yes   | Yes |
| [Trigger - Motion detection](https://gopro.github.io/labs/control/motion)                   | Yes     | Yes     | Yes   | Yes   | Yes   | Yes |
| [Trigger - Sound Pressure Level](https://gopro.github.io/labs/control/spltrigger)           | Yes     | Yes     | Yes   |       |       |     |
| [Trigger - USB Power](https://gopro.github.io/labs/control/usb)                             | Yes/No  | Yes/No  | Yes   | Yes   |       | Yes |
| [Upload scripting](https://gopro.github.io/labs/control/dailytl)                            | Yes     | Yes     | Yes   |       |       |     |
| [USB power trust override](https://gopro.github.io/labs/control/extensions)                 | Yes     | Yes/No  |       |       |       |     |
| [Wake on Power](https://gopro.github.io/labs/control/extensions)                            | Yes     | Yes     |       | Yes   |       |     |
| [Wider Color Gamut](https://gopro.github.io/labs/control/extensions)                        | Yes     |         |       |       |       |     |
| [White Balance Lock](https://gopro.github.io/labs/control/extensions)                       | No/Yes  |         |       |       |       |     |

## Software 

Labs is expanding, experiment software for GoPro users [GoPro Labs software](software).

updated: August 10, 2023<br>
