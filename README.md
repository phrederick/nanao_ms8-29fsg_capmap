# NANAO MS8-29FSG - Recap Reference

<!-- TOC -->

- [Overview](#overview)
- [Who this page is for](#who-this-page-is-for)
- [Reference Map](#reference-map)
- [Capacitor Values & Notes](#capacitor-values--notes)

<!-- /TOC -->

## Overview
The purpose of this page is to serve as a quick and easy reference for a recap of your NANAO MS8-29FSG chassis. In the context of this page, the term "recap" refers to the replacement of electrolytic capacitors which are a common failure point for electronics.

Please note that you should not assume that a recap is a magical "fix-all solution" for issues you may be experiencing with your arcade machine. Although completely optional, an ESR meter is an invaluable tool for troubleshooting electrolytic capacitors **both in and out of circuit**, and they can save you a LOT of time if you know how to use one. I encourage you to do your own research about how they work and where to get them. They are a relatively cheap tool and I can't recommend them enough. A couple of examples are:

* 'EVB' brand ESR meter: https://www.evbesrmeter.pt/
* 'PEAK' brand Atlas ESR70 meter: https://www.peakelec.co.uk/acatalog/esr70-capacitor-esr-meter.html

## Who this page is for
There are capacitor kits for the NANAO MS8-29FSG chassis available online, but if you prefer to purchase your own caps for whatever reason (e.g. it's cheaper, or you prefer specific brands), this page may be useful to you. The assumptions are that you:
* Know what a NANAO MS8-29FSG chassis is (and I suppose you do if you're reading this page)
* Know how to safely dismantle and discharge the CRT + chassis in your cabinet
* Have some basic knowledge of what an electrolytic capacitor is and how to observe the correct polarity when installing them
* Have the necessary soldering skills and equipment, such as:    
    * Soldering iron
    * Side cutters
    * Desoldering tools
    * ESR meter (optional)    

## Reference Map
<img src="https://i.imgur.com/zo7C84B.png">

## Capacitor Values & Notes
Reference|Capacitance Value|Voltage Rating|Location & Notes|Digi-Key Example
---------|-----------------|--------------|----------------|---------------|
C401 | 1 uF | 50 V | **main board** | [493-5042-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPJ1H010MDD1TD/3129379)
C422 | 470 uF | 16 V | **main board** | [1189-1146-ND](https://www.digikey.com.au/en/products/detail/rubycon/16YXJ470M8X11-5/3134104)
C431 | 470 uF | 35 V | **main board** | [1189-3745-1-ND](https://www.digikey.com.au/en/products/detail/rubycon/35YXG470MEFCT810X20/6599209)
C432 | 100 uF | 35 V | **main board** | [1189-3732-1-ND](https://www.digikey.com.au/en/products/detail/rubycon/35ML100MEFCT78X7-5/6599198)
C438 | 470 uF | 25 V | **main board** | [1189-1735-ND](https://www.digikey.com.au/en/products/detail/rubycon/25YXG470MEFC10X16/3563695)
C443 | 1 uF | 50 V | **main board** | [493-5042-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPJ1H010MDD1TD/3129379)
C446 | 33 uF | 16 V | **main board**<br>* Non-polarised. | [P1165-ND](https://www.digikey.com.au/en/products/detail/panasonic-electronic-components/ECE-A1CN330U/227606)
C447 | 47 uF | 16 V | **main board** | [493-11386-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPW1C470MDD1TD/4319934)
C448 | 100 uF | 35 V | **main board** | [1189-3732-1-ND](https://www.digikey.com.au/en/products/detail/rubycon/35ML100MEFCT78X7-5/6599198)
C449 | 33 uF | 16 V | **main board** | [493-5358-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPS1C330MDD1TD/3129695)
C501 | 1 uF | 50 V | **main board** | [493-5042-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPJ1H010MDD1TD/3129379)
C521 | 33 uF | 16 V | **main board**<br>* This is an 'OS-CON' low ESR polymer capacitor. | [P16309-ND](https://www.digikey.com.au/en/products/detail/panasonic-electronic-components/20SEP33M/4204146)
C560 | 0.47 uF | 160 V | **main board** | [493-5389-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPS2CR47MED1TD/3129726)
C561 | 1 uF | 200 V | **main board** | [493-5390-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPS2D010MED1TD/3129727)
C562 | 4.7 uF | 25 V | **main board**<br>* Digi-Key example is 35V rating. | [493-11325-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPS1V4R7MDD1TD/4319758)
C565 | 4.7 uF | 100 V | **main board** | [493-17067-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPJ2A4R7MED/2599377)
C566 | 4.7 uF | 100 V | **main board**<br>* Unmarked on PCB but shares location with R566.<br>* Negative lead to the left as per [Reference Map](#reference-map) image. | [493-17067-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPJ2A4R7MED/2599377)
C570 | 22 uF | 250 V | **main board** | [P13640-ND](https://www.digikey.com.au/en/products/detail/panasonic-electronic-components/EEU-EE2E220/1245969)
C572 | 47 uF | 16 V | **main board** | [493-11386-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPW1C470MDD1TD/4319934)
C573 | 470 uF | 16 V | **main board** | [1189-1146-ND](https://www.digikey.com.au/en/products/detail/rubycon/16YXJ470M8X11-5/3134104)
C574 | 33 uF | 35 V | **main board** | [493-14729-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/ULD1V330MDD1TD/6161737)
C576 | 470 uF | 16 V | **main board** | [1189-1146-ND](https://www.digikey.com.au/en/products/detail/rubycon/16YXJ470M8X11-5/3134104)
C577 | 1 uF | 100 V | **main board** | [493-11582-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPM2A010MDD1TD/4319668)
C580 | 1 uF | 50 V | **main board** | [493-5042-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPJ1H010MDD1TD/3129379)
C905 | 1000 uF | 180 V | **main board**<br>* Filter cap - unlikely to need replacing. | Examples [here](https://www.digikey.com.au/en/products/filter/aluminum-electrolytic-capacitors/58?s=N4IgjCBcoEwAwBYCcVQGMoDMCGAbAzgKYA0IA9lANrhy0AEArQGIgC6pADgC5QgCqAOwCWXAPKYAsoWz4ArgCdCIAL6l4AdhTQQGSDgIlyVcAA44dAGptOPSP2FjJ0uYpWkAtDFQ6oXebMMKSGoAVjZlCKA). Remember to check lead spacing.
C906 | 100 uF | 160 V | **main board** | [P13507-ND](https://www.digikey.com.au/en/products/detail/panasonic-electronic-components/EEU-ED2C101S/1086732)
C908 | 47 uF | 16 V | **main board** | [493-11386-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPW1C470MDD1TD/4319934)
C909 | 100 uF | 160 V | **main board** | [P13507-ND](https://www.digikey.com.au/en/products/detail/panasonic-electronic-components/EEU-ED2C101S/1086732)
C910 | 220 uF | 50 V | **main board** | [P122401-ND](https://www.digikey.com.au/en/products/detail/panasonic-electronic-components/EEU-FS1H221L/7381267)
C911 | 220 uF | 25 V | **main board** | [1189-3720-1-ND](https://www.digikey.com.au/en/products/detail/rubycon/25YXF220MEFCT78X11-5/6599189)
C913 | 220 uF | 16 V | **main board** | [1189-2190-ND](https://www.digikey.com.au/en/products/detail/rubycon/16YXF220MEFC8X11-5/3563334)
C1 | 1 uF | 50 V | **card 1** | [493-5042-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPJ1H010MDD1TD/3129379)
C2 | 1 uF | 50 V | **card 1** | [493-5042-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPJ1H010MDD1TD/3129379)
C3 | 1 uF | 50 V | **card 1** | [493-5042-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPJ1H010MDD1TD/3129379)
C4 | 1 uF | 50 V | **card 1** | [493-5042-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPJ1H010MDD1TD/3129379)
C420 | 1 uF | 50 V | **card 2** | [493-5042-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPJ1H010MDD1TD/3129379)
C532 | 1 uF | 50 V | **card 2** | [493-5042-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPJ1H010MDD1TD/3129379)
C332 | 1 uF | 50 V | **neck board** | [493-5042-1-ND](https://www.digikey.com.au/en/products/detail/nichicon/UPJ1H010MDD1TD/3129379)