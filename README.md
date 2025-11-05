Status Prototype Educational and Defensive Demonstration
Owner Developer CodeWithMehru

Project summary
Marauder is an ESP32 based wireless monitoring reference device documented as part of WebSec Marauder Guardian
The goal is educational to show students how wireless threats can be detected and how to defend networks using passive observation and logging
This repository reproduces advertised capabilities for transparency but the project is strictly defensive
All offensive features that impersonate or disrupt other devices are disabled and not used
This repo contains no code or instructions to perform attacks

Advertised features factual list with offensive items disabled
Wi Fi advertised features
Scan APs scan for nearby access points showing SSID BSSID RSSI allowed passive
Scan Stations discover client stations allowed passive
Deauth Flood sending deauth packets disabled offensive
AP Clone Spam cloning access points disabled offensive
Karma responding to probe requests disabled offensive
Evil Portal fake captive portal disabled offensive

Bluetooth advertised features
Bluetooth Sniffer sniff Bluetooth advertisements allowed passive
Detect Card Skimmers detect Bluetooth enabled skimmers monitoring only allowed passive
Sour Apple attack disabled offensive
Swiftpair Spam disabled offensive
Samsung BLE Spam disabled offensive

Other advertised features
Packet Monitor visualize Wi Fi packet density allowed passive
Signal Monitor show RSSI and signal strength allowed passive
GPS support for tagging events on owned networks allowed passive
SD Card Support save passive logs and statistics allowed passive
Web Update OTA update firmware via web allowed maintenance
CLI command line interface for diagnostics allowed
Customizable settings and multiple device support allowed

What I will actually use and demonstrate
Passive Wi Fi scanning SSID BSSID RSSI and channel with no transmission
Passive station discovery and counts only on networks I own or have permission to test
Promiscuous mode monitoring to count management frame spikes for detection only no transmitting
Passive Bluetooth advertisement scanning no pairing and no injection
Signal visualization and simple alerts on OLED and buzzer
Optional local logging to micro SD and secure HTTP upload to a private server for later analysis
GPS tagging to map events only on owned or permissioned networks
OTA updates and a simple CLI for maintenance

Safety and ethics must read
Do not run offensive features such as deauth jamming fake portals or credential capture unless you have explicit written permission and the activity is legal where you are
This repository contains no offensive code and no instructions for active attacks
Always test only on equipment you own or where you have written permission and keep records of consent

Repo contents documentation only
README file with project overview and safety notes
JOURNAL file with development and testing log
LICENSE file for project license
BOM file with parts list and suppliers
proof of work folder with wiring diagrams sketches and GitHub proof screenshots

How to contribute and learn
This repo is for documentation and education only
If you want to help open an issue or a pull request proposing defensive legal improvements like UI passive analysis or logging format
Offensive or enabling content will be rejected

Image disclaimer
The wiring images in the proof of work folder are design stage mockups used to illustrate planned connections and pin mappings
They are visual references only and in hand assembly photos and test logs will be uploaded once components are obtained

Contact
Mehru= https://github.com/CodeWithMehru