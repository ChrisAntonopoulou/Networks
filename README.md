# Networks

Welcome to my Networks Projects Repository! This repository contains my assignment for my MSc at University of York. 

## Requirements

You have been appointed as the Network Consultant for a fictional company called York-Environmental Water Treatment (YEWAT). The company is run separately from
the local water supply company but maintains strong reporting links. The company is tasked with managing the wastewater treatment for the catchment
area on behalf of the local water utility. Water treatment removes contaminants and undesirable components or reduces their concentration so that the water becomes fit
for its desired end use. This treatment is crucial to human health and allows people to benefit from both drinking and irrigation use.

The company uses technology to dynamically monitor inflows of wastewater, analyse treated water quality, and monitor the quality and volume of outflows of clean water
to the water supply system using SCADA sensors. A SCADA system is a combination of hardware and software that enables industrial process automation by capturing
Operational Technology (OT) real-time data. SCADA connects the sensors that monitor equipment like motors, pumps, and valves to an onsite or remote server.

The network infrastructure could be described as hybrid, with the laboratory and operations centre utilising existing wired networks onsite but trialling the use of IoT
devices and drones to complement their data collection and analysis.

For the purposes of this assessment, you will be analysing the network requirements for the wastewater site. The site contains the following buildings and facilities:
- An Operational Control Room (HQ).
- A Water Quality Laboratory.
- The IT Department (Data Centre).
- Several water treatment ponds with wired TCP/IP SCADA sensors that can
operate the gates and pumps, which are distributed across the whole area of
the site.
- Remote wireless IoT devices and drones.

Network Requirements:

The network should give access to the correct department networks by job role. This includes access to their own departmental records and those that they interact with.
You do not need to consider the low-level details of how wastewater treatment works, but you should design the network to meet the following business needs:

- The Operational Control Room staff monitor and control all inflows to, and
outflows from, the water treatment works and are in control of the pumping
and water treatment sensors. These include the SCADA sensors used to
operate sluice gates and pumps, which are part of a permanent wired network.

- The Water Quality Laboratory staff are responsible for sampling and testing
water quality. They generate data which is stored on a server in the IT
Department building.

- The IT Department (Data Centre) consists of work-stations and servers that
store and analyse data collected from the treatment ponds and laboratories
and provide services to all other buildings.

- The company is trialling several IoT devices that monitor weather conditions
and water levels across the wider area. Many are fixed but include some
mobile drones. These devices connect to 4G networks and transmit their data
to the cloud.

- Due to cost issues, the business stakeholders have chosen not to run physical cables
between the buildings. However, the offices are spaced out so that any wireless
communication from one building to another is subject to environmental factors such
as rain and cold, resulting in a weak signal being emitted.

This assessment is broken down into three tasks to address the following stakeholder
concerns:

Concern 1: 

Analyse the requirements given in the scenario and design the physical
layout of the proposed system, IP address design and the network components to
meet the requirements of the scenario.

Concern 2: 

The IT Director has highlighted the importance of connectivity between
the site buildings and the importance of a strong signal between them. She also has
concerns about the resilience and availability of remote devices and sensors.

Concern 3: 

The Chief Information Security Officer (CISO) is concerned about the
impact and feasibility of the proposed transition from SCADA sensor technology to IP-
based wireless cyber-physical devices that control the flow of water into and out of
the treatment ponds.


## Contact
If you have any questions about this repository or specific projects, feel free to reach out:

- LinkedIn: [ <img  alt="Java" width="30px" style="padding-right:10px;" alt= "LinkedIn" title="My LinkedIn profile"
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linkedin/linkedin-original.svg">](https://www.linkedin.com/in/chrisantonopoulou/)

- Github: [ <img alt="Java" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg">](https://github.com/ChrisAntonopoulou)


**Note**: *This repository is for personal use and academic reference only. Unauthorized use or distribution of any project in this repository is prohibited.*
