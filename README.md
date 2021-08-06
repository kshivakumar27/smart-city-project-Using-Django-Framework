Step 1 : Purpose and Requirement Specification 
•	Purpose – The purpose of IoT gardening is to maintain the well-being of a garden using the power of the Internet of Things (IoT). With the help of present tools and software, planter is integrated with sensors that monitors the real-time status of the plants.

•	Behaviour – The IoT smart gardening has both auto and manual modes.

•	System Management Requirements -   A Raspberry Pi is used to relay useful information of the garden, such as luminosity, humidity and the moisture content in the soil from various sensors into a cloud database. Once the information is in the cloud, it can be accessed from anywhere using a Smartphone app.

•	Data Analysis Requirements – The system performs local Analysis of data, based on that it will decide whether to turn on street lights or to turn on water pumps.

Step 2 : Process Specification

In this step the use cases of the IoT system are formally described based on and derived from the purpose and requirement specification.

Figure 2.1 shows the process diagram for street lights and water pumps. The process diagram shows two modes of the system – auto and manual. When auto mode is chosen the system monitors the light level. If the light level is low, the system changes the light state to “on”. Where as if the light level is high, the system change the state of light to “off”. But in case of manual mode user will change the state of light.
