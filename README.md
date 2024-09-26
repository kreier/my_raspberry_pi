# Projects with my Raspberry Pi's

This repository is more for documentation and history of smaller ideas that materialized over the last decade.

## Raspberry Pi 1B rev 1.2

- Purchased in June 2012 with 26 GPIO pins, 512 MByte RAM, single core 700 MHz
- Used in the Physics class grade 10 in Warstade in 2013
- Start of the [T410](https://github.com/kreier/T410) project in March 2020
- Reactivated in November 2020
- Reactivated again in January 2024

![Working Pi 1B in 2020](https://raw.githubusercontent.com/kreier/T410/main/docs/RPi-T410.jpg)

## Rasberry Pi 3 B

- Purchased in 2018 at AISVN and used to stream video over composite to 7" screen
- On my work desk

## Raspberry Pi 4 

- Purchased in early 2020
- Overheating
- Peter wanted to use it to VNC his Windows PC

## Nvidia Jetson Nano

- Application for a project at hackster.io failed, so I ordered one late 2019 from mouser
- Demanding power requirements
- Idea of self driving car with camera input in early 2020 in project [jetson-car](https://github.com/kreier/jetson-car/tree/main/docs)

Robot history from 2018 is written in the [T300](https://github.com/kreier/T300) part that was stopped by import problems after lockdowns in Wuhan January 2020. We started teaching virtual in February 2020. General project overview (generated from November 2019 to December 2020) are in the https://kreier.github.io/ . And a story from December 2019 to July 2020 is in the https://kreier.github.io/solarmeter/ project. Since we could return to school in May 2020!

## Hardware Comparison

| model        | SOC       | CPU                                                           |  MHz |   ISA   | RAM | [CoreMark](https://github.com/kreier/benchmark/tree/main/CoreMark) |
|--------------|-----------|---------------------------------------------------------------|-----:|---------|----:|----------|
| Pi1B rev 1.2 | BCM2835   | 1x [ARM1176JZF-S](https://en.wikipedia.org/wiki/ARM11)        |  700 | ARMv6   | 0.5 | 1574     |
| Pi 3 B       | BCM2837B0 | 4x [Cortex A53](https://en.wikipedia.org/wiki/ARM_Cortex-A53) | 1200 | ARMv8-A |   1 | 3800     |
| Pi 4 1.1     | BCM2711   | 4x [Cortex A72](https://en.wikipedia.org/wiki/ARM_Cortex-A72) | 1500   ARMv8-A |   4 | 8257     |
