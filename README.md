


# maker100-curriculum
maker100-robotics-machine-learning-IoT-communication-curriculum

Views better using the README.md [here](README.md)

Note:   
The 2024 economy version of this course is at [maker100-eco](https://github.com/hpssjellis/maker100-eco)   
The original 2021 version of this course is at  [maker100](https://github.com/hpssjellis/maker100)   

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
1. Start with a microcontroller that has proven successful for other educators. In my case, I recommend the  [Seeedstudio #XIAO-ESP32S3-Sense](https://wiki.seeedstudio.com/xiao_esp32s3_getting_started/)  which costs around $14 USD. For 30 students, that totals $420. Yes, each student should have their own microcontroller. Additionally, you'll need USB-C cables, microSD cards, and pin headers.
1. Class sets of most equipment aren't necessary. Since the course is asynchronous, students can work at their own pace. This means you may only need a few of the more expensive sensors, like the Pixy2, a Lidar, or soldering equipment. While there are benefits to having class sets of all equipment, I’ve never found it necessary. Plus, it can create a storage mess.
1. Demand peer teaching. When a student successfully completes a curricular task, have them teach a few other students how to do it. This reinforces their understanding and builds a collaborative learning environment and really is the only way this course will be successful.                                                                                                                                                                                                     
1. Students can manage their own work. They can download the curriculum from Github as a zip file, unzip it, and upload it to their own GitHub repositories, allowing them to organize and update their work effectively.
1. I have students make very short videos on the school network of each project, with a simple circuit diagram shown in the video. First time educators may just want to keep a running tally of the assignments they have seen working.
1. The inexpensive [Seeedstudio XIAO-SAMD21](https://wiki.seeedstudio.com/Seeeduino-XIAO/) microcontroller board for $7 USD which comes with pin headers is a great microcontroller for students to play with when testing new sensors and runs very similar to many Arduino boards, and easily is auto detected the Arduino IDE.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                
1. Note: The Educator decides which assignments to do and in what order and which ones to change, and also decides how many assignments to complete before class time is spent on the final projects.
1. Final projects determine the grade. Studentcan pass with a simple unique sensor actuator assignment, A grades can be assigned for multiple sensor and or multiple actuators, and or IoT and/or Machine learning. When students have completed these basic assignments they are expected to get together in groups and use there proven skills to attempt a group project.
1. I do not teach each assignment in the order presented, I often jump back and forth from  simple Senses and simple Machine learning and simple actuators then back to the main order. Note: For advanced students this coursee is Asychronous so that they can work ahead and solve issues that the other students will benefit from later.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                
1. No final projects using higher than 40 volts, water or drones, without some family safety protocols (such as parent is an electrical Enginer etc)


<br><br>


# The Maker100 Curriculum                                                                                                                                                                                                                      
                                                                                                                                                                                                                                              
&nbsp;&nbsp;<br><h2 name="basics">Basics</h2><br> 
1. **Base01-Install:** Determine the software to install (Best to have some software installed before the class starts) A good software installation starting point is: [NodeJS](https://nodejs.org/en/download/package-manager), [Python](https://www.python.org/downloads/), [Arduino Legacy and New IDE](https://www.arduino.cc/en/software), [Pixymon2](https://pixycam.com/downloads-pixy2/), [Putty](https://www.putty.org/), [platformIO](https://platformio.org/), which needs [VSCode](https://code.visualstudio.com/download) and [OpenMV](https://openmv.io/pages/download) Note: Good communication with the IT department is essential as new software will need to be installed during the course, especially if important upgrades are released.
1. **Base02-Language:** Determine the computer language to use: Probably best to work with a few standard languages and platforms. I mainly use Arduino C/CPP with the platforms: the Arduino Legacy and new IDE, the [arduino cloud](https://cloud.arduino.cc/) and platformIO. Other choices are: full GNU MAKE C/CPP, microPython, Zepher(RTOS) and the ESP-IDF as well as many more.
1. **Base03-Blink:** Get the Blink program working using the Arduino IDE and your microcontroller, which means you will need to install the correct board and identify the PORT
1. **Base04-Libraries:** Understand libraries as some examples will not work until one or many libraries have been installed. My students install the "Portenta Pro Community Solutions" library in the Arduino IDE and have a look at the long list of examples that match many of the concepts in this curriculum. I made this library for the PortentaH7 produced by Arduino in 2020, many of the examples need to be slightly changed to work with the XIAO-esp32S3                               
                                                                                                                                                                                                                      
                                                                                                                                                                                                                                              
     <br><br><h2 name="coding">Coding</h2><br>                                                                                                                                                                                                 
                     
Note: Explain VIDEO FLAC as seen below. Have students write arduino code that shows to the serial monitor each of these abilities.  Very important for stsudents to try to change and improve their code to learn how it works.
1. **Code01-Var:**  Variables, make code to show multiple types of variables in the serial monitor
1. **Code02-In-out:** Input/Output make code to read a variable from the serial monitor (click send) and print it to the serial monitor
1. **Code03-if:** Decisions (If statments and possibly case statements). Write code to make a decision based on information sent to the program from the serial monitor
1. **Code04-Events:** Events things that drive code  (This is actually from Javascript programming). Write a menu and have code do different things based on the menu decision, such as WASD, each letter makes something move a different direction
1. **Code05-structs:** Objects (Structs in some languages like C/CPP) Make a struct a fancy variable that connects a key word with data and presents the data in the serial monitor                                                                                                                                                                                                                      
   
1. **Code06-Functions:** Functions, write a function that prints to the serial monitor and then activate it
1. **Code07-Loops:**  Loops such as For loops (possibly while loops). Using a varible that stores a number print something that many times.
1. **Code08-Array:**  Arrays. Make an Array a fancy variable that numbers each value. a loop can be used to print the whole array to the serial monitor
1. **Code09-Class:**  Classes. A. Use a class. B. make a class from scratch and then use it.       
1. **Code10-SOS:**  In as few lines as possible make the onboard LED (LED_BUILTIN) flash an SOS. Which is 3 short flashes, 3 long flashes 3 short flashes                                                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                              
   <br><br><h2 name="sensors">Sensors</h2><br>
1. **Sense01-Analog:** Find a module sensor that has an analog output and get a reading on your micrcontroller serial monitor on pin A0, reminder to connect GND and 3V3 if needed
1. **Sense02-Voltage-Divider:** Find a variable resistor sensor (has two prongs) like a thermistor, phtoresistor or flex sensor and use a Voltage Divider to get and control the reading on the serial monitor
1. **Sense03-two-prong:** same as above but serial monitor analog read a different 2 prong sensor using a voltage divider.
1. **Sense04-Digital:** Connect a digital sensor like a button to the micrcontroller at show on the serial monitor when the button has been pressed
1. **Sense05-Button:** Actually the first actuator assignment but connect a resistor and an LED and make the LED blinnk like the onboard LED_BUILTIN from the BLINK program.
1. **Sense06-Sense-Actuate:** Combine the above two assignments to make your first sensor / actuator asssignment. This is what most Arduino style programs are like. Use a button as a sensor and an LED with serial resistor as the actuator to get a visual response and a response on the serial monitor. This is an important assignment as it connects both sensors and actuator using a microcontroller
1. **Sense07-Accel:** Use a 3 (or 6 or 9) axis accelerometer to measure x, y, z see if the results make sense knowing that veritacal acceleration due to gravity is about 9.8 m/s^2
1:**Sense0-joy-stick:** Connect a joy stick to your microcontroller and get a reading. This is almost exactly the same as  **Sense01-Analog:** with A0, 3V3 
1:**Sense0-:**                                                                                                                                                                       
1:**Sense0-:**                                                                                                                                                                       
1:**Sense0-:**                                                                                                                                                                       
1:**Sense0-:**                                                                                                                                                                       
1:**Sense0-:**                                                                                                                                                                       
1:**Sense0-:**                                                                                                                                                                       
1:**Sense0-:**                                                                                                                                                                       
1:**Sense0-:**                                                                                                                                                                       
                                                                                                                                                                                                                                              
 <br><br><h2 name="ML">Machine Learning</h2><br>
1. **ML01-sensecraft:** Use a simple way to install machine learning models to your microcontroller such as [sensecraft.seeed.cc](https://sensecraft.seeed.cc/ai/#/model) for the XIAO-ESP32S3-Sense
1. **ML02-vision:** Use [Edgeimpulse.com](https://edgeimpulse.com/) and your cell phone or another cloud based method to make a vision classification model by taking pictures of pen/pencils labelled "1pen" and things without them labelled "0unknown". The numbers are not needed but really help later when things get more complex. Test your model also from your cell phone.
1. **ML03-wake-word:**  Use [Edgeimpulse.com](https://edgeimpulse.com/) and your cell phone or another cloud based method to make a key word using sounds such as "Hi Google". Label recordings appropriately, you may want to record no sound and background sounds. 1. ML04-motion  Use [Edgeimpulse.com](https://edgeimpulse.com/) and your cell phone or another cloud based method to make a motion model using a 3 axis accelormeter. Now your labels might be "0still", "1wave", "2punch"
1. **ML05-FOMO:**  Use [Edgeimpulse.com](https://edgeimpulse.com/) and your cell phone or another cloud based method to make a Vision Fast objects, More Objects (FOMO) model, this now needs bounding boxes and a data queue to store the images before you draw labelled boxes around each image.
1. **ML06-deploy:** Use [Edgeimpulse.com](https://edgeimpulse.com/) to deploy one of the above models (deplaoy means to download the Arduino Library with examples for your microcontroller. Note: On widows computers the first compilation can take 15-25 minutes so get it compiling. Also look at the code and see if you can determine when the code prints out the results. A really good idea to try deploying all the EdgeImpulse models to your microcontroller.
1. **ML07-regression. Use EdgeImpulse.com to make a vision regression model (numerical size) and deploy the model to your device
1. **ML08-anomaly:** Use EdgeImpulse.com to make an anomaly detection model with two labels that can rate how different the classification is from the label and deploy it to your microcontroller                                                                                                                                              
                                                                                                                                                                                                                                              
 <br><br><h2 name="actuators">Actuators (Motors, LED's etc)</h2><br>
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**
1. **Act0-:**                                                                                                                                                                                                                
                                                                                                                                                                                                                                              
 <br><br><h2 name="iot"> IoT Internet of Things Connectivity<h2><br>
1. **IoT0-:**
1. **IoT0-:**
1. **IoT0-:**
1. **IoT0-:**
1. **IoT0-:**
1. **IoT0-:**
1. **IoT0-:**
1. **IoT0-:**
1. **IoT0-:**
1. **IoT0-:**
                                                                                                                                                                                                                     
                                                                                                                                                                                                                                              
 <br><br><h2 name=final>Final Projects </h2> Note: Be very leary of projects that use other microcontrollers as they are most likely are just a followed cookbook <br><br>
1. **Final01-simple:** (pass) Simple unique for each student sensor and actuator with circuit diagram (Proof of concept)
1. **Final02-multi:** (possible A or higher) Multiple sensor and/or multiple actuator and/or IoT communication and/or Machine Learning final Project with circuit diagram with 3D Printed structure (Can also be wood, metal, cardboard etc) (Prototype)
1. **Final03-group:** (possible A+) Based on prievious projects students get in groups and combine there strengths to make a useful or fun final project which must include Machine Learning. 



## Grading
Notes about how to grade students. 

Basically as long as the teacher is clear at the start of the course any grading method is fine. What I do is:
1. Students must finish all manadatory assignments, (When the entire class has difficulty with an assignment I make it optional until any student can do it or I get it working. In 2024 I never got e-ink working which stayed optional and GPS never worked for latitude and longitude, students gt full marks on that assignment if they generated all the GPS data, but I really wanted someone to parse the data for just latitude and longitude.
2. Once the manadatory assignments are complete they can start their final projects, which must be done in order, easy to hard (advanced students will work on a hard project and never get it finished).
3. I encourage students to work on multiple projects as some projects just can't be finished before marks are due.
4. Final grades come from final individual projects. Group projects just bump grades up a few percent.







