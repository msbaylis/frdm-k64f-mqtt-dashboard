# frdm-k64f-mqtt-dashboard

This is a simple web dashboard to be used in conjunction with a Freescale FRDM-K64F board as part of an MQTT demo. The dashboard uses the Eclipse Paho MQTT Javascript client library to do the following:

  - connect/disconnect to the MQTT Dashboard public broker (broker.mqttdashboard.com)
  - subscribe to a user-defined MQTT topic
  - receive messages from the FRDM-K64F board when SW2 or SW3 is pressed and update/display the # of presses
  - send messages to the FRDM-K64F board when a dashboard button is clicked to control the state of the its LED
  - display a log of the messages sent/received

This web app also uses the following components:
  - jQuery
  - Bootstrap
  - Flat-UI

Code that runs on the FRDM-K64F was developed using the mbed.org online developer tools and can be found at the following URL:
https://developer.mbed.org/users/msbaylis/code/K64F-RTOS-MQTT-Example/
  
