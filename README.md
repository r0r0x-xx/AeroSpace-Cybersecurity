### Offensive Cybersecurity in Aerospace and Satellite Technology

### **1. Introduction to Satellites**

- **Satellite orbits**
    - Types of orbits: low earth orbit (leo), medium earth orbit (meo), geostationary orbit (geo), and highly elliptical orbit (heo)
    - Purposes and characteristics of different orbit types
    - Security challenges specific to various orbits
- **Satellite types - services**
    - Communication satellites
    - Earth observation satellites
    - Navigation and positioning satellites
    - Scientific and military satellites
- **Satellite types - hardware**
    - nanosatellites and cubesats
    - commercial and government satellites
    - structural differences based on satellite purpose
- **Satellite components - hardware**
    - propulsion systems
    - payload systems
    - subsystems for power, thermal control, and telecommunications
    - sensors and actuators
- **Satellite components - software**
    - satellite operating systems
    - software for navigation and attitude control
    - telemetry, tracking, and command (tt&c) management
    - risks and vulnerabilities in satellite software updates
- **Satellite communication**
    - key components of communication links (uplink, downlink)
    - commonly used radio frequencies (l-band, s-band, x-band, ka-band, ku-band)
    - communication types: unicast, multicast, broadcast
    - satellite communication bands and their applications
    - protocols and standards such as ccsds, dvb-s, and tcp/ip for space communication
- **Satellite networks**
    - network architectures (star topology, mesh, hybrid)
    - protocols used in satellite networks
    - satellite packet data protocols and data flow topologies
- **Data types and formats**
    - raw data vs processed data levels (level 0 to level 4)
    - common data formats used in satellite communication
    - examples of satellite data handling for earth observation and navigation

### **2. Introduction to cybersecurity in satellite technology**

- **Attack surfaces**
    - space segment: satellites and payload systems
    - user segment: ground terminals and user devices
    - link segment: communication channels and rf links
    - ground segment: ground stations and network infrastructure
- **Satellite attacks**
    - examples of past incidents, including sparta as a case study
    - potential vulnerabilities in satellite systems
    - understanding denial-of-service, spoofing, and interception in satellite environments
- **Satellite networks and vulnerabilities**
    - risk analysis of satellite networks
    - vulnerabilities in communication links
    - common exploitation scenarios and their implications

### **3. Tools and techniques**

- **Satellite communication analysis**
    - tools for rf signal interception and analysis
    - examples: gnuradio, sdr-based tools, and satnogs
- **Protocol analysis and testing**
    - tools for analyzing satellite-specific protocols
    - examples: wireshark, ccsds protocol analyzers
- **Satellite hardware and firmware assessment**
    - reverse engineering tools for satellite firmware
    - examples: ida pro, ghidra, binwalk
- **Simulators and emulators**
    - satellite system simulation environments
    - examples: nos3, openatkit
- **Network and ground station testing**
    - tools for network and penetration testing
    - examples: nmap, metasploit, burp suite
- **Custom exploit development**
    - scripting and payload creation for satellite systems
    - examples: python, c, and assembly for low-level interactions
