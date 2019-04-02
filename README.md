# WL-Sense-Analytics-ThingChart
In this project we are publishing the wireless Vibration and Temperature sensor data to Thing Speak using ThingSpeak MQTT API.
We have also made an interactive webpage using html,CSS,BootStrap and Javascript function where we can visualize different sensor data using Google Charts.
In our firmware we are loading this webpage from SPIFFS and streaming it on local WiFi IP. We can see it by opening local WiFi IP in web browser.

* First of all open the local WiFi IP in your Webbrowser.
* Second step is to Select the sensor as an example here we have selected Vibration and Temperature Sensor also check the Show Temperature   Graph Checkbox to Show Temperature in Celcius and Fahrenhite Area Chart.
* In the third Step select the Event to e triggered we are using IFTTT for email notification and messages

![gChart1](https://github.com/ncdcommunity/WL-Sense-Analytics-ThingChart/blob/master/googleGraph.png)

* Then Hit Submit button and the area chart will show up on the top left side of the webpage

![gChart1](https://github.com/ncdcommunity/WL-Sense-Analytics-ThingChart/blob/master/gChart4.png)

* Similarly if we can do not need Temperature Graph Uncheck the checkbox and only vibration graph will show up.. 

![gChart1](https://github.com/ncdcommunity/WL-Sense-Analytics-ThingChart/blob/master/gChart1.png)

![gChart1](https://github.com/ncdcommunity/WL-Sense-Analytics-ThingChart/blob/master/gChart2.png)
