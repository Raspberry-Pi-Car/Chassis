# PiCar Chassis
A 3D printable chassis for a 2-wheel drive Raspberry Pi controlled car designed for personal and academic use.

## OnShape Model

A revised model (01/06/2025) can be found at: [PiCarChassis2](https://cad.onshape.com/documents/606afa32c4ddef82647d70d7/w/6173d1c845c871eaac10e766/e/4a1e5e404db76d444ffd6e8d?renderMode=0&uiState=683caa3380ccf723f2ae1f88)


## 3D printing

For those who do not want to customize their car in any way, the STL files are available in **V1-STLs**. These STL files have no fun names embedded in the print and are designed to be as simple as possible. Please note, the parts title ***Print2*** will need two of these item printed to be able to completely assemble the car. These parts are the _Front Shaft Spacer_, _Front Shaft_, _N20 Sleeve_, and _Rear Spacer_. All other items in the print only need a single copy per car. 

For **V2-STLs**, the number at the end, ie. the `#` in `NAME-#.stl`, is the number of parts that need to be printed.

Happy printing!!

### Custom text printing

The text on the car can be edited by opening the _Chassis_ tab and scrolling down to the folder _TEXT (2)_ and editing the two sketches that are inside (`TEXT TOP` & `TEXT BOTTOM`). Once in the sketch, right-click on the text itself and you can modify the name and number. You can remove the text by right-clicking on the extrusions (`Extrude Text Top` & `Extrude Text Bottom`) and selecting _suppress_.

Video tutorial will be added soon<sup>TM</sup>.

## Required Hardware

Below is a list of hardware that is used to assemble the design and links to get them from different suppliers.

| Part and Model | Quantity | Purchase Link 1 | Purchase Link 2 | Purchase Link 3 |
| -------- | -------- | -------- | -------- | -------- |
| N20 Motors (6V 300 to 400 RPM recommended) | 2 | [AliExpress](https://www.aliexpress.us) | [Alibaba](https://www.alibaba.com) | [Amazon](https://a.co/d/13G6bXz) |
| MF148ZZ Bearing (8x14x4mm) | 10 | [AliExpress](https://www.aliexpress.us)  | [Alibaba](https://www.alibaba.com) |
| 12mm Hex to 8mm Wheel Coupling | 4 | [AliExpress](https://www.aliexpress.us) | [Alibaba](https://www.alibaba.com)
| PiCamera (v1 fit tested, v2 untested) | 1 | 
| Ultrasonic Sensor | 1 | 

The screws and other hardware can be bought as individual kits from Amazon/AliExpress/Alibaba or as individual parts at McMaster-Carr or you local hardware store. 

| Hardware Size | Type | Quantity | Purpose | Note |
| -------- | -------- | -------- | -------- | --------|
| M1.6 x 8mm Machine Screws (Can be plastic) | Pan head or Countersunk | 8 | Camera and Ultrasonic Sensor | Working to remove this requirement |
| M2 x 10/12mm Machine Screws | Pan head or Countersunk | 6 | Servos mounting |
| M2 Nuts | | 6 | With M2 Screws |
| M3 x 10mm Machine Screws | Pan head or Countersunk | 9 | Chassis and Head Stabilization |
| M3 x 8 or 10mm Machine Screws | Countersunk | 2 | Battery Holder | 
| M3 Nuts | | 3 | Battery Holder and Head Stabilization |
| M3 Heat Insert | One Sided | 8 | Chassis |
| M4 x 8mm Machine Screw | Pan Head | 4 | Wheel Coupling |
| | | | |
| M1.7 Self-tapping Screws | Comes with servos | 4-5 | For Servo Arms | 


## How to assemble

Assembly tutorial Coming Soon<sup>TM</sup>.


## Purpose 
### Motivation
After taking ESE 205, _Introduction to Engineering Design_ course at Washington University in St. Louis, and later becoming an _Assistant Instructor_ for the course, I needed to repair the commercial alternative. The brand will not be stated, but the vehicles were extremely time-consuming to construct and more importantly to maintain in a class setting. The servos were continuously getting stripped and needing continuous replacement. The was due to the weight of the items being supported, the nature of first year students, and the design being made of laser cut polycarbonate. This meant that the full car is held together with a lot of screws and hardware Which can be avoided if 3D printing is used. 

Since the big boom of 3D printing, 3D printing is more available than ever, it made sense to try and remake the cars using 3D printing, allowing for easier maintenance, since if a part broke, it could easily be reprinted. If the requirements for the class change, the model can be updated and reprinted for ~$5. The goal was to use less hardware as well, dropping the screw requirement from approximately 50 down to approximately 20 and removing the need for M3 standoffs to connect two laser cut panels together.  

### Goal
The goal was to design a simple and complete design for use in an introductory level hardware interfacing class. The goal of the class was to use onboard sensors to complete specified tasks as set by the instructor of the course. The chassis was to be design to be easy to assemble, easy to print, and, most importantly, easy to maintain. The aim was to make the servos easily replaceable while stabilizing the head and removing steering slop, which were both problems on the original design. 

### Overall Model

![PiCar Model](https://github.com/user-attachments/assets/ddfa6e94-6176-41c8-adce-63950f62f545)

### Current Model

The current model is made with OnShape, the goal is to soon release another model that uses Fusion360 to allow for more choices for individuals looking to customizing their own car. 
