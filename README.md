# IoTrash(IoT-Based-Garbage-Monitoring-Service)

* [Introduction](#introduction)
* [Prerequisites](#prerequisites)
* [How to install](#how-to-install)
* [Preview](#Preview)

## Introduction
![Introduction](https://user-images.githubusercontent.com/24422677/131486502-76625a91-1736-4306-ae79-f8bfc00ff02c.jpg)

  The janitor who manages trash bins in many buildings has the difficulty of going around and checking the bins every time. So we suggest a solution of trash bins monitoring system. This system Contributes easy manages for janitor. We used some platforms that 'Spring framework for server', 'ARTIK 053 for hardware', 'Android Studio for smartphone'. 'Spring Framework' is a server development tools for Java. This project was done a 'Spring Framework' applied 'MVC patterns(JSP+Spring Framework, RESTful API). The server was communicated hardware of 'ARTIK 530' and smartphone of 'Android'. 'ARTIK053' is a platform supported 'ARTIK' of SAMSUNG. Support for that platform is now deprecated(~2018). This platform was make up 'C' language in Tizen RT. Hardware is attached trash bins. Hardware check a trash bins and request a server add the checked values real time. So server saved the reqeusted values and show this values through web pages and Android smartphone.
  
  
Some features of this project
* Values of trash bins display
* Values of trash bins check on realtime
* Security
* Values of trash bins record on realtime
* Periodically collection of data

![Features](https://user-images.githubusercontent.com/24422677/131491540-2df73f98-020d-4077-9dab-12f3eb02696d.png)
 
 
 Server databases is mariadb. This is ERD.
 ![ERD](https://user-images.githubusercontent.com/24422677/131491932-f232dd08-8a89-47c4-a9eb-511bd33bf1fc.png)
 
 
## Prerequisites
 1. You must have platform of 'ARTIK 053'. The 'SAMSUNG' was supported this platform. But support for that platform is now deprecated(~2018).
 2. Android Version is so low. It may not be supported in the current version.
 3. 'Spring Framework' is no 'Spring boot'.
 
## How to install
It is recommended for reference only. To install this project, do the following steps:
1. Prepare Platform of 'ARTIK053', Three color LED, Resist, Infrared sensor.
2. Add the code ''
 
## Preview
* Introduction video  : https://youtu.be/JGBrlb_sIm4
* Demonstration video : https://youtu.be/cF5nNAuwbno
