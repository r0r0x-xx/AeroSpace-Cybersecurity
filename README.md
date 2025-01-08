
# An introductory overview of aerospace, satellites, and related topics.

Hey Folks! Over the past three years, I have been self-taught in aerospace technology, dedicating a lot of time to learning and researching this field. This repository is a compilation of ideas, notes, and observations I have gathered during this journey. I have organized the material in a clear and coherent manner (I hope so! XD), starting with satellite technology, followed by general aerospace security, and finally, exploring how to hack satellites. I hope you find this resource useful for enhancing your understanding and knowledge of this fascinating field! :)

## Contents

* [Introduction](Introduction)
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


















