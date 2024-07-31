# Automated_Gardening_System

As time passes, automation is taking over in every aspect of our life. One important part is food. The quality of food depends on various factors one such being irrigation.
But with growing concerns around resource management and water wastage, the current system is proving to be inefficient. Water is being wasted, sometimes only because humans are not quick enough to respond and more water is provided than the plants require. Hence, we propose a basic automatic gardening system.

A system which uses a microcontroller and some sensors for smart gardening. We use Raspberry PI, along with soil moisture sensor and water level sensor to automate the gardening system making it more efficient.We check the moisture of soil, and if it’s below a threshold we check the water tank level and if it’s above a certain minimum, water automatic starts pouring on the plants. It stops when either the threshold moisture level is attained or when the water level drops below the defined minimum.

We also check the intensity of light falling on the plants to turn on/off an artificial sunlight source (led here for example).Besides this, if you still want custom control over your irrigation and light, we provide a mobile app, which not only enables you to custom control the light and motor, but also gives real time moisture level and light intensity data to choose what is best for your plants.

This, as stated earlier, is a basic automation and has the potential of growing and become better with time.

Project Overview   
  -Microcontroller: Raspberry Pi    
  -Sensors: Soil moisture sensor, water level sensor
  
  -Functions:
  
    Automatically waters plants based on soil moisture and tank water level.
    Controls artificial lighting based on light intensity.
    Mobile app for manual control and real-time data monitoring.
    
  -Software and Tools:
  
    Python3: Scripts for interfacing Raspberry Pi with various components and the internet.
    Visual Studio Code: Development environment for the app.
    GPIO: Python library to send and receive signals from Raspberry Pi.
    LightSensor: Python library for interfacing Raspberry Pi with LDR.
