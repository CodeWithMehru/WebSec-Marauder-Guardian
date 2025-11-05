JOURNAL FOR WEBSEC MARAUDER GUARDIAN

Day 1 Project kickoff and research
Researched defensive versus offensive Wi Fi tools and legal and ethical considerations
Collected references on passive Wi Fi scanning BLE sniffing and signal analysis
Decided to keep the project strictly passive and educational and documented ethics in the README
Created the initial project outline scope and success criteria
Time spent 12 hours

Day 2 BOM and parts selection
Surveyed vendors Amazon and Robu for ESP32 boards TFT displays LiPo chargers antenna and buzzer
Compiled BOM file and optimized costs with notes on parts I already own and parts to buy
Chose ESP32 DevKitC 32UE for BLE and Wi Fi support and ILI9341 TFT for display work
Time spent 10 hours

Day 3 Mechanical design and 3D case
Modeled the case layout concept including dimensions and mounting points in Fusion360 CAD
Exported STL files for front and back and iterated on fastening points and ventilation
Rendered a prototype image for repo documentation the image is a placeholder until the physical build is done
Time spent 18 hours

Day 4 Wiring diagrams and prototyping plan
Created the wiring diagram showing connections from ESP32 to TFT TP4056 to LiPo buzzer switch and SD module
Added notes on pin choices voltage rails JST connector recommendations and safety checks
Planned the breadboard test steps and listed the required tools such as soldering iron and JST crimp
Time spent 10 hours

Day 5 Firmware architecture and module design
Designed the firmware structure with modules for wifi scanning bluetooth scanning display logger gps and ota
Wrote the API and logging plan including fields timestamp ssid bssid rssi channel gps
Prepared the Arduino and PlatformIO structure with dependency notes
Time spent 23 hours

Day 6 Passive scanning experiments
Ran local experiments using ESP32 example sketches for Wi Fi scanning and BLE scanning on a dev board or simulated environment
Measured timings and power draw recorded outputs and filtered noisy SSIDs
Decided on scan intervals balancing battery life and detection latency
Time spent 16 hours

Day 7 Logging and data format
Created CSV and JSON schemas for SD and HTTP logs with example entries including timestamp ssid bssid rssi channel gps lat gps lng
Wrote logger pseudocode and SD rotation policy for file sizes and daily logs
Planned secure upload using HTTPS and token based auth
Time spent 16 hours

Day 8 Safety ethics and documentation
Expanded the README safety section and explicitly marked offensive features as disabled
Wrote the testing policy to test only on owned or permissioned networks and to record consent
Added image disclaimer in the README and updated the journal
Time spent 8 hours

Day 9 UI UX display and alerts
Designed the TFT screen layout with a status bar list of SSIDs RSSI bar graph and alert banner
Defined buzzer behaviors short beep for new network detection long beep for suspicious spikes
Sketched CLI commands for querying logs and setting thresholds
Time spent 15 hours

Day 10 Roadmap testing plan and next steps
Compiled the final roadmap purchase parts assemble prototype run controlled tests and publish firmware version 0.1
Created test plans for lab tests field tests and consent forms
Prepared files to push to the repository including firmware skeleton BOM wiring and journal
Time spent 12 hours

2025 10 31 Prototype wiring sketch BOM update and visual mockup
Created a hand drawn prototype wiring sketch and a photoreal wiring mockup showing how modules will connect
Connections shown include ESP32 DevKitC to ILI9341 TFT over SPI TP4056 to LiPo battery to slide power switch to ESP32 VIN INA219 on the battery positive MicroSD on SPI buzzer on GPIO25 and optional GPS on UART
Updated the BOM with planned parts and supplier references and prioritized low cost easy to source modules
Uploaded the wiring mockup and schematic to the proof of work folder as visual references
These images are design stage visuals and will be replaced with in hand photos and assembly logs after parts arrive or are borrowed
Time spent 6 hours

Notes
The uploaded images in the repo are prototype references to visualize the final build
Actual device photos will be added when the physical assembly is complete
Firmware and documentation are developed from scratch for educational demonstration of Wi Fi safety
The design is intended as an educational replica to help students learn about wireless threats and how to stay safe