# Solar Panel Gazebo Build Instructions
## Table of contents
* [General info](#general-info)
* [Structure](#general-info)
* [Requirements](#Requirements)
* [PCB](#Requirements)
* [3D Print](#3D-Printing)
* [Soldering](#Soldering)
* [Unit Testing](#Unit-Testing)
* [Assembly](#Assembly)


## General info

This repository contains the implementation of a feasibility study for automatic readings of a solar panel. The project will heavily focus on measuring the current of the solar panel in Amps.

![PCB](image/20191121_154604.jpg)

## Structure 

1.  [Documentation](https://github.com/E-Hajj/Ahmad/tree/master/documentation) of the solar repository.  
2.  [Code](https://github.com/E-Hajj/Ahmad/tree/master/Code) contains the source code to interact with the solar panel and sensors.   
3.  [Electronics](https://github.com/E-Hajj/Ahmad/tree/master/Electronics) holds the contents of the PCB design,schematic and breadboard design.  
4.  [Raspberry pi Case](https://github.com/E-Hajj/Ahmad/tree/master/Raspberry%20pi%20case) contains the required build for the case.  
5.  [Images](https://github.com/E-Hajj/Ahmad/tree/master/image) of the project.


## Requirements

In this project you will need the required components to build this project.
* **Raspbery pi 3**   *$114*
  * Power supply 2A micro usb 
  * Ethernet cable and hdmi cable
  * Sd card for the software
  * If you dont own an raspberry pi 3 i would recommed buying one from [Amazon](https://www.amazon.ca/s?k=raspberry+pi+3&ref=nb_sb_noss_2) or [Sayal Electronics](https://secure.sayal.com/STORE2/index.php). 
* **Acs712 (current sensor)** *$13.99*
  * I would recoomend getting it from [Amazon](https://www.amazon.ca/COVVY-Current-Arduino-ACS712ELC-20A-Indicator/dp/B07TQ5M9MP/ref=sr_1_2_sspa?gclid=CjwKCAiArJjvBRACEiwA-Wiqq8mHMc1JzZT1BMymqLKF9jO-BrsuzXUFn7JWweUKXyQUBpmXN-AduxoC1csQAvD_BwE&hvadid=208460006382&hvdev=c&hvlocphy=9000826&hvnetw=g&hvpos=1t2&hvqmt=e&hvrand=8319947952554246574&hvtargid=kwd-298127854743&hydadcr=4516_9156520&keywords=acs712&qid=1575398013&sr=8-2-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFJWVVBN1pEVTJGQlomZW5jcnlwdGVkSWQ9QTA3MjUwNTgzM0tNWklaQzJVSjI0JmVuY3J5cHRlZEFkSWQ9QTA3MDIwMzUyMTZFUjhCNTRQRU1DJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==) becuase it comes in a pack of 2 incase one breaks or is faulty.  
* **Ads1115 (Analog to Digital Converter)** *$15.99*
   * [Amazon](https://www.amazon.ca/gp/product/B07GBYY54P/ref=ppx_yo_dt_b_asin_title_o04_s00?ie=UTF8&psc=1) would be a great option for this component, because the shipping is very quick for this.
* **Velleman Solar Cell 1V 200MA** *$7.95*
   * I would strongly recommend  [Sayal Electronics](https://secure.sayal.com/STORE2/index.php) sinces its cheaper and always in stock.
* **Wire Stripper/cutters** *$6.56*
  * If you already own them please make sure they work and are well sharpened.
   * [Amazon](https://www.amazon.ca/gp/product/B005HQR1YK/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1)
* **Safety eyewear** *$2.91*
  * Very important since you will be soldering and cutting and stripping wire 
  * Safety First
* **Soldering kit** *$29.99*
  * you will need some sort of soldering iron and solder to put together the PCB.
  *[Amazon](https://www.amazon.ca/gp/product/B07L3VNMKX/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&psc=1)
  
 ## PCB
 I would strongly recommend ordering your parts before you continue on to this part. Usually the parts will take 3 to 5 days due to shipping unless you have amazon prime then it should take a day or two. While waiting for the parts you should start working on the breadboard and PCB board. Creating the PCB will take time depending where you get it made so i would strongly recommed that you get it made right away as it would take time.
 
 1. Get the PCB board made 
 2. set up the breadboard for future testing of the sensors and componenets.
 
 
 ## Soldering 
 * If youve never soldered before i would recommend you to watch these videos on how to solder and safety as well. [Video](https://www.youtube.com/watch?v=BLfXXRfRIzY&list=PLQ32vZrF5U2lFOJTtZDytBWBYVLNp4RYz)
 1. When soldering the PCB make sure the 6 pin socket is at the bottom of the board.
 ![PCB](image/PCB_TopViewV1.jpg)
 2. Line up the 10 and 3 pin sockets to their corresponding connection as seens in this picture, Then solder.
 ![PCB](image/PCB_BottomViewV1.jpg)
 3. Once completed you must check if all pins are fully covered in solder an are stable. 
 4. To make sure all connections are fine and the board isnt damage you must use a digital multi meter and measure the resistance between each ports. The readings should be overload for the ports that shouldnt be connected. The corresponding pin to pin should show a little resisitance.
 
 
 ## 3D Printing
 
 
 ## Unit Testing 
 
 
 ## Assembly
 
 
 
 
 
   

 
   
   

