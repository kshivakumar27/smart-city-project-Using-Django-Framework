
<h1>Requirements</h1>
<h4>Hardware Requirements</h4>sensors,aralms,camera,sprinklers,motors,capacitives,humidity meters,moisture meters,street lights.
<h4>Software requirments</h4>Web application for monitoring users and admin,CCtv camera for 24/7 survivalence,Computers,wifi ,cloud support databases for admin and users,mobile apps,servers.





<h2>Explanation in steps</h2>
Step 1 : Purpose and Requirement Specification 
•	Purpose – The purpose of IoT gardening is to maintain the well-being of a garden using the power of the Internet of Things (IoT). With the help of present tools and software, planter is integrated with sensors that monitors the real-time status of the plants.

•	Behaviour – The IoT smart gardening has both auto and manual modes.

•	System Management Requirements -   A Raspberry Pi is used to relay useful information of the garden, such as luminosity, humidity and the moisture content in the soil from various sensors into a cloud database. Once the information is in the cloud, it can be accessed from anywhere using a Smartphone app.

•	Data Analysis Requirements – The system performs local Analysis of data, based on that it will decide whether to turn on street lights or to turn on water pumps.

Step 2 : Process Specification

In this step the use cases of the IoT system are formally described based on and derived from the purpose and requirement specification.

shows the process diagram for street lights and water pumps. The process diagram shows two modes of the system – auto and manual. When auto mode is chosen the system monitors the light level. If the light level is low, the system changes the light state to “on”. Where as if the light level is high, the system change the state of light to “off”. But in case of manual mode user will change the state of light.

Step 3 : Domain Model Specification 

•	Physical Entity – The Physical Entity is a discrete and identifiable entity in the physical environment (e.g., plants, soil, light, etc.). The IoT system provides information about the physical entity by using sensors and performs actuation upon the Physical Entity like switching on a light.

•	Virtual Entity -  Virtual entity is the representation of physical entity in the digital world. For each physical entity, there is a virtual entity in domain model. In the IoT smart gardening there is one virtual entity for Appliance and one more virtual entity for lights.

•	Device – Device provide a medium for communication between physical entity and virtual entity. Devices are used to gather information about physical entity and perform actuations upon physical entities. Device used in smart gardening is minicomputer.

•	Resources – Resource are soft component which can be either “on-device” or “network resources”. On-device Resource used in smart gardening is operating system that runs on the single board mini computer.

•	Service – The services provided by smart gardening system are as follows,
	Drip irrigation system
	App controlled water system
	Automatic watering schedules
	Database of the garden's health status
	Real-time feedback of the garden's various sensors


Step 4 : Information model Specification
	Information model defines the structure of all the information in the IoT system. In smart gardening application there are two Virtual Entities – a virtual entity for Appliance with the attributes of Streetlights, plastic object detectors, temperature sensors and a virtual entity for water pumps. 


Step 5 : Service Specifications
	The fifth step in the IoT design methodology is to define the service specification. Service specification define the services in the IoT system types, service inputs/output, service endpoints, service preconditions and service effects.
	 shows an example of deriving the services from the process specification and information model for IoT Smart Gardening system. From the process specification and information model the states and attributes can be identified for which each state and attribute defines a service. The mode service sets mode to auto or manual or retrieves the current mode. The state service sets the light appliance state to on/off or retrieves the current light state. The controller service monitors the light level in auto mode and switches the light on/off and updates the status in status database.

Virtual entity is the representation of physical entity in the digital world. For each physical entity, there is a virtual entity in domain model. In the IoT smart gardening there is one virtual entity for Appliance and one more virtual entity for lights
The mode service sets mode to auto or manual or retrieves the current mode. The state service sets the light appliance state to on/off or retrieves the current light state. The controller service monitors the light level in auto mode and switches the light on/off and updates the status in status database.


Step 6 : IoT Level Specification
	The sixth step in the IoT design methodology is to define the IoT level for the system. The services provided by the system of numerous elements like sensors, protocols, actuators, cloud services, and layers the services in the sence such a number is chosen to include these various types of components into a complex network.
Services by the node device which have unique identities and states can perform remote sensing, actuating and monitoring capabilities of on and off from remotes place.Communication established between things and cloud based server over the Internet by various IOT protocols and the alert can be disabled by the user from the mobile application.


Step 7 : Functional View Specification
	functional groups shows the mapping of deployment level to functional groups for smart gardening. 
IoT device maps to the device functional groups like sensors, actuators and computing devices and the management functional groups. Resources map to the device functional group and communication functional group. Web services maps to services functional group. Database maps to Management functional group where as Application maps to application functional group and security functional group.


Step 8 : Operational View Specification
	The eighth step is to define the operational view specifications. In this step various options pertaining to the IoT system deployment and operation are defined such as service hosting options, storage options, device options and application hosting options.
	
	
<h3> Some hardware devices</h3>

![Capacitor](https://github.com/Shivkumargowdru/smart-park/blob/main/Images/Annotation%202020-06-18%20001533.png),![](https://github.com/Shivkumargowdru/smart-park/blob/main/Images/Annotation%202020-06-18%20002717.png)


![Street lights](https://github.com/Shivkumargowdru/smart-park/blob/main/Images/Annotation%202020-06-18%20002036.png)
