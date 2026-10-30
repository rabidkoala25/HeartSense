# HeartSense

a little magnetic field meter i made. it reads how strong the magnetic field
is around you and shows it on a screen with a scroll wheel to get through the
menu. i did the board, the firmware and a browser version.

this repo has the hardware. the code is in its own repos:

- firmware (runs on the pico): https://github.com/rabidkoala25/HeartSense-Firmware
- simulator (try it in a browser): https://github.com/rabidkoala25/HeartSenseDemo

## try it without the hardware

https://rabidkoala25.github.io/HeartSenseDemo/

## hardware/

the KiCad files are in here. open `HeartMeter.kicad_pro`. the gerbers in
`gerbers/` are what you send to a board maker, and `3d/` has the 3d models.

(stuff still says HeartMeter inside, that was the old name.)

## parts

pico, MMC5603 magnetometer, MCP73831 for charging the battery, an OLED,
a scroll wheel, a buzzer and an rgb led. only the charger is surface mount,
the rest is through-hole.
