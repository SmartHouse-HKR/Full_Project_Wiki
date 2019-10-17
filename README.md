# SmartHouse@HKR

Here is the main information regarding the architecture and organization of this project.

## Table Of Contents

* [Guidelines and Standards](#Guidelines-and-Standards)

* [Server-Client Architecture](#Server-Client-Architecture)



## Guidelines and Standards

To make sure we are all on the same page when contributing, please look at our **[CONTRIBUTING.md](https://github.com/SmartHouse-HKR/GUIDELINES/blob/master/CONTRIBUTING.md)** guidelines.

## Server-Client Architecture.

We will be using **MQTT** as the main IoT protocol. 

<img src="https://jp.mathworks.com/help/supportpkg/raspberrypi/ref/mqtt_basics.png">

<sup>Figure 1: The MQTT publish-subscribe architecture <span id="a1">[[1]](#f1)</span></sup>


* **MQTT Versions**

   * MQTT v3.1.0 
   * MQTT v3.1.1 – Most common
   * MQTT v5 
   * MQTT-SN <a title="Note text goes here."><sup>n</sup></a>
   
* **MQTT Servers** (a.k.a. "Brokers")

   * Self-Hosted Servers:
       * [Mosquitto](http://www.steves-internet-guide.com/mosquitto-broker/)
       * Hive MQ

* **MQTT Packet Structure**

   Here is a good (and recently updated: 05/2019) explanation of the protocol structure:

   [Understanding the MQTT Protocol Packet Structure](http://www.steves-internet-guide.com/mqtt-protocol-messages-overview/)



## References

1. <span id="f1"></span> M. Publish and M. Subscribe, "Publish MQTT Messages and Subscribe to Message Topics- MATLAB & Simulink- MathWorks 日本", Jp.mathworks.com, 2019. [Online]. Available: https://jp.mathworks.com/help/supportpkg/raspberrypi/ref/publish-and-subscribe-to-mqtt-messages.html. [Accessed: 17- Oct- 2019]. [↩](#a1)



