
# An introductory overview of aerospace, satellites, and related topics.

Hey Folks! Over the past three years, I have been self-taught in aerospace technology, dedicating a lot of time to learning and researching this field. This repository is a compilation of ideas, notes, and observations I have gathered during this journey. I have organized the material in a clear and coherent manner (I hope so! XD), starting with satellite technology, followed by general aerospace security, and finally, exploring how to hack satellites. I hope you find this resource useful for enhancing your understanding and knowledge of this fascinating field! :)

## Contents

* [Introduction](##Introduction)
* [Types of orbits used in satellite communication](###Types-of-orbits-used-in-satellite-communication)
* [Types of satellites, categories, and services](###Types-of-satellites,-categories,-and-services)
* [Key hardware components of satellites](###Key-hardware-components-of-satellites)
* [Key software components of satellites](###Key-software-components-of-satellites)
* [Key components of satellite communications between satellites and ground stations.](##Key-components-of-satellite-communications-between-satellites-and-ground-stations.)
* [Types and formats of data sent or used by satellites](###Types-and-formats-of-data-sent-or-used-by-satellites)
* [Types of antennas used in ground Stations for satellite communication](###Types-of-antennas-used-in-ground-stations-for-satellite-communication)
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











