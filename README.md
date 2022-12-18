<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# ePlant - a Building AI project

Final project for the Building AI course

## Summary

The idea is to have a small IoT devices connected to different sensors around your plant(s) / garden / or even industrial crops / greenhouses. This devices supposedly is going to first gather data, then use a simple regressions calculation using data to forecast if the plant is risking any kind of disease induced by the enviromnet (as of too much heat/humidity/light/wind could cause it) and warn the worker about it. Given enough devices and data, the system could start working on training a model to control and adjust the enviroment to optimise everything.


## Background

This project aim to help diffent figures in different situations.
It could help people with lack of knowledge or people that have inadequate care for this or people with not enough time or planning for an holiday.
On an industrial level it could lead to crops optimisation and because of the cheapness of these sensors, to the expansion and digitalisation of every type of farm.


## How is it used?

Installing sensors on the plant that can measure temperature, humidity, light intensity, soil moisture, and nutrient levels would be the first step. A single-board computer, such as a Raspberry Pi, or microcontroller can be connected to these sensors to collect and send sensor data.

The microcontroller or single-board PC can be modified to gather and store the sensor information in a data set. The data can be gathered on a regular basis (for instance, every hour) or triggered by particular occurrences (for instance, when the soil moisture falls below a certain level).

The gathered sensor information can be utilized to prepare an AI model that can anticipate the ideal circumstances for the plant. Based on the sensor data, the model could be trained to predict the plant's ideal temperature, humidity, and light intensity.

By adjusting the temperature, humidity, and light intensity to match the predicted ideal conditions, the machine learning model can be used to control the plant's environment. Grow lights, humidifiers, and thermostats that are connected to the microcontroller or single-board computer can be used to accomplish this.

A user interface, such as a web app or mobile app, that displays the current sensor readings and the anticipated optimal conditions can be used to monitor the system. If necessary (for example, to water the plant or add nutrients), the user can also manually adjust the system.

Plants could be automatically cared for by this AI-based system by monitoring and adjusting the environment to ensure that the plants are receiving the best conditions for growth. It could also inform the user of any issues with the plant, such as when the soil moisture drops below a certain level, or whether the plant requires fertilization or watering.

## Challenges

It would need expert figures to correctly understand if something is not properly working, and the necessity of someone else to fix it.

## What next?

The idea is that there could be a generalised knowledge base for a farm, with sensors in every kind of environment, all gathering data together and training a model daily.


## Acknowledgments

* https://www.educba.com/iot-in-agriculture/
* https://www.digiteum.com/iot-agriculture/
* https://www.cropin.com/iot-in-agriculture
