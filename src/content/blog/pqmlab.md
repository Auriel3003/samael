---
author: Samael
pubDatetime: 2024-05-30T14:27:52.737Z
title: PQM Lab
postSlug: pqm-lab
featured: false
ogImage: https://user-images.githubusercontent.com/53733092/215771435-25408246-2309-4f8b-a781-1f3d93bdf0ec.png
tags:
  - Visits
description: My Experience at IUCAA's PQM-Lab
---



# My Experience at IUCAA's Precision and Quantum Measurement Laboratory

... By Sahil Ashok Sawant

As a budding engineer with a passion for astronomy, my journey took an exciting turn when I was selected for the ISSAA summer school program organized by the **Inter-University Centre for Astronomy and Astrophysics (IUCAA)**. This opportunity not only allowed me to delve deeper into my research interests in _**Instrumentation**, **Telecommunications**, and **Physics**_ but also gave me the chance to work alongside some of the most brilliant minds in the field. Among the many enriching experiences, my exposure to **IUCAA's Precision and Quantum Measurement Laboratory (PQM)** stands out as particularly transformative.

## Exploring the Radio Frequency Synthesizer

Under the expert guidance of Dr. Sujaya Das Gupta, I was introduced to the intricacies of developing a Radio Frequency (RF) Synthesizer. The objective of this project was to create a precise RF synthesizer tailored for quantum science and technology applications, particularly for quantum state manipulation, which necessitates highly stable and accurate frequency sources.

The RF synthesizer we worked on is a marvel of modern engineering, featuring:
* Atomic Clock Reference (10 MHz): This ensures the synthesizer's high precision and stability, a critical component for maintaining the integrity of quantum state manipulations.
* Stability Metrics: The synthesizer boasts impressive short-term stability of 10^11 units and long-term stability of 10^40 units, making it exceptionally reliable over various durations.
* Dual Channel Synthesis: Each channel allows for independent control of frequency, phase, and amplitude, with phase synchronization ensuring coherent signal generation.
* Digital Control and Generation: Advanced DSP techniques minimize noise, and the system is capable of rapid frequency transitions with a high resolution of up to 48 bits.

One of the most exciting aspects of this project was working with the Direct Digital Synthesis (DDS) technology, controlled by a Raspberry Pi 4B. This setup not only provides high precision and flexibility but also incorporates robust SPI communication protocols, ensuring stable and efficient performance.

Through this project, I gained a deeper understanding of:
1. The critical role of atomic clocks in maintaining frequency stability.
2. The importance of low noise digital signal processing in high-precision applications.
3. The intricacies of integrating hardware components such as DDS chips, VCOs, ADCs, and DACs with microcontrollers.

## Fiber Optics Noise Cancellation System

The second major project I worked on, guided by Dr. Stanley Johnson, focused on the stability and reliability of message transmission using fiber optics. This project aimed to mitigate environmental noise, such as vibrations, that can adversely affect signal integrity.

The fiber optics noise cancellation system connects IUCAA and IISER over a distance of 15 km, with a simulated setup extending the range to 50 km. The system is designed to cancel frequency noise, maintaining the stability of the transmitted signal.

Key components included:
* Acousto-Optic Modulator (AOM) Driver: Modulates the light signal, encoding the message for transmission.
* ADC, FPGA, and DAC: These components work together to convert, process, and re-convert the signal, ensuring it remains stable and accurate.
* RF Synthesizer: Provides the precise RF signals necessary for signal modulation and demodulation.

The efficacy of the noise cancellation system was evident through:
1. Noise Detection: The system's ability to detect external noise sources, such as mechanical vibrations, and adjust accordingly.
2. Phase and Modulation Experiments: These experiments revealed how changes in phase and modulation impact signal stability and noise resilience, offering valuable insights for optimizing transmission systems.

This project enhanced my understanding of:
* The role of acousto-optic modulators in optical communication.
* The integration of ADCs, FPGAs, and DACs for real-time signal processing.
* The critical importance of noise cancellation in maintaining the integrity of long-distance optical communication.

### Conclusion
My time at IUCAA's PQM Lab was nothing short of extraordinary. Under the mentorship of Dr. Sujaya Das Gupta and Dr. Stanley Johnson, I not only gained hands-on experience with cutting-edge technologies but also developed a profound appreciation for the meticulousness required in high-precision instrumentation and telecommunications. This experience has undoubtedly enriched my academic journey and solidified my resolve to continue exploring the fascinating intersections of electronics, telecommunications, and physics. I look forward to applying these insights to future projects and contributing to advancements in these dynamic fields.
