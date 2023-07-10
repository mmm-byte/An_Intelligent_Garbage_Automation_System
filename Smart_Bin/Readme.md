# Smart Bin

The Smart Bin Project is an IoT-based solution that aims to optimize waste management by monitoring and managing the waste levels in bins in real-time. This repository contains the source code and documentation for the project.

## Features

- Real-time monitoring of waste levels in smart bins
- Data processing and analytics for waste management insights
- Web-based dashboard for remote monitoring and user interaction
- Automated notifications and alerts for optimized waste collection
- Integration with IoT devices, sensors, and actuators

## Technologies Used

- Microcontrollers/IoT devices (e.g., Arduino, Raspberry Pi)
- Sensors (e.g., ultrasonic sensors, weight sensors)
- Actuators (e.g., servo motors, solenoids)
- Backend infrastructure (e.g., Node.js, Express.js)
- Database (e.g., MongoDB, Firebase)
- Data processing and analytics (e.g., Python, Matplotlib)
- Web application (e.g., HTML, CSS, JavaScript)
- Communication protocols (e.g., Wi-Fi, Bluetooth)

### Prerequisites

- #### Arduino Uno
Arduino Uno is an open-source microcontroller board based on the processor ATmega328P. It has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analog inputs, a USB connection, a power jack, an ICSP header and a reset button. It contains everything needed to support the microcontroller. Just plug it into a computer with a USB cable or power it with an adapter to get started. You can experiment with your Arduino without worrying too much about it. In the event of a worst case scenario, you could buy a new one as the Uno is very economical.
- #### Ultrasonic Sensor HC-SR04
HC-SR04 is an ultrasonic distance sensor used for measuring the distance at which an object is located. The principle used by this sensor is called SONAR. It is perfect for small robotics projects such as obstacle avoiding robot, distance measuring device etc. It has two parts, one emits the ultrasound sonar to measure the distance to an object. The other part is the receiver which listens for the echo. As soon as the ultrasound hits the object it bounces back and is detected by the receiver. The time taken for the wave to come back decides the distance of the object being measured.
- #### SG90 Micro servo motor
The micro servo 9G is a light, good quality and very fast servo motor. This servo is designed to work with most radio control systems. It is perfect for small robotics projects. The SG90 mini servo with accessories is perfect for remote-controlled helicopters, planes, cars, boat,s and trucks.
- #### Arduino IDE
The Arduino Integrated Development Environment - or Arduino Software (IDE) - contains a text editor for writing code, a message area, a text console, a toolbar with buttons for common functions and a series of menus. It connects to the Arduino hardware to upload programs and communicate with them.

## Getting started

- It is important to dispose of the trash properly. It is a responsibility with which everyone should comply. In the era of Covid-19, people are trying to innovate everyday life things and make things as contactless as possible. Smart dustbin is one of those innovative ideas.  
- The smart dustbin uses an Ultrasonic sensor HC-SR04 to detect objects in front. 
- It then sends the signals to Arduino Uno. The Arduino understands the signal and sends a signal to the Servomotor which opens the flap on top of the dustbin.
- Here we have program it to open the race for only 3 seconds after 3 seconds the flap automatically closes. You can change that time just by making minor changes to the code in Arduino IDE.
- The Ultrasonic sensor HC-SR04 pins echo and trig are connected to Arduino Uno pins 5 and 6 respectively. The VCC pin is connected to 5V on Arduino Uno and both the grounds are connected together. 
- A 9v battery has been connected to Vin pin on the Arduino Uno and grounds are connected together. 


