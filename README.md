# Interfacing Capacitive Fingerprint Sensor with Arduino UNO

Video tutorial : [https://youtu.be/ULMnPckZp1M](https://www.youtube.com/watch?v=Y87V0O1yMCk&list=LL&index=1)

![alt text](https://github.com/akarsh98/DFRobot-FingerPrint-Sensor/blob/main/Capacitive%20Fingerprint%20Sensor/1.JPG)

In this project, we are going to interface a Capacitive Fingerprint Sensor from DFRobot with the Arduino UNO. It is a sleek and compact fingerprint sensor which is different from the previously available more bulky and comparitively less accurate fingerprint sensor. It is a 6 pin device which is loaded with the ID809 high performance  processor and semiconductor fingerprint sensor as the core, the sensor adopts built-in IDfinger6.0 algorithm, which can complete all fingerprint identification work independently. It supports UART and can easily realize functions like fingerprint registration, fingerprint deletion, etc.

![alt text](https://github.com/akarsh98/DFRobot-FingerPrint-Sensor/blob/main/Capacitive%20Fingerprint%20Sensor/2.JPG)

So today, we are going to interface this sensor with the Arduino and after that we will code it in such a manner that will make it capable of performing three tasks which are: Fingerprint Scanning and Testing, Adding a new Fingerprint and after that deletion of any added fingerprint. We will use the Arduino IDE Serial monitor to check that which operation is going on and the device is currently in which status.There is another way to connect this scanner i.e by using the USP to Serial converter and the NOEM Host Software but we will not be using that today.

![alt text](https://github.com/akarsh98/DFRobot-FingerPrint-Sensor/blob/main/Capacitive%20Fingerprint%20Sensor/7.JPG)

![alt text](https://github.com/akarsh98/LoRa-Remote-Controller/blob/master/LoRa%20Remote/Capture.PNG)
PCBGOGO, established in 2015, offers turnkey PCB assembly services, including [PCB manufacturing](https://www.pcbgogo.com/), PCB assembly, components sourcing, functional testing, and IC programing. 
Its manufacturing bases are equipped with the most advanced production equipment such as YAMAHA pick and place machine, Reflow oven, Wave soldering Machine, X-RAY, AOI testing machine; and the most professional technical personnel.
Though it’s only five years old, their factories have the experience in PCB industry for over 10 years in Chinese markets. It is a leading specialist in surface-mount, thru-hole and mixed technology PCB assembly and electronic manufacturing services as well as [turnkey PCB assembly](https://www.pcbgogo.com/pcb-assembly.html). 
PCBGOGO provides the order service from prototype to mass production, join them now.
