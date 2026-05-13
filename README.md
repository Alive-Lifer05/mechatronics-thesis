# Level 7 Mechatronic Engineering Thesis

**Author:** Conor McGowan  
**Programme:** BEng in Mechatronic Engineering  
**Institution:** ATU Sligo  
**Level:** Undergraduate, Level 7  

## Thesis

[Download the thesis PDF](./conor-mcgowan-mechatronics-thesis.pdf)

## Description

This repository contains my Level 7 Mechatronic Engineering thesis project.

## Abstract

Upper-limb amputation can significantly affect independence, daily function, and quality of
life, creating a need for prosthetic technologies that are both responsive and accessible.
Although advanced myoelectric prosthetic systems can provide powered hand control, their
cost, complexity, calibration requirements, and maintenance demands can limit practical
availability. This project investigates a low-cost electromyography (EMG) acquisition and
intent-detection system as an early-stage control pathway for future prosthetic hand
applications.

The developed system used a SparkFun MyoWare 2.0 muscle sensor and an Arduino Nano
ESP32 to acquire forearm muscle activity from surface electrodes. The EMG signal was
sampled through the microcontroller, processed using baseline estimation, activation feature
extraction, digital smoothing, adaptive thresholding, and logged over USB serial for analysis.
A repeated rest/flex protocol was used to evaluate whether deliberate forearm contraction
could be distinguished from rest. A 3D-printed DexHand platform was retained as the
intended future mechanical output, but full prosthetic hand actuation was not treated as the
validated outcome of this work.

The final analysed session recorded 10,401 valid samples at approximately 250 Hz. The
cleaned ADC signal ranged from 505 to 583 counts, with a peak filtered activation of
0.02237 V and a mean threshold of 0.01957 V. Limited binary intent detection was achieved,
with one of five instructed flex windows detected, zero false triggers outside flex windows,
and a measured onset response of 268 ms for the detected trial.

These results show that low-cost EMG acquisition and structured analysis are feasible using
accessible hardware. However, the system also demonstrated that reliable intent detection
depends strongly on electrode placement, contact quality, cable strain, and signal margin
above rest. The work therefore provides a practical foundation for future prosthetic hand
control, while identifying the need for improved electrode mounting, calibration, and
actuation integration before dependable real-time DexHand control can be achieved.
