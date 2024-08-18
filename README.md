


# maker100-curriculum
maker100-robotics-machine-learning-IoT-communication-curriculum

## Problem: 
How can a School or University start a general Robotics course for all students when there are only a few educators skilled in Robotics and Machine Learning?

## Solution:

1. **A versatile, passionate educator**
2. **A computer lab** equipped with a few 3D printers
3. **Strong IT support** to manage software installations and updates
4. **An initial robotics lab** stocked with sensors, actuators, IoT modules, basic electronics (wires, breadboards, batteries, resistors, capacitors, etc.), soldering equipment, etc. ~ $2,000 - $10,000 
5. **A budget for consumables** and a set of new microcontrollers every few years. ~ $500 - $3,000
6. **A well-crafted, asynchronous, student-friendly Robotics, Machine Learning, and IoT curriculum**

## Concept:   
Robotics is fundamentally about solving technology problems. Students must actively engage in overcoming these challenges. Once all the technology problems are solved and there are no more challenges to face, can it truly be called a Robotics Curriculum? This curriculum with new microcontrollers every few years solves that issue and makes solving the technology problems a constant process.

## Why:
Large Language Models (LLMs) like ChatGPT, coPilot, BingChat, and LLAMA-v2 are revolutionizing various aspects of life, including education. However, the complexity of AI and the datasets these models are trained on makes them difficult to teach to the general public. TinyML, using affordable microcontrollers like Arduinos, offers students a hands-on way to grasp AI concepts. It allows them to train a simplified version of Machine Learning using small, manageable datasets—such as images they create themselves.

This approach is relatively easy to teach within a Robotics, Machine Learning, and IoT course, providing students with an intuitive understanding of the technology that is rapidly transforming our world.






## Tricks:
1. **Start with a microcontroller that has proven successful for other educators.** In my case, I recommend the  [Seeedstudio #XIAO-ESP32S3-Sense](https://wiki.seeedstudio.com/xiao_esp32s3_getting_started/)  which costs around $14 USD. For 30 students, that totals $420. Yes, each student should have their own microcontroller. Additionally, you'll need USB-C cables, microSD cards, and pin headers.
2. **Class sets of most equipment aren't necessary.** Since the course is asynchronous, students can work at their own pace. This means you may only need a few of the more expensive sensors, like the Pixy2, a Lidar, or soldering equipment. While there are benefits to having class sets of all equipment, I’ve never found it necessary. Plus, it can create a storage mess.
3. **Demand peer teaching.** When a student successfully completes a curricular task, have them teach a few other students how to do it. This reinforces their understanding and builds a collaborative learning environment and really is the only way this course will be successful.
4. **Students can manage their own work.** They can download the curriculum from Github as a zip file, unzip it, and upload it to their own GitHub repositories, allowing them to organize and update their work effectively.
5. I have students make very short videos on the school network of each project, with a simple circuit diagram shown in the video. First time educators may just want to keep a running tally of the assignments they have seen working.
6. The inexpensive [Seeedstudio XIAO-SAMD21](https://wiki.seeedstudio.com/Seeeduino-XIAO/) microcontroller board for $7 USD which comes with pin headers is a great microcontroller for students to play with when testing new sensors and runs very similar to many Arduino boards, and easily is auto detected the Arduino IDE.
7. Note: The Educator decides which assignments to do and in what order and which ones to change, and also decides how many assignments to complete before class time is spent on the final projects.
8. Final projects determine the grade. Studentcan pass with a simple unique sensor actuator assignment, A grades can be assigned for multiple sensor and or multiple actuators, and or IoT and/or Machine learning. When students have completed these basic assignments they are expected to get together in groups and use there proven skills to attempt a group project.





# The Maker100 Curriculum

### A. Basics:
A01. Determine the software to install (Best to have some software installed before the class starts) A good software installation starting point is: [NodeJS](https://nodejs.org/en/download/package-manager), [Python](https://www.python.org/downloads/), [Arduino Legacy and New IDE](https://www.arduino.cc/en/software), [Pixymon2](https://pixycam.com/downloads-pixy2/), [Putty](https://www.putty.org/), [platformIO](https://platformio.org/), which needs [VSCode](https://code.visualstudio.com/download). Note: Good communication with the IT department is essential as new software will need to be installed during the course, especially if important upgrades are released.
A02. Determine the computer language to use: Probably best to work with a few standard languages and platforms. I mainly use Arduino C/CPP with the platforms: the Arduino Legacy and new IDE, the [arduino cloud](https://cloud.arduino.cc/) and platformIO. Other choices are: full GNU MAKE C/CPP, microPython, Zepher(RTOS) and the ESP-IDF as well as many more.
A03. Get the Blink program working using the Arduino IDE and your microcontroller, which means you will need to install the correct board and identify the PORT
A04. Understand libraries as some examples will not work until one or many libraries have been installed. My students install the "Portenta Pro Community Solutions" library in the Arduino IDE and have a look at the long list of examples that match many of the concepts in this curriculum. I made this library for the PortentaH7 produced by Arduino in 2020, many of the examples need to be slightly changed to work with the XIAO-esp32S3


### B. Coding
B01. Explain VIDEO FLAC as seen below. Have students write arduino code that shows to the serial monitor each of these abilities.
   
B02. V variables
B03. I Input/Output
B04. D Decisions (If statments and possibly case statements)
B05. E Events things that drive code
B06. O Objects (Structs in some languages like C/CPP)
   
B07. F Functions
B08. L Loops  For loops
B09. A Arrays
B10. C Classes

 

### C. Sensors

C01. Find a module sensor that has an analog output and get a reading on your micrcontroller serial monitor on pin A0
C02. Find a variable resistor sensor (has two prongs) like a thermistor, phtoresistor or flex sensor and use a Voltage Divider to get and control the reading on the serial monitor
C03. Use a button as a sensor and an LED with serial resistor as the actuator to get a visual response and a response on the serial monitor. This is an important assignment as it connects both sensors and actuator using a microcontroller
C04. 


### D. Machine Learning


### E. Actuators (Motors, LED's etc)



### F. IoT Comunication


### G. Projects
G01. (pass) Simple unique for each student sensor and actuator with circuit diagram
G02. (possible A) Multiple sensor and/or multiple actuator and/or IoT communication and/or Machine Learning final Project with circuit diagram
G03. (possible A+) Based on privious projects students get in groups and combine there strengths to make a useful or fun final project which must include Machine Learning. 


