# VFO-DO RF Generator

This VFO-DO is a HF generator covering from few kHz to 100MHz. This project provide to any beginner in electronic or radio the necessary elements to build a source of stable frequency (precise at the Herz level due to the steering by a GPS)... and it is very simple to build.

It is coming from the initial idea from Gene Marcus W3PM/GM4YRE and published in an [article](http://www.arrl.org/files/file/QEX_Next_Issue/2015/Jul-Aug_2015/Marcus.pdf) of QEX.
This repository is an evolution of the work done by F6ITU who provided a [KiCad project](https://github.com/F6ITU/VFO-DO/) for this VFO-DO.

This project can be used as field equipements, where it is unthinkable to move a served oscillator (fragile and expensive). This is mainly a simple approach to drive a little SDR or replace the VFO of a traditional radio device.

The cost of this is around 30 euros. However, please take in account the phase noise of this type of generator cannot compete with a traditional VFO-DO

## Specific features

During the integration, few changes were applied in the initial code of the author:
  * usage of a I2C Crystal Display, it is freeing multiple pin on the Arduino
  * add a button to disable the GPS at start


## Intellectual property and licence

The intellectual property and the publishing rights are owned respectively by the author and the publishing society mentioned.

Permission is granted to use, copy, modify, and distribute this firmware and documentation for non-commercial purposes.

## External links

More informations on the oscillator module based on SiLabs Si5351 : 
[https://learn.adafruit.com/adafruit-si5351-clock-generator-breakout?view=all](https://learn.adafruit.com/adafruit-si5351-clock-generator-breakout?view=all)

Another source for this module 
[https://www.sv1afn.com/si5351a.html](https://www.sv1afn.com/si5351a.html)
Careful : this last module is not "pin compatible" with the previous one

Origin firmware from the author [http://www.knology.net/~gmarcus/Si5351/Si5351_vfo_v5.ino.zip](http://www.knology.net/~gmarcus/Si5351/Si5351_vfo_v5.ino.zip)

A WSPR emitter-receiver designed by the author and using the VFO-DO
[http://www.knology.net/~gmarcus/Si5351/Si5351A_WSPR_XCVR.pdf](http://www.knology.net/~gmarcus/Si5351/Si5351A_WSPR_XCVR.pdf)
