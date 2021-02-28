---
name: Firmware Bug report
about: Create a report to help us improve
title: ''
labels: bug, firmware
assignees: ''

---

**Version**
Version 10.1.0.5334 |10.1 Alpha 17|

**Target**
omnibusf4sd

**Describe the bug**
FC wont comunicate with TX after initial setup using Frsky rxsr: after first reboot of a succesfull setup,
in configuration-serial tab uart 6 is detected as inv s-bus, but arming, entering osd ect is not working.

**To Reproduce**
1. connect rxsr reciever to: 5v, ground, rx6.
2. bind to TX
3. flash latest bootloader and Falco-x firmware.
4. initial setup
5. see error

**Expected behavior**
full comunication with the flight controller.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Additional context**
using LANRC flight controller.
