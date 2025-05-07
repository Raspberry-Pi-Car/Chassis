# PiCar Chassis
A 3D printable chassis for a 2 wheel drive Raspberry Pi controlled car designed for personal and academic use.

## OnShape Model

You can find the full model in OnShape: [PiCarChassis1](https://cad.onshape.com/documents/7e4770bd0883ef791fccfce2/w/b0bda0ce8d7720ebb6f6aa24/e/0d48a400d6beaccd7df07606?renderMode=0&uiState=681bd0953f563009a6b3afbd) (once the link is pressed you may need to refresh)

## 3D printing

For those who do not want to customize their car in any way, the STL files are available in **V1-STLs**. These STL files have no fun names embedded in the print and are designed to be as simple as possible. Please note, the parts title ***Print2*** will need two of these item printed to be able to completely assemble the car. These parts are the _Front Shaft Spacer_, _Front Shaft_, _N20 Sleeve_, and _Rear Spacer_. All other items in the print only need a single copy per car. Happy printing!!

### Custom text printing

Tutorial on how to customize the text and add your own text coming soon.

## Required Hardware

Below is a list of hardware that is used to assemble the design and links to get them from different suppliers.

| Part and Model | Quantity | Purchase Link 1 | Purchase Link 2 | Purchase Link 3 |
| -------- | -------- | -------- | -------- | -------- |
| N20 Motors (6V 300 to 400 RPM) | 2 | [AliExpress](https://www.aliexpress.us/item/2251832822008333.html?spm=a2g0o.order_list.order_list_main.35.55511802F0cztx&gatewayAdapt=glo2usa) | [Alibaba](https://www.alibaba.com/product-detail/Bringsmart-JGA12-N20B-All-Metal-Gears_1600893524712.html?spm=a2700.galleryofferlist.normal_offer.d_title.78d813a0OGqrv8) | [Amazon](https://a.co/d/13G6bXz) |
| MF148ZZ Bearing (8x14x4mm) | 10 | [AliExpress](https://www.aliexpress.us/item/3256805156166045.html?spm=a2g0o.order_list.order_list_main.29.55511802F0cztx&gatewayAdapt=glo2usa)  | [Alibaba](https://www.alibaba.com/product-detail/MF148-ZZ-MF148ZZ-MF148-2Z-Mini_1601282596612.html?spm=a2700.galleryofferlist.normal_offer.d_title.764513a0qrBIF2) | [McMaster-Carr](https://www.mcmaster.com/7804K146/) |
| 12mm Hex to 8mm Wheel Coupling | 4 | [AliExpress](https://www.aliexpress.us/item/3256806226849189.html?spm=a2g0o.order_list.order_list_main.23.55511802F0cztx&gatewayAdapt=glo2usa) | [Alibaba](https://www.alibaba.com/product-detail/Hexagon-Coupling-12mm-Tire-Connector-Coupling_1601266273126.html?spm=a2700.galleryofferlist.normal_offer.d_title.3f5a13a0jycNtH) | [Amazon](https://a.co/d/eVg6nnu)
| PiCamera (Any version) | 1 | 
| Ultrasonic Sensor | 1 | 

The screws and other hardware can be bought as individual kits from Amazon/AliExpress/Alibaba or as individual parts at McMaster-Carr or you local hardware store. 

| Hardware Size | Type | Quantity | Purpose | Note |
| -------- | -------- | -------- | -------- | --------|
| M1.6 x 8mm Machine Screws | Pan head or Countersunk | 8 | Camera and Ultrasonic Sensor | Working to remove this requirement |
| M2 x 10/12mm Machine Screws | Pan head or Countersunk | 7 | Servos and Head Stabilization
| M2 Nuts | | 7 | With M2 Screws |
| M3 x 8mm Machine Screws | Pan head or Countersunk | 10 | Chassis and Head |
| M3 x 8mm Machine Screws | Countersunk | 2 | Battery Holder | 
| M3 Nuts | | 2 | Battery Holder |
| M3 Heat Insert | One Sided | 10 | Chassis and Head |
| M4 x 8mm Machine Screw | Pan Head | 4 | Wheel Coupling |
| | | | |
| M1.7 Self-tapping Screws | Comes with servos | 3 | For Servo Arms | 


## How to assemble

Assembly tutorial coming soon.


## Purpose 
### Motivation
After taking ESE 205, _Introduction to Engineering Design_ course at Washington University in St. Louis, and then becoming an _Assistant Instructor_ for the course and needing to repair the commercial alternative. The brand will not be stated, but the vehicles were extremely time-consuming to construct and more importantly to maintain in a class setting. The servos were continuously getting stripped and needing continuous replacement. The was due to the weight of the items being supported, the nature of first year students, and the design being made of laser cut polycarbonate. This meant that the full car is held together with a lot of screws and hardware than what is truly necessary. 

### Goal
The goal was to design a simple and complete design for use in an introductory level hardware interfacing class. The goal of the class was to use onboard sensors to complete specified tasks as set by the instructor of the course. The chassis was to be design to be easy to assemble, easy to print, and, most importantly, easy to maintain. The aim was to make the servos easily replaceable while stabilizing the head and removing steering slop, which were both problems on the original design. 

### Overall Model

![PiCar Model](https://github.com/user-attachments/assets/ddfa6e94-6176-41c8-adce-63950f62f545)

### Current Model

The current model has only been tested with PLA and works great, once the model goes public, it can be clones and custom text emedded in the print to allow for cutoming naming, or for a class, numbering. 
