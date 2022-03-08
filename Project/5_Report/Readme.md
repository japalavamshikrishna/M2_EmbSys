# INTRODUCTION TO IRRIGATION SYSTEM
Freshwater is needed for crop and energy production, industrial fabrication as well as human and ecosystem needs. According to AQUASTAT database (AQUASTAT, 2016), 69% of the total extracted freshwater is used by agriculture sector, whereas 19% is used by industrial sector and the rest in used by domestic segment. Therefore, water can be considered as a critical need in agriculture sector for future global food security However, continued increase in demand for water by domestic and industrial sectors and greater concerns for environmental quality have create a challenge to every country to reduce the farm water consumption and sustain the fresh food requirement (Flörke et al., 2013). Consequently, there is an urgent need to create strategies based on science and technology for sustainable use of water. Industrialist and researchers are working to build efficient and economic automatic systems to control water usage in order to reduces much of the wastage.

Irrigation is an artificial application of watering the land for agricultural production. The requirement of water to the soil depends on soil properties such as soil moisture and soil temperature. Effective irrigation can influence the entire growth process and automation in irrigation system using modern technology can be used to provide better irrigation management. In general, most of the irrigation systems are manually operated. These traditional techniques can be replaced with automated techniqus of irrigation in order to use
water efficiently and effectively. Conventionally, farmers will present in their fields to do irrigation process. Nevertheless, nowadays farmers need to manage their agricultural activity along with other occupations. A sensor based automated irrigation system provides promising solution to farmers where the presence of a farmer in field is not compulsory during irrigation process
.
Arduino is a flexible programmable hardware platform and designed to control the circuit logically. Central to the Arduino interface board is the main component of an integrated circuit chip that can be programmed using C++ language. This microcontroller is an AVR type, which produced by Atmel firm. The device can read the input, process the program, and produce many outputs based on project requirements. In this chapter, the development of an automated irrigation system based on Arduino microcontrollers is presented. In this system, a soil moisture sensor is used to detect and check the soil humidity of the plant. Based on the soil moisture level from the soil, the system will let the water pump to automatic water the plant when it is too dry and turn off the water pump when the soil of the plant is wet.
AUTOMATED WATERING TECHNIQUES
At the previous works, considering to the automated watering techniques, it can be found that the Arduino based sensors have been utilized for the plant watering system (Devika et al., 2014) and automated irrigation systems (Agrawal & Singhal, 2015; Kumar Sahu & Behera, 2015; Singh & Saikia, 2017).
An Arduino Based Automatic Plant Watering System is proposed in (Devika et al., 2014) where the authors developed the Arduino microcontroller used to control two functional components which are the moisture sensors and the motor/water pump to automatically water the plant. The moisture sensor’s function is to sense the level of moisture in the soil whereas the water pump supplies water to the plants.
In (Agrawal & Singhal, 2015), a smart drip irrigation system using Raspberry Pi and Arduino is proposed for home automation
An Automated Irrigation System Using Arduino Microcontroller
system. A drip irrigation system makes the efficient use of water where the water is slowly dripped to the roots of the plants through narrow tubes and valves. The water flow from the system can be remotely controlled via email.
AN AUTOMATED IRRIGATION HARDWARE IMPLEMENTATION
This project design includes several functional blocks as shown Figure 1 namely: acquisition block, microcontroller block, automatic functional block and monitoring block.
• Acquisition block
This block consists of one soil moisture sensor which takes the data from the soil. It depends on the moisture level of the soil whether to send high or low voltage to the microcontroller to show that it is wet or dry. When the soil is wet, it will send the low output voltage, whereas when it is dry, it will send the high output voltage. This sensor is directly connected to Arduino microcontroller.
• Microcontroller block
In this block, Arduino Uno is the microcontroller which is the core hardware of this project. It receives the input from the soil moisture sensor and processes the input based on the requirement coded in the microcontroller.
• Monitoring block
This block includes an LCD display, which is used to monitor the level of soil moisture by showing the percentage of the moisture on the screen. When the soil is dry the percentage will be lower and vice versa. In addition, it also shows the pump status which is on or off, in which users will know the current pump status.
5
Internet of Things: Usage and Application
Figure 1.1: Functional Block diagram
• Automatic Functional block
This block includes the automated watering function of the system. The automated function consists of two main controlling hardware, which is relay module and DC watering pump. The relay is an automatic electric switch that uses an electromagnet to move the switch from OFF to ON or vice versa. The switch controls the electric signal that pass through the water pump. When the moisture level is below the threshold level, Arduino sends a signal to the relay module to automatically open the path for the electric to pass through the water pump to water the plant. After the system detects the sufficient level of the water in the soil, the relay will close the path for electric and thus the water pump will be stop immediately pumping the water.
6
An Automated Irrigation System Using Arduino Microcontroller
All the hardware will be assembled to Arduino, which is the microcontroller that use to control all the hardware that attached to it and let it function. Figure 1.2 shows the details of Arduino pins and their connection to the corresponding hardware, which are based on the Table 1.1.
Figure 1.2: Details of Arduino Pin for Hardware Connection
Table 1.1: Arduino pins and their corresponding hardware
Hardware
Pin
Soil moisture sensor
A0, Vin, GND
LCD screen
A4, A5, AREF, GND
Relay module
5V, GND, 2
Figure 1.3 shows the complete hardware setup of the proposed system which include the Arduino board and all the necessary attached hardware. This project is considered a complete prototype where it can be used and function for the daily life. From Figure 1.3, it can be seen that the Arduino is the center of this system which connects all the required hardware. The soil moisture sensor measures the level of moisture from the soil, and it is transferred to the Arduino board to process and make decision.
SOIL MOISTURE SENSOR TEST
This section describes the test strategy that is used for this project. The test is used to determine whether the hardware and software will be test early to make sure that it is functioning according to the requirement
Results:
Test
Soil Moisture Sensor
Test Purpose
To test the sensor values and its functionality.
Test Environment
A glass of water and Arduino IDE.
Expected Step
1. Open the serial monitor in Arduino IDE and see the sensor value for the dry condition.
2. Open the serial monitor in Arduino IDE and see the sensor value for the dry condition.
3. Immersed the soil moisture sensor into a glass of water and see for the wet condition in the serial monitor in Arduino
IDE too.
Expected Result
The soil moisture sensor is light up in the controller when it is switched on, and it can show the lower and upper
boundaries of the sensor value in dry and wet conditions.
CLOSURE
The main purpose of this chapter is to propose an automated irrigation system that water the plant without any human control. The automated irrigation system implemented is found to be feasible and cost effective for optimizing water resources for agricultural production. Besides the automated irrigation system, the proposed system also provides the monitoring function where users are able to check the soil moisture based on the reading on the LCD display. The proposed system has been designed and tested to function automatically. For future works, the automated irrigation system can be configured to measure the moisture level (water content) according to the moisture requirement of the different plants.
References
Books and Journals
Agrawal, N., & Singhal, S. (2015). Smart drip irrigation system using raspberry pi and arduino. International Conference on Computing, Communication & Automation, 928–932. http://doi.org/10.1109/CCAA.2015.7148526
