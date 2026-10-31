# HeartSense

a little magnetic field meter i made. it reads how strong the magnetic field
is around you and shows it on a screen with a scroll wheel to get through the
menu. 

my reason for making this device is because my friend wears a pacemaker, and was concerned of being in a highly magnetic environment. this device lets them see the ambient magnetic field strength, avoiding interference with their pacemaker. 

this repo has the hardware. the code is in its own repos:

- firmware: https://github.com/rabidkoala25/HeartSense-Firmware
- simulator: https://github.com/rabidkoala25/HeartSenseDemo
    - https://rabidkoala25.github.io/HeartSenseDemo/ 

## images

<img width="655" height="1440" alt="image" src="https://github.com/user-attachments/assets/95df2061-6216-4add-840a-602462a66eac" />

<img width="1680" height="1202" alt="image" src="https://github.com/user-attachments/assets/94a3e044-752f-41af-a387-df843f0683c8" />


## hardware/

the KiCad files are in here. open `HeartMeter.kicad_pro`. the gerbers in
`gerbers/`, and `3d/`  the 3d models.

if you find anything that says HeartMeter, that's what it was called before i changed it to HeartSense

## soldering note

all components are through hole, save for the SMD charging chip which will be assembled not by me. 
