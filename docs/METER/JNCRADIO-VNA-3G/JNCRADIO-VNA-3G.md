
# TUTORIALS
---
* [GENERAL INTRODUCTION IN ENGLISH BY @MLS](https://www.youtube.com/watch?v=rNNP-izZUbo&t=78s)
* [ANTENNA SETUP(SWR&SMITH CHART)](https://www.youtube.com/watch?v=1UaOFN1Xf1g)
* [CABLE LOSS MEASUREMENT IN ENGLISH BY @CHELEGANCE](https://www.youtube.com/watch?v=OA9Fm3M0ty8&t=2s)
* [FIRMWARE UPGRADE](POSTS/FIRMWARE-UPGRADE.md)


# RESOURCES
---
## USER MANUAL

- [JNCRADIO VNA 3G User Manual_V1.0](JNCRadio VNA 3G Portable Vector Network Analyzer User Manual V1.0_0.1.pdf)

## FIRMWARE UPDATES

- [v1.1.0_LATEST](JNCRadio_VNA_3G_firmware_v1.1.0.zip) - RELEASED 2022.8.19
```
1. Scan points increased to 1001;
2. When only channel S11 is turned on, the acquisition and processing of channel S21 will be automatically stopped to speed up scanning;
3. Corrected the sign of group delay value, and improved the group delay noise;
4. Fixed the bug of TDR mode;
5. When 'save' or 'recall' command is sent with no arguments, the status of all save/recall slots will be printed;
6. Dark mode support: copy 'dark_mode.txt' to the root directory of the VNA to enable dark mode;
7. Optimized the display format of the frequency range on the main screen;
8. Add the battery level icon.
```

- [v1.0.2](V1.0.2.zip) – RELEASED 2022.1.25
```
1.COMPATIBLE WITH NANOVNA-SAVER-0.3.10, CAN BE RECOGNIZED AS ‘JNCRADIO’.

2.FIXED KNOWN TYPOS.
```
- [v1.0.0](V1.0.0.zip)

## DESKTOP SOFTWARE PACKAGES

- [0.3.10_LATEST](../nanovna-saver-0.3.10.exe) – RELEASED 2022.1.25

```
1.SWEEP POINTS CAN BE SET UP TO 501 POINTS(101,201 IN PREVIOUS VERSIONS)

2.COMPATIBLE WITH JNCRADIO-VNA-3G
```
- [0.3.8](../nanovna-saver-0.3.8.exe)


# Q&A
---

* Why my boot up screen and the firmware loading screen come out scrambled, does it mean my device is defective?

    No worries this is a known case. The reason was that the clock of the bootloader was too fast and some screens couldn't follow and showed scrambled information. The way to fix it is to update the bootloader but that's not something an end user can do.

    However it doesn't need to be fixed and It won't affect any usages of the VNA.



* Is there a Battery level indication?

    (YES for the latest firmware - v1.1.0)
    Battery level indication is now(firmware version 1.0.2 and previous) presented by voltage figures - lower than 3.4v to recharge is recommended, and lower than 3.2v devices will auto be turned off. This can be later changed to percentage in a later firmware upgrade.


* How do you set the time from the front panel?

    RTC time needs to be set from the command line - there are instructions in the manual.

* What are the differences from the early version(f v2)?

    1.Scanning speed increased by 4 times to 400 points/s ;  
    2.Scanning points up to 501, which will present more details of the measurement;  
    3.Up to 13 calibration state storage slots;  
    4.Snp files are named with RTC time, which is easy for viewing;  
    5.More powerful processor makes the operation smoother and facilitates subsequent firmware upgrades to add more new features.   
