# Introduction

 This README describes all the steps needed to run the simple Aquaponics setup up and running for the School Project. This repository contains all the schematics and software needed to run everything, as well as a complete list of hardware resources needed with possible sources to provide them.

![Image of current system](https://dl.dropboxusercontent.com/u/4286043/NEBULAIR/SchoolProject/2015-07-28%2019.19.52%20HDR.jpg)

## Schematics overview

![Image of the Fritzing schematics](https://dl.dropboxusercontent.com/u/4286043/NEBULAIR/SchoolProject/Schematics1.png)


# Software needed

* Any operating system will do (Windows, GNU/Linux, Mac). 
* The hardware schematics have been created using __[Fritzing](http://fritzing.org)__ (FOSS).
* The software can be compiled and sent on the Arduino using the __[Arduino SDK](https://www.arduino.cc/en/Main/Software)__ (FOSS). 


# Hardware materials needed

To have a complete system, a minimal set of hardware is required. It is also possible to _upgrade_ the system to give it more capabilities later on.

All prices are including BTW

## Required hardware

### Electronics

* **Arduino**
 * An [Arduino Leonardo](https://www.arduino.cc/en/Main/ArduinoBoardLeonardo) will be used
 * Possible source - [Kiwi electronics](https://www.kiwi-electronics.nl/arduino-leonardo-met-headers-ATmega32u4?search=leonardo) - 21.95€

* **Cables BreadBoard Fem/Fem**
 * Used for connecting the board to the components
 * Possible source - [Amazon](http://www.amazon.fr/gp/product/B00ENSOHJ0?psc=1&redirect=true&ref_=ox_sc_act_title_2&smid=A1P3HNFSEHPC4K) - 1.49€

* **Cables BreadBoard Mal/Fem**
 * Used for connecting the board to the components
 * Possible source - [Amazon](http://www.amazon.fr/gp/product/B00ENSOGWS?psc=1&redirect=true&ref_=ox_sc_act_title_1&smid=A1P3HNFSEHPC4K) - 1.49€

* **Relay Board**
 * 4 relays board, to power the two pumps as well as the led strips. 5V trigger is low enough to use the Arduino.
 * Possible source - [Amazon](http://www.amazon.fr/gp/product/B00AZEVSQG?psc=1&redirect=true&ref_=ox_sc_act_title_3&smid=A3BIDE681BQEK5) - 3.03€

* **Water sensor**
 * Chosen device is a simple switch activated using the same principle as toilet flushes. 
 * Possible source - [Amazon](http://www.amazon.fr/gp/product/B009DYP2H0?psc=1&redirect=true&ref_=ox_sc_act_title_1&smid=AGJ2TI2R2YFK8) - 2.01€

* **Pump**
 * 12V pumps have proven to be powerful enough. Since we do not use a Bell Siphon system, we will need 2 pumps.
 * Possible source - [Amazon](http://www.amazon.de/gp/product/B00OIHLTME?psc=1&redirect=true&ref_=oh_aui_detailpage_o01_s00) - 7.59€ * 2 = 15.18€
 * A cheaper version - [Amazon](http://www.amazon.de/gp/product/B008OPKSC8?psc=1&redirect=true&ref_=oh_aui_detailpage_o00_s00) - 3.93€ * 2 = 7.86€

* **5V Power source for arduino**
 * A cable is needed to power the Arduino as well as program it. USB cables are perfect for this.
 * Possible source - [Amazon](http://www.amazon.de/dp/B00KPX9FB2?psc=1) - 6.49€

* **USB Charger**
 * Used to plug the Arduino to a power outlet in the long run.
 * Possible source - [Amazon](http://www.amazon.de/Stromadapter-Reiselader-Ladeger%C3%A4t-Reiseladeger%C3%A4t-Navigationsger%C3%A4t/dp/B00UHJA50O/ref=pd_sim_sbs_23_6?ie=UTF8&dpID=41GLJmSIGSL&dpSrc=sims&preST=_AC_UL160_SR160%2C160_&refRID=0CQKH2YM9DRPXWQKJ1RC) - 2.99€

* **12V power source**
 * Will be used to power the pumps as well as the LED strip
 * Possible source - [Amazon](http://www.amazon.de/Branded-power-supply-2-1mm-Supply/dp/B0056SV18Q/ref=sr_1_2?s=ce-de&ie=UTF8&qid=1448984892&sr=1-2&keywords=12v+power) - 8.16€


### General purpose, Consumables

On top of the purely electronic components, a number of additional elements are required to have a complete Aquaponics system runnning.

* **Tubing for the pumps**
 * Some tubing is needed for the pumps to flow in the buckets. A couple meters should be enough. The tubing should have the same diameter as the pump.
 * Possible source - [Amazon](http://www.amazon.de/Souked-50-Zoll--Aquarium-Luftschlauch-Luftpumpe/dp/B00SV4ALQ0/ref=sr_1_7?ie=UTF8&qid=1448987197&sr=8-7&keywords=aquarium+tubing ) - 4.38€

* **Plastic buckets**
 * Two plastic buckets are needed, one for the fish tank, and the other for the plants. The fish bucket should be bigger than the other one. 
 * The plan bucket should preferably be dark/black, to avoid growth of parasites and mold.
 * Possible source - [Ikea](http://www.ikea.com/nl/nl/catalog/products/30102974/) - 3.49€ * 2 = 6.98€


* **Fish**
 * For such a small system, a number of one to two fishes is advised. It is advised to take the cheapest, most resilient fish possible. Common Goldfish are usually a good choice to start with
 * Possible source - Any pet store - 1.50€ * 2 = 3€

* **Fish food**
 * Possible source - Any pet store - 2€

* **Ph/Nitrates strips**
 * Will be used to check that the environment is under control, and that the nitrates are being delivered to the plants. 
 * Possible source - Any pet store - 8€

* **Ceramic balls**
 * Will be used to lay the plants in, as well as allow for bacteria growth. Avoid soil! 
 * Possible source - Gardening store - 4€

* **Plants**
 * Resistant plants are advised for a first system. Small trees and spices are usually good choices (Mint, Paprika, Thym, ...)
 * Possible source - Gardening store - 8€

## Possible upgrades

Those elements are not required for the basic system, but can be used to improve the automation and or go further in the project.

* **LED Strip**
 * The LED Strip is used to improve the growth rate of plants. It uses special wavelength. 2m is enough for one system, and the strip can be cut as desired. We use 12V strips to match the pumps voltage
 * Natural light can be enough but for winter times, it is advised to use grow lights as it allows to control the day/night cycles.
 * Possible source - [Amazon](http://www.amazon.de/SOLMORE-Light-Strip-Pflanzenlichter-Selbstklebend/dp/B00ZI4P0A8/ref=sr_1_cc_2?s=aps&ie=UTF8&qid=1448983389&sr=1-2-catcorr&keywords=grow+light+strip) - 12.99€

* **Ultra Sound Sensor**
 * The Ultra Sound sensor can be used as a replacement for the water level sensor. It allows for a more precise control of the water level, and is also less subject for mechanical failures. 
 * Possible source - [Amazon](http://www.amazon.fr/gp/product/B00BIZQWYE?dpID=41dsw83-RXL&dpSrc=sims&preST=_SL500_SR135%2C135_&refRID=50345E784KBQDMPTW3C2&ref_=pd_rhf_sc_s_cp_5) - 1.46€

* **pH Probe**
 * For a more complete system, a pH probe can be used to measure pH constantly.
 * Possible source - [Amazon](http://www.amazon.de/Gain-Express-PH-025RE_UK_FBA-Digital-pH-Meter-Monitor-Elektroden-Sonde/dp/B0111WRS7I/ref=sr_1_3?ie=UTF8&qid=1448987775&sr=8-3&keywords=ph+probe) - 40.51€  

## Total Prices

This part simply aims at summarizing the numbers listed above to give an idea of the price of a simple system, as well as an upgraded system.

Those prices do not include shipping costs, which will vary depending on the number of systems to build.

* Simple system, no upgrade included : 86€ (per system)
* Upgraded system : 100€ (per system)
* Fully upgraded system (including probe) : 145€ (per system)

# Existing system


Some photos and videos about the current system. The system is slightly different, as it uses a Bell Siphon and overflow to drain water back to the fish pawn instead of pumping it. 

## Short video of the principle
[![Short video of the first system](http://img.youtube.com/vi/gHlj5Vq7Mjk/0.jpg)](https://youtu.be/gHlj5Vq7Mjk)

## Some images of the system, day and night cycles

### First generation Arduino circuit
![Image of the first generation Arduino circuit](https://dl.dropboxusercontent.com/u/4286043/NEBULAIR/SchoolProject/2015-11-20%2016.34.16.jpg)

### System during day and night
![System during day](https://dl.dropboxusercontent.com/u/4286043/NEBULAIR/SchoolProject/2015-11-01%2020.30.21.jpg)
![System during night](https://dl.dropboxusercontent.com/u/4286043/NEBULAIR/SchoolProject/2015-10-26%2021.31.42.jpg)