##Requirements
1. hdmi display output
2. touchscreen feature for whole display portion
3. speakers for music playback
4. bluetooth and wifi connectivity
5. usb port for mouse and keyboard
6. ethernet for initial internet setup
7. headers for LED to light up inside to see internals
8. ir sensor / proximity sensor for turning display on and off


##Parts : SoC , RAM, Memory

Soc Requirements

1. boot linux
2. ethernet
3. hdmi 
4. touchscreen responsiveness


Blog Post: [microprocessor embedded design](https://jaycarlson.net/embedded-linux/)

Multi-core 1+ GHz Cortex-A parts with 256 MB of RAM - 8 GB EMCC storage

First Look: TEXAS INSTRUMENTS AM335X

AM3358BZCZA100

[mouser AM3358BZCZA100 ] (https://www.mouser.com/ProductDetail/Texas-Instruments/AM3358BZCZA100?qs=OHhYoCux73mK%2FF575s3uKw%3D%3D)

Ports Needed:

1. SDIO - Wifi/bluetooth chip
2. ??? - Audio port for speaker
3. usb - touchscreen
4. usb - mouse and keyboard
4. pwm - for led
5. LCD - hdmi output
6. ethernet
7. I2C - ir proximity sensor 

##Parts : Wifi / Bluetooth

ESP32-D0WD
https://www.digikey.com/en/products/detail/espressif-systems/ESP32-D0WD/8028403


##Parts : Speakers
PCM1780DBQ - PCM -> DAC

Audio Serial port -> DAC -> Amplifier

Amplifier will be part of a second project. Will have a audio aux connector

##Parts : HDMI

TDA19988

Uses the LCD interface 

##Parts : IR proximity sensor

MOD_CH101-03-01

Ultrasonic solution
Uses i2c

Have wire to mount it in frame

##Parts : On-Board Power Supply

PMIC for TI part


##Parts : Touchscreen

Digitizer (USB)

[Amazon digitizer] (https://www.amazon.com/Deyowo-Interactive-Points-Infrared-Overlay/dp/B08KG9BS8X/ref=as_li_ss_tl?dchild=1&keywords=ir%2Bframe%2B32&qid=1608906358&sr=8-3&linkCode=sl1&tag=sbio20-20&linkId=04ccda43b82a7187599f775fa3370137&language=en_US&th=1)


##Parts : LEDs



##Parts : Two Way Mirror

Two Way Mirror (24 inch)

[Amazon Two Way Mirror](https://www.amazon.com/SPEEDYORDERS-Acrylic-Through-Plexiglass-Unbreakable/dp/B09QQQXCZR/ref=sr_1_1_sspa?crid=3CQ39NCZ3L4L0&keywords=Acrylic%2BSee-Through%2BMirror%2C%2B30%25%2BTransparent&qid=1676740098&s=home-garden&sprefix=%2Cgarden%2C751&sr=1-1-spons&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFGNEVPTTFPOTYzRjMmZW5jcnlwdGVkSWQ9QTA5NTU0ODExSFNGOFgwTUdBTEFDJmVuY3J5cHRlZEFkSWQ9QTAxMDE0NTcxSVNKOE9TV0U3QkU4JndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ&th=1)
