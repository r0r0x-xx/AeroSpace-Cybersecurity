
# An introductory overview of aerospace, satellites, and related topics.

Hey Folks! Over the past three years, I have been self-taught in aerospace technology, dedicating a lot of time to learning and researching this field. This repository is a compilation of ideas, notes, and observations I have gathered during this journey. I have organized the material in a clear and coherent manner (I hope so! XD), starting with satellite technology, followed by general aerospace security, and finally, exploring how to hack satellites. I hope you find this resource useful for enhancing your understanding and knowledge of this fascinating field! :)

## Contents

* [Introduction](##Introduction)
* [Types of orbits used in satellite communication](##Types-of-orbits-used-in-satellite-communication)
* [Types of satellites, categories, and services](##Types-of-satellites,-categories,-and-services)
* [Key hardware components of satellites](##Key-hardware-components-of-satellites)
* [Key software components of satellites](##Key-software-components-of-satellites)
* [Key components of satellite communications between satellites and ground stations.](##Key-components-of-satellite-communications-between-satellites-and-ground-stations.)
* [Types and formats of data sent or used by satellites](##Types-and-formats-of-data-sent-or-used-by-satellites)
* [Types of antennas used in ground Stations for satellite communication](##Types-of-antennas-used-in-ground-stations-for-satellite-communication)
* [Introduction to Cybersecurity in Satellite Technology](##Introduction-to-Cybersecurity-in-Satellite-Technology)
* [Offensive cybersecurity in Aerospace and satellite technology](##Offensive-cybersecurity-in-Aerospace-and-satellite-technology)
* [Tools and techniques](##Tools-and-techniques)


## Introduction 

**What is aerospace cybersecurity?**

Aerospace cybersecurity is critical for protecting the integrity of both aircraft and spacecraft operations. In a time when cyber threats are constantly evolving, it is vital to implement strong security measures to safeguard sensitive systems and data within the aerospace sector. By prioritizing aerospace cybersecurity, we can ensure the safety and reliability of our air and space industries, which in turn helps maintain public trust and promotes technological innovation.


## Satellite orbits and technologies

Satellites are objects that orbit around a planet or other celestial bodies. They can be natural, like moons, or artificial, which are man-made devices launched into space for various purposes. Artificial satellites serve many functions, including communication, weather monitoring, navigation, scientific research, and Earth observation.

Satellite orbits describe the paths that satellites travel around celestial bodies like Earth. These paths are shaped by the interplay between the planet's gravitational force and the satellite's velocity. Orbits are key in determining a satellite's purpose, its cover area, and how long it can operate. Technically, orbits are characterized by altitude, inclination, eccentricity, and time to complete a full revolution.


## Types of orbits used in satellite communication

**LEO - Low Earth Orbit**

- Satellite elevation: Between 160 km  and 2,000 km above the Earth's surface.
- **Main characteristics**:
    - Short orbital period: 90 to 120 minutes, allowing multiple daily visits to the same region.
    - The low relative speed for the Earth's surface.
    - High atmospheric drag, especially at altitudes below 500 km, causes more significant orbit degradation and requires propulsion systems to maintain it.
- **key functions:**
    - **Communications constellations:** These are designed to provide global broadband connectivity.
    - **Earth observation satellites**: Include scientific missions that monitor climate change, agricultural activities, and natural disasters.
    - **Spy satellites**: These are used by government agencies due to their high image resolution from low altitudes.
- **Limitations in this orbit**:
    - Need for large constellations for continuous coverage.
    - Increased risk of collisions due to the density of objects in this region.


**MEO - Medium Earth Orbit**

- **Satellite elevation**: Between 2,000 km  to 35,786 km.
- **Main characteristics**:
    - Depending on altitude, an orbital period of 2 to 12 hours offers more excellent orbital stability compared to LEO.
    - Less atmospheric interference extends the satellite's lifetime and reduces the need for frequent maneuvers.
    - Improved regional coverage due to increased visibility range.
- **key functions:**
    - **Navigation systems**: GPS, Galileo, GLONASS, and BeiDou. Satellites in MEO offer consistent and accurate signals for global positioning.
    - **Scientific satellites**: Designed for long-term monitoring missions, such as analysis of Earth's magnetic fields.
- **Limitations in this orbit**:
    - Requires powerful telecommunications systems due to the greater distance from the Earth's surface.
    - Lower spatial resolution compared to LEO satellites.


**GEO - Geostationary Earth Orbit**:

- **Satellite elevation**: 35,786 km on the Earth's equator.
- **Main characteristics**:
    - Satellites are positioned with an angular velocity that synchronizes with the Earth's rotation, enabling them to maintain a fixed position in the sky.
    - They provide continuous coverage of one-third of the globe, which is ideal for television broadcasting and meteorology services.
    - The satellite density in this orbit is lower than the Low Earth Orbit (LEO), reducing the risk of collisions.
- **key functions:**
    - Global telecommunications: This includes satellites such as Intelsat and SES.
    - Weather monitoring: Satellites like GOES provide essential data for real-time weather predictions.
    - Early warning systems: These are crucial for detecting natural phenomena, including hurricanes and earthquakes.
- **Limitations in this orbit**:
    - The launch costs are elevated due to the substantial energy required to reach altitude.
    - There is a communication delay of approximately 240 ms or more, which could affect time-sensitive applications.


**HEO - Highly Elliptical Orbit**:

- **Main characteristics**:
    - Orbits with a low perigee (ranging from 300 to 1,000 km) and a high apogee (exceeding 35,786 km) allow for extended periods in the apogee region.
    - A high inclination angle makes these orbits ideal for providing coverage in high-latitude or polar regions.
    - Increased exposure to space radiation at apogee necessitates robust systems to protect electronic components.
- **key functions:**
    - Polar Monitoring: This is utilized by meteorological and scientific satellites that observe polar regions.
    - Space Telescopes: Certain high Earth orbit telescopes benefit from the long duration of apogee, allowing for continuous observations.
    - Military Communication: This offers stable communication services in regions that are geographically inaccessible to low Earth orbit (LEO) or geostationary (GEO) satellites.
- **Limitations in this orbit**:
    - Complex trajectory requires precise control for orbital stability.
    - Increased exposure risk to charged particles from the Van Allen Belt.


## Types of satellites, categories, and services

This overview outlines the main types of satellites, highlighting their functions, purposes, and examples. Satellites are categorized based on their specific applications and the services they provide to industries, governments, and everyday users.

**Communication satellites:**

- Objective and application:
    - They facilitate the transmission of data, television, telephony, and high-speed internet access.
    - Intercontinental links that reduce the need for terrestrial infrastructure, essential in remote regions or with little terrestrial connectivity.
- Highlighted examples:
    - Intelsat: Provides global telecommunications services with a vast network of satellites in GEO.
    - SES: Satellite video transmission and Internet access, operating satellites in both GEO and MEO orbits through its O3b constellation.
- Technical aspects:
    - Frequency band: They use bands such as Ku (12-18 GHz) and Ka (26-40 GHz) to maximize bandwidth.
    - Unicast: For specific point-to-point communications.
    - Broadcast: For transmitting content to large audiences, such as satellite television.
    - Multicast: For distributing data to a defined group, common in business networks.

**Earth observation satellites**

- Objective and application:
    - Collection of environmental images and data for monitoring changes in the Earth's surface, predicting weather, and conducting environmental impact studies.
    - Applications in agriculture, natural resource management, and the monitoring of natural disasters.
- Highlighted examples:
    - Sentinel (Copernicus Program): Captures multispectral data for monitoring climate change and environmental disasters.
    - Landsat: A Series of satellites operated by NASA and the USGS, pioneering continuous monitoring of the Earth's surface since 1972.
- Technical aspects:
    - Spatial resolution: variations from 10 m (Sentinel-2) to 30 m (Landsat-8).
    - Re-visit frequency: ability to observe the same area every few days in LEO.
    - Sensors: equipped with optical cameras, infrared radiometers, and synthetic aperture radars (SAR) for continuous monitoring under weather conditions.


**Navigation Satellites**

- Objective and application:
    - Provide global positioning services (GNSS) and precise time synchronization.
    - It is essential for civil and military applications, such as air, maritime, and land navigation, and critical systems, such as electrical and financial networks.
- Highlighted examples:
    - GPS: Pioneering system offering global coverage with 24 active satellites in MEO.
    - GLONASS: Alternative to GPS, with active constellation for global services.
    - Galileo: The development system is focused on providing high precision for civil applications.
    - BeiDou: Provides regional and global services in Asia since 2020.
- Technical aspects:
    - Constellations are distributed in MEO, ensuring global coverage with multiple satellites that are always visible.
    - Signal transmission in L1, L2, and L5 bands to reduce interference and improve accuracy.

**Scientific Satellites**

- Objective and application:
    - Designed for astronomical studies, climate analysis, and exploration of physical phenomena in space.
    - They make detailed observations from space, eliminating atmospheric distortions.
- Highlighted examples:
    - Hubble Space Telescope: LEO orbit for astronomical studies in visible and ultraviolet light.
    - SOHO: Satellite at the L1 Lagrangian point, dedicated to continuous observation of the Sun.
- Technical aspects:
    - Equipped with specialized instruments such as spectrometers, telescopes, and particle detectors.
    - It is located in LEO or GEO, depending on the scientific objectives.
    - Redundant systems to avoid critical failures in long-duration missions.
    

**Military Satellites**

- Objective and application:
    - They carry out surveillance, espionage, secure communications, and tactical support activities.
    - They provide critical information in real time for military operations.
- Highlighted examples:
    - Keyhole: Optical reconnaissance satellites operated by the United States.
    - Milstar: Jamming-resistant military communications satellites.
- Technical aspects:
    - Highly encrypted to protect sensitive data.
    - Equipped with advanced radar and multispectral monitoring systems.
    - Frequent orbital maneuvers to avoid detection or tracking.

**Nanosatellites and CubeSats**

- Technical aspects:
    - Nanosatellites are satellites with a mass of less than 10 kg, designed to be compact and efficient. At the same time, CubeSats are a specific type of nanosatellite built in modular units of 10x10x10 cm (called 1U).
    - Their modular architecture allows scalable configurations, such as 1U, 2U, 3U, and up to 6U, adapting to various scientific, educational, and commercial applications.
    - Reduced cost: They use standard commercial components (COTS - Commercial Off-The-Shelf) to minimize the cost of manufacturing and launch.
    - Flexibility: It is ideal for short-duration experiments in low orbit (LEO) or for testing new technologies.
    - Deployment: Frequently launched as secondary payloads on commercial rockets.
- Highlighted examples:
    - Scientific: They allow scientists to observe atmospheric phenomena, measure space radiation, and study orbital dynamics.
    - Educational: They offer universities and research centers an affordable platform for practical training in aerospace engineering.
    - Designed to monitor air quality in urban areas using optical sensors and spectrometry, sending real-time data to ground stations via S-band radio frequency links.
- Technical challenges:
    - Limitations in payload capacity and power generation due to their size.
    - Greater vulnerability to mechanical failures and radiation compared to larger satellites.
    

**Commercial and Government Satellites**

- Technical aspects:
    - Specifically designed to fulfill complex and long-duration missions, integrating advanced technologies and redundant systems to ensure high reliability.
    - Commercial satellites typically focus on telecommunications, navigation, and Earth observation, while government satellites also cover scientific, meteorological, and defense applications.
    - Payload systems: These include high-resolution cameras, multi-band spectral sensors, and high-bandwidth telecommunications equipment.
    - Control subsystems: Attitude control and orientation systems (ADCS) to ensure proper payload alignment with mission objectives.
    - Power generation: High-efficiency triple-junction solar panels and advanced energy storage systems.
- Highlighted examples:
    - Commercial satellites: Intelsat constellation satellites for global telecommunications and PlanetScope satellites for high-frequency imaging.
    - Government satellites: GOES for meteorology and Keyhole spy satellites operated by intelligence agencies.
- Technical challenges:
    - High development and launch costs.
    - Strict security and data protection requirements to prevent interception or sabotage.


## Key hardware components of satellites

Satellite hardware encompasses the physical systems required for operation, ensuring functionality and mission success.

- Structure or bus: The structure provides a rigid framework that integrates and supports all satellite subsystems. It withstands mechanical stress during launch and protects internal components in orbit. Examples are the Spacebus (Thales Alenia) and the SSL 1300 platform.
- Power system: It generates and manages electrical energy using solar panels and rechargeable batteries. It ensures an uninterrupted power supply for all components. Examples are Spectrolab solar panels, used on NASA missions, and Saft lithium-ion batteries.
- Propulsion system: The propulsion system provides thrust for orbital corrections, station-keeping, and deorbiting. It typically uses chemical or electric propulsion. Examples are the RIT-10 ion thruster (electric propulsion) and MON/MMH bipropellant systems.
- Thermal control system: The system regulates internal temperatures to ensure optimal performance in extreme space conditions. Examples include MLI (Multi-Layer Insulation) to minimize heat loss and Loop Heat Pipes to transfer excess heat to radiators.
- Communication system: It facilitates data exchange between the satellite and ground stations using antennas, transceivers, and modulators. Examples are the Ka-band phased array antenna by Airbus and the iQRF modulator/demodulator used for telemetry.
- Attitude and orbit control system (ADCS): This system allows the satellite to maintain its intended orientation and trajectory. It uses devices like reaction wheels and star trackers. Examples are the Honeywell HR16 reaction wheels and Ball Aerospace star trackers used in precision alignment tasks.
- Payload system: The system carries mission-specific equipment, such as cameras, sensors, or scientific instruments. Examples are the WorldView-3 optical sensor for Earth imaging and the SAR payload on Sentinel-1 for radar mapping.
- Onboard computing and control: This system processes mission data, manages subsystems, and executes commands. Examples are the LEON3 processor and the RAD750 CPU, a radiation-hardened computer used in many NASA satellites.
- Sensors and actuators: It gather data for orientation and navigation, while actuators control physical movements. Examples are Sun sensors (Adcole sun sensors) for position tracking and stepper motors for antenna deployment.
- Data storage system:  This recolect the telemetry and payload data for later transmission to ground stations. Examples are Solid-state drives (SSDs), like the ones used in the GOES weather satellites, and high-capacity flash memory modules for CubeSats

## Key software components of satellites

Satellite software is critical in operations management, system control, and communication, enabling hardware components to operate synchronously and efficiently. Given the complexity of space missions, software systems must be robust, reliable, and secure, especially in extreme operating environments with no margin for error.

- Mission operating system (Flight Software): This software manages the satellite's overall operations, including command execution, power management, and subsystem control, such as VxWorks or RTEMS.
- Attitude and orbit control software (AOCS): Regulates the orientation and position of the satellite in its orbit using advanced algorithms.
- Mission data handling software: This software manages the collection, storage, and transmission of data generated by payload systems.
- Communication and telemetry software: This software controls the transmission and reception of signals between the satellite and ground stations. For example, protocols based on CCSDS (Consultative Committee for Space Data Systems).
- Diagnostic and monitoring software: This software performs real-time monitoring of all subsystems, detecting failures and executing recovery protocols.
- Thermal Control Software: This software coordinates thermal regulation systems to maintain hardware operating conditions.
- Security and encryption software: This software protects communications and data from unauthorized access or malicious interference.
- Propulsion management software: Monitors and controls propulsion systems during orbital maneuvers. For example systems on RIT-22 ionization thrusters.
- Payload software: This controls mission-specific instruments, such as cameras, sensors, or radars.
- Ground control interface: This allows ground stations to efficiently send commands and receive telemetry data for example the SCOS-2000 systems used in ESA missions.


## Key components of satellite communications between satellites and ground stations.

Satellite communication refers to the transfer of data between satellites and ground stations, as well as between satellites themselves. This process is facilitated by various protocols designed to address specific needs for telemetry, command, scientific data transmission, and operational control in space missions.

- Uplink: This allows the transmission of commands and configurations from ground stations to the satellite. It is designed for high reliability through redundancy and coding techniques.
- Downlink: This facilitates the transmission of data collected by the satellite, including telemetry and scientific data, to ground stations. It is optimized to minimize data loss and maximize transfer speed.

- Direct Link communication: A satellite communicates directly with a ground station or user terminal without any intermediary devices.
- Relay Satellite communication: This method involves communication between ground stations through an intermediary satellite. It is often used in broadcasting and large-scale communication networks.
- Inter-Satellite communication: In this type, satellites exchange data with one another. This is commonly seen in satellite constellations or mesh networks, which facilitate data relay or improve coverage.

**Satellite radio frequencies** are portions of the electromagnetic spectrum used for communication between satellites and ground stations, as well as among satellites. These frequencies enable the transmission of telemetry signals, commands, scientific data, navigation information, and general communications.

- L-Band (1–2 GHz):  Primarily used for Global Navigation Satellite Systems (GNSS) like GPS and Galileo, as well as mobile satellite communications and satellite tracking systems.  Provides good atmospheric penetration and is less susceptible to rain fade. However, it has limited data transmission capacity, making it suitable for low-bandwidth applications.
- S-Band (2–4 GHz): Commonly used in satellite communications for both commercial and military applications, including telemetry and data relay. Robust under adverse weather conditions, suitable for low-capacity data transfers, and offers reliable performance for Low Earth Orbit (LEO) and Medium Earth Orbit (MEO) satellites.
- C-Band (4–8 GHz): Widely utilized for satellite television, radio communications, and secure data links between ground stations and satellites. Exhibits high resistance to rain fade compared to higher frequency bands, providing reliable service for geostationary satellites, although it supports lower data rates relative to higher bands.
- X-Band (8–12 GHz): Commonly used in military, scientific, and radar applications, as well as in satellite communication systems for high-resolution imagery and secure transmissions. Offers high data capacity, is minimally affected by rain, and is optimized for radar applications and deep-space communications; however, it provides more limited coverage than lower-frequency bands.
- Ku-Band (12–18 GHz): Employed for satellite TV (Direct-to-Home or DTH), broadband satellite internet, and high-capacity communications. It supports high data throughput and lower latency but is more susceptible to rain fade, which can affect performance during severe weather.
- Ka-Band (26–40 GHz): Focused on high-capacity broadband communications, satellite internet, and data-intensive applications requiring high throughput. Delivers extremely high data rates, making it ideal for high-speed internet access and low-latency services. However, it is highly sensitive to rain fade and requires precise alignment of satellite dishes.
- V-Band (40–75 GHz): Mainly used for experimental communication systems, advanced data links, and emerging technologies. Offers very high data rates but is highly sensitive to atmospheric attenuation, limiting its practical application in certain environments.

**Satellite communication protocols** are standardized methods for exchanging data between satellites, ground stations, and other space systems. These protocols specify how data such as telemetry, commands, scientific data, and communication signals.

- CCSDS - Consultative Committee for Space Data Systems: This protocol establishes standards for telemetry and command systems in space, operating at S-band and X-band frequencies. These standards ensure reliable transmission of telemetry and commands, essential for successful space missions.
- SpaceWire: This protocol is a high-speed communication protocol for internal satellite subsystems, enabling low-latency data transmission between onboard computers. Its efficiency has led to widespread use in missions by ESA and NASA.
- PUS  -Packet Utilization Standard: This protocol manages data from space systems by packaging information. It simplifies communication between payloads and subsystems, which is crucial for Earth observation and scientific missions.
- SLE - Space Link Extension: This technology boosts communication between ground stations and satellites by enabling reliable remote data exchanges. It is vital for interplanetary missions and multi-station operations.
- DTN - Delay Tolerant Networking: This protocol addresses communication delays in space by allowing data storage and retransmission once connectivity is restored. It is essential for Mars missions and deep space exploration, safeguarding vital information.
- HDLC - High-Level Data Link Control: This protocol ensures structured communication and data integrity in telemetry systems, providing a reliable basis for data exchange in long-duration scientific missions.
- TCP/IP Adapted: This protocol is used in modern space networks for efficient scientific data transfer and telemetry. It primarily operates in the Ka-band to facilitate smooth file transfers and operational telemetry.
- ECSS - European Cooperation for Space Standardization:
The European Cooperation for Space Standardization (ECSS) promotes interoperability among space systems by standardizing protocols and enhancing communication between ground stations and satellites in ESA missions.
- TDM - Time Division Multiplexing: This allocates communication channels into time slots, allowing multiple signals to use the same frequency. It is key for high-capacity commercial satellite communications.
- ARINC 653: This protocol standardizes partitioning in real-time satellite systems, ensuring the secure execution of critical applications in areas like attitude control and propulsion in high-reliability missions.
- LoRa: This protocol is a low-power, wide-area network protocol for CubeSats that enables long-distance, low-data-rate communication, primarily in the UHF band. It advances small satellite communication technologies.
- DVB-S: Protocol used for satellite television broadcasting. It supports digital video and audio signals and primarily operates in the Ku-band, C-band, and Ka-band to deliver content efficiently via satellite.
- DVB-RCS: This protocol facilitates two-way communication through satellite, providing a return channel for interactive services. It typically operates in the Ku-band and Ka-band, enabling services such as satellite internet and telephony.
- IPoS: This protocol allows the transmission of IP-based data over satellite links, making it possible to access the internet and other data services in L-band, Ku-band, and Ka-band for broadband satellite applications.

## Types and formats of data sent or used by satellites

Data collection, transmission, and processing are crucial functions in satellite systems, as they support scientific, commercial, and defense applications. The levels and formats of processing are designed to enhance efficiency, accuracy, and compatibility with various analysis systems and end users.

- Telemetry data: This data consists of real-time information sent from the satellite to ground stations to monitor the satellite's health and status. It includes parameters like temperature, voltage, attitude, and orbit. Telemetry data is typically formatted using protocols like CCSDS.
- Command data: This data refers to the instructions sent from ground stations to control satellite operations, such as adjusting its orientation, activating or deactivating payloads, or changing operational modes. These commands are typically transmitted in binary format and encapsulated in data packets.
- Scientific data: Satellites collect various types of scientific data, such as images, measurements, and sensor readings. This data can be in formats like:
    - Raw data: Unprocessed data directly from sensors, often stored in binary or scientific file formats.
    - Processed data: Data that has been analyzed or converted into usable formats, such as CSV, NetCDF, or HDF5 for scientific analysis.
    - Image and vdeo data: Earth observation satellites or scientific satellites often send image and video data (JPEG or TIFF for images MPEG-4 or H.264 for video streams).
    - Synthetic Aperture Radar (SAR): Data in specialized formats for radar imaging.
- Navigation Data: Satellites, particularly navigation satellites (e.g., GPS), transmit navigation data, which includes position, time, and velocity information. This is usually in a specific binary format, often following the NMEA or RTCM standard.
- Data for Communication Services: Data used for satellite communication services (e.g., broadband or broadcasting) is transmitted in packetized form, typically using IP (Internet Protocol) for networking. Formats such as MPEG-2 or MPEG-4 are used for video and IP packets for internet data transmission.
- Payload Data: Payload data refers to the data collected by a satellite's mission-specific instruments or payloads. Formats for payload data vary greatly depending on the mission and payload type.
- Status reports and logs: Satellites often send operational logs and status reports, formatted in text or binary, for diagnostics and system performance monitoring. These formats may include log entries in XML or JSON for easier parsing and interpretation.
- Data for Inter-Satellite Communication: Data exchanged between satellites in a constellation (for purposes like relaying information or forming a network) typically follows standardized protocols such as SpaceWire or CCSDS. The format is often in binary or specialized packetized formats optimized for low-latency and high-throughput data exchange.

## Types of antennas used in ground Stations for satellite communication

Ground stations rely on advanced antenna systems to establish and maintain reliable communication links with satellites. Selection of an antenna and its associated components is based on the satellite's orbit, the frequency band used, and specific mission requirements such as data volume and link quality.

- Parabolic reflector antennas: These antennas focus radio waves toward a receiver, making them highly directional. They are commonly used in large communication satellites, broadcasting satellites, and Earth observation satellites, as well as in large ground-based satellite dishes and geostationary satellites.
- Phased array antennas: These antennas can electronically steer the direction of their beam without the need for physical movement. They are widely used in Low Earth Orbit (LEO) satellites, modern communication satellites, and military satellites, such as the Starlink constellation and various military communications systems.
- Helix antennas: Designed for circular polarization, these antennas are ideal for communication between satellites and ground stations. They are handy for S-band and L-band communications, exemplified by the Iridium constellation.
- Patch antennas: Flat antennas that are often employed for high-frequency satellite communications, providing wide-angle coverage. These antennas are typically used in small satellites and CubeSats, making them suitable for small satellite communication systems.
- Horn antennas: Known for their high gain and directional communication capabilities, horn antennas are often used at higher frequencies for inter-satellite communication. They are crucial in space science satellites and systems where high precision is required, such as high-frequency communication systems on interplanetary satellites.



