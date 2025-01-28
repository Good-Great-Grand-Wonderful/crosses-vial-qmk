# Crosses by Good Great Grand Wonderful

![crosses](imgur.com image replace me!)

Reduce painful ulnar deviation by using separate key modules at shoulder width and rotate them to reduce painful ulnar deviation. And leverage the integrated 26.5-degree tenting mechanism to reduce forearm pronation.

* Keyboard Maintainer: [Good Great Grand Wonderful LLC](https://github.com/Good-Great-Grand-Wonderful)
* Hardware Supported: 
 * Matrix configurations in: 3x5, 3x6, 4x6 boards with a three key thumb cluster.
 * Trackballs!
 * OLED Displays
 * Any SPI / I2C breakout using a 6P JST SH for SPI and a 2.54 mm breakout for I2C.
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    qmk compile -kb gggw/crosses/<LAYOUT>/<REV> -km default

Flashing example for this keyboard:

    qmk flash -kb gggw/crosses/<LAYOUT>/<REV> -km default

NOTE: If your thumb cluster is _less than_ Rev11 then use Rev1 firmware, otherwise use Rev2


## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Double-tap the reset button on the RP2040
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
