# p8-smartwach
P8 Smartwatch (Colmi) hacking resources page

"the p8 watch is a pinetime, same hardware, pinouts, manufacturer. Some minor differences on how the button is handled exist" - enaon
"PineTime and P8 are almost identical but attract different types of developer" - Daniel Thompson

Buy: https://pl.aliexpress.com/item/4000557708951.html (18$)
Product page: https://www.colmi.com/products/p8-smartwatch

# Alternative software
- WaspOS (MicroPython)
  - https://github.com/daniel-thompson/wasp-os
  - documentation: https://wasp-os.readthedocs.io/en/latest/index.html
  - forum: https://forum.pine64.org/showthread.php?tid=9017
  - instaling tutorial
  [![Alt text](https://img.youtube.com/vi/VJoDtMy-4pk/0.jpg)](https://www.youtube.com/watch?v=VJoDtMy-4pk)
- ATCwatch (C)
  - https://github.com/atc1441/ATCwatch
 [![Alt text](https://img.youtube.com/vi/rRqulnz1nJM/0.jpg)](https://www.youtube.com/watch?v=rRqulnz1nJM)
- Espurino (js)
  - https://github.com/fanoush/ds-d6/tree/master/espruino/DFU/P8
[![Alt text](https://img.youtube.com/vi/PgB1PQA5_OQ/0.jpg)](https://www.youtube.com/watch?v=PgB1PQA5_OQ)
- P8-nb (Espurino)
  - ninebot speed meter, calculator
  - https://github.com/enaon/ninebot-one-nRF52/tree/master/p8-nb
  [![Alt text](https://img.youtube.com/vi/4hs8I65Fz5g/0.jpg)](https://www.youtube.com/watch?v=4hs8I65Fz5g)
   

  
- Gitter discussion
  - https://gitter.im/nRF51822-Arduino-Mbed-smart-watch/Lobby?at=5eaeabe831a6d25d7ca726f3
  
# How to flash with DaFlasher
- https://github.com/atc1441/DaFlasherFiles
- https://play.google.com/store/apps/details?id=com.atcnetz.paatc.patc
[![Alt text](https://img.youtube.com/vi/gUVEz-pxhgg/0.jpg)](https://www.youtube.com/watch?v=gUVEz-pxhgg)

- Other DaFlasher compatible smartwaches and branclets
 - https://gist.github.com/atc1441/d0a3c1f5ee69ab901bccba4eb47a6e4e

# Revert to original firmware
Daniel Thompson
"You will need to revert back to SoftDevice 5 and have a copy of the original firmware. I can help with the first bit but I didn't make any firmware backup (and couldn't legally share it even if I had) so I am not able to provide a copy of the original firmware. Anyhow, if you do have a backup then note that the the zip updates in DaFlasherFiles cannot be applied directly to wasp-bootloader but we can return to the DaFlasher bootloaders by installing https://github.com/fanoush/ds-d6/blob/master/micropython/DS-D6-adafruit-back-to-desay-sd132v201.zip followed by ATCdfuFromSD2toSD5.zip . If you don't have a backup and decided you didn't like wasp-os then perhaps you could try ATCwatch to see if you like that better!"

# Other usfull informations
- P8 Pinouts
  - https://files.gitter.im/nRF51822-Arduino-Mbed-smart-watch/Lobby/oFNe/P8pinout.jpg

# Other hackable watches (prices are not including shipping)
- PineTime (only not glued devkit) 25$
  - https://www.pine64.org/pinetime/
  - https://wiki.pine64.org/index.php/PineTime
  - buy: https://store.pine64.org/?product=pinetime-dev-kit
  - avalable OSes: https://wiki.pine64.org/index.php/PineTime#Development_efforts
    - InfinityTime - https://github.com/JF002/Pinetime/blob/master/README.md
    - Visual Rust - https://marketplace.visualstudio.com/items?itemName=LeeLupYuen.visual-embedded-rust
    - CHIP-8 games - https://lupyuen.github.io/pinetime-rust-mynewt/articles/chip8
- BangleJS (moded NO1 F18) 90$
  - https://banglejs.com
- Pebble (not made any more, old one could use Rebble)
- LILYGO® TTGO T-Watch-2020 (seams simple to program, but battery seems not to last long) 30$
  - https://www.tindie.com/products/ttgo/lilygor-ttgo-t-watch-2020/ 
- SMA-Q2 58$
  - https://github.com/emeryth/sma-q2-oss
  - https://hackaday.io/project/85463-color-open-source-smartwatch
  - Buy: https://pl.geekbuying.com/item/SMA-Q2-Smartwatch-Heart-Rate-Monitor-Black-389947.html
- Hexiwear (it stopped in 2017) 56$
  - https://www.mikroe.com/hexiwear 
- Watchy (isn't waterproof) 55$
  - https://www.hackster.io/news/sport-your-hacker-status-on-your-wrist-with-watchy-an-esp32-powered-smartwatch-3db389fd4bc3
  - https://github.com/sqfmi/Watchy-Hardware
- Amazfit Bip (games, calculator, seems hard to create apps) ~50-65$
  - https://github.com/Freeyourgadget/Gadgetbridge/wiki/Amazfit-Bip-OS
- TG-Watch02
  - https://www.reddit.com/r/pebble/comments/g7pgrc/homemade_python_smart_watch/
  
# Micropython learning
- https://realpython.com/micropython/
