---
author: Samael
pubDatetime: 2024-05-31T14:27:52.737Z
title: Instrumentation Lab
postSlug: instrumentation-lab
featured: false
ogImage: https://user-images.githubusercontent.com/53733092/215771435-25408246-2309-4f8b-a781-1f3d93bdf0ec.png
tags:
  - Visits
description: My Experience at IUCAA's Instrumentation-Lab
---


# My Experience with IUCAA's Summer School Program: Instrumentation Lab

Hello, I'm Sahil Ashok Sawant, a B.Tech student in Electronics and Telecommunications Engineering with a deep passion for astronomy. Recently, I had the incredible opportunity to participate in the IUCAA Summer School Program in Astronomy and Astrophysics (ISSAA). This program, organized by the Inter-University Centre for Astronomy and Astrophysics (IUCAA), allowed me to immerse myself in the fascinating world of astronomy and astrophysics. One of the highlights of this program was my visit to IUCAA's laboratories, including the Precision and Quantum Measurement (PQM) Lab, where I had the chance to work on some cutting-edge projects.

# Telescope Simulator: Bridging the Gap between Theory and Practice
### Objective
The primary objective of the Telescope Simulator project was to develop a comprehensive simulator that replicates the movements and mechanical behavior of a real telescope. This simulator is crucial for testing and calibrating observational instruments and techniques without relying on actual telescopes, which can be both expensive and logistically challenging.

### Key Features and Specifications

### 1. Mechanical System

The simulator features three arms of rotation:
* Altitude: Vertical movement to adjust the telescope's angle.
* Azimuth: Horizontal rotation to change the telescope's orientation.
* Polarization Plane: Adjusts the plane of polarization for precise observation settings.
Counterweights made of lead ensure the simulator remains balanced and operates smoothly, with a mechanical locking system securing its positions.

### 2. Fabrication Techniques
The fabrication process included:

* Ultrasonic Cleaning: Ensuring all parts were free from contaminants.
* Thermal Wrap Chamber: Controlled heating processes for specific materials.
* 3D Printing: Creating custom parts with complex geometries.
* Ultraviolet Gluing: Using UV light to cure adhesives for strong and precise bonding.
* Optomechanical Subsystem
Advanced tools like an interferometer and a profilometer were used to measure precise distances and ensure the smoothness and accuracy of the mechanical components.

### 3. Software and Electronics Integration
The electronic aspects were managed by Sakya Sinha, focusing on FPGA programming and digital logic design. Sujeet Punnadi developed the software interfaces and drivers. We utilized open-source libraries and developed customized solutions for device control and interfacing. The use of FPGA technology allowed for efficient real-time processing and precise control of the simulator's functions.

# SUIT Payload: Unlocking the Secrets of the Sun

### Objective
The Solar Ultraviolet Imaging Telescope (SUIT) project aimed to capture high-resolution images of the Sun's ultraviolet emissions, enabling detailed study of solar activities such as flares and differential rotation.

### Key Components and Features
### 1. Optical System
The optical system consisted of lenses and mirrors to collect and focus ultraviolet light, a filter wheel to isolate specific wavelengths, and a light detector to produce high-resolution images.

### 2. Electronics
The frontend electronics handled sampling and sequencing of the captured data. Backplane cards managed clock drivers, pixel arrangement circuitry, processing electronics, and biasing systems. Space-grade FPGAs provided by ISRO ensured reliability in the harsh space environment.

### 3. Onboard Intelligence and Data Handling
A microcontroller, also provided by ISRO, managed overall system operations. IUCAA developed payload-specific logic to process the large volumes of data generated within the limited communication window. Advanced algorithms for event detection, such as flare detection and auto exposure time correction, were implemented to enhance our ability to monitor solar events accurately.

# ISDEC: Advanced Electronics Control for Astronomy

### Objective
The IUCAA SIDECAR Drive Electronics Controller (ISDEC) project aimed to develop a fully programmable electronics controller for the Teledyne HAWAII type Detector (H4RG), offering an alternative to the Teledyne JADE2 based controller.

### Key Features and Specifications
### 1. Hardware
ISDEC controlled the H4RG IR Detector using the SIDECAR ASIC, operating at extremely low temperatures within a cryogenic Dewar. A Xilinx Spartan-IIIE FPGA supported the CMOS and LVDS interfaces with the SIDECAR ASIC. The system featured high-speed USB 2.0 interface for communication and fast data readout.

### 2. Software
Developed primarily in C, the Linux-based software ensured compatibility with widely used Linux distributions. The system supported high-speed asynchronous data transfers and flexible configuration via command line interfaces and parameter files.

**_Conclusion_**
Participating in the IUCAA Summer School Program and working on these groundbreaking projects was a transformative experience. It deepened my understanding of the intricate interplay between instrumentation, telecommunications, and physics. The hands-on experience in the laboratories, combined with the guidance from experts like Dr. Sujaya Das Gupta and Dr. Stanley Johnson, has significantly enhanced my skills and knowledge.

I am grateful for the opportunity to contribute to these innovative projects and look forward to applying what I have learned in my future endeavors. This experience has reaffirmed my passion for astronomy and has set a strong foundation for my career in this exciting field.








