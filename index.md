---
title: P8 hack
layout: default
---


# p8-smartwach
P8 Smartwatch (Colmi) hacking resources page

P8 watch is one of many smartwatches supported by DaFit app (including PineTime). It is quite cheap (~$17 USD on aliexpress) and has full touchscreen, button and 240x240 color display.

"the p8 watch is a pinetime, same hardware, pinouts, manufacturer. Some minor differences on how the button is handled exist" - enaon
"PineTime and P8 are almost identical but attract different types of developer" - Daniel Thompson

Buy: <https://pl.aliexpress.com/item/4000557708951.html> (18$)

Product page: <https://www.colmi.com/products/p8-smartwatch>

New P9 product page: <https://www.colmi.com/products/p9-smartwatch>

# Alternative software
**WaspOS (MicroPython)**
  - <https://github.com/daniel-thompson/wasp-os>
  - documentation: <https://wasp-os.readthedocs.io/en/latest/index.html>
  - forum: <https://forum.pine64.org/showthread.php?tid=9017>
  - example of Star Trek themed modification: <https://forum.pine64.org/showthread.php?tid=11287>
  - installing tutorial

[![Alt text](https://img.youtube.com/vi/VJoDtMy-4pk/0.jpg)](https://www.youtube.com/watch?v=VJoDtMy-4pk)

**ATCwatch (C++)**
  - <https://github.com/atc1441/ATCwatch>
  - discord: <https://discord.com/channels/717057001594683422/717057210211106826>

[![Alt text](https://img.youtube.com/vi/rRqulnz1nJM/0.jpg)](https://www.youtube.com/watch?v=rRqulnz1nJM)

**Modified ATCwach**
  - <https://github.com/0x416c6578/p8-firmware>

**P8-nb (Espurino js)**
  - ninebot speed meter, calculator
  - <https://github.com/enaon/ninebot-one-nRF52/tree/master/p8-nb>

[![Alt text](https://img.youtube.com/vi/4hs8I65Fz5g/0.jpg)](https://www.youtube.com/watch?v=4hs8I65Fz5g)

**Espurino (js)**
  - <https://github.com/fanoush/ds-d6/tree/master/espruino/DFU/P8>
 
 [![Alt text](https://img.youtube.com/vi/PgB1PQA5_OQ/0.jpg)](https://www.youtube.com/watch?v=PgB1PQA5_OQ)

**Another espurino (js)**
  - <https://github.com/gerardwr/P8>



  
**Gitter discussion**
  - <https://gitter.im/nRF51822-Arduino-Mbed-smart-watch/Lobby?at=5eaeabe831a6d25d7ca726f3>
  
# How to flash with DaFlasher
- <https://github.com/atc1441/DaFlasherFiles>
- <https://play.google.com/store/apps/details?id=com.atcnetz.paatc.patc>

[![Alt text](https://img.youtube.com/vi/gUVEz-pxhgg/0.jpg)](https://www.youtube.com/watch?v=gUVEz-pxhgg)



# Revert to original firmware
Daniel Thompson: (from waspOS)

"You will need to revert back to SoftDevice 5 and have a copy of the original firmware. I can help with the first bit but I didn't make any firmware backup (and couldn't legally share it even if I had) so I am not able to provide a copy of the original firmware. Anyhow, if you do have a backup then note that the zip updates in DaFlasherFiles cannot be applied directly to wasp-bootloader but we can return to the DaFlasher bootloaders by installing <https://github.com/fanoush/ds-d6/blob/master/micropython/DS-D6-adafruit-back-to-desay-sd132v201.zip> followed by ATCdfuFromSD2toSD5.zip . If you don't have a backup and decided you didn't like wasp-os then perhaps you could try ATCwatch to see if you like that better!"

# Other useful information
- P8 Pinouts
  - <https://files.gitter.im/nRF51822-Arduino-Mbed-smart-watch/Lobby/oFNe/P8pinout.jpg>
 - Other DaFlasher compatible smartwatches and bracelets
  - <https://gist.github.com/atc1441/d0a3c1f5ee69ab901bccba4eb47a6e4e>

# Micropython learning
- <https://realpython.com/micropython/>
