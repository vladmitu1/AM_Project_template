# Your Project Name
ESP32 Led Webserver
| | |
|-|-|
|`Author` | Mitu Vlad-Mihai

## Description
An ESP32 LED Webserver is a project where an ESP32 microcontroller is programmed to control an LED (or multiple LEDs) via a web interface. The ESP32 acts as both the server and the controller, serving web pages to connected clients (such as a computer, smartphone, or tablet). These web pages provide an interface that allows users to interact with the LEDs, typically to turn them on or off, change their brightness, or alter their color (if RGB LEDs are used).
## Motivation
Educational Value:
Learning Embedded Systems: Building this project introduces the basics of embedded systems, including microcontroller programming, GPIO (General Purpose Input/Output) management, and PWM (Pulse Width Modulation).
Networking Fundamentals: Understanding how web servers work, managing HTTP requests/responses, and handling web-based communication.
Web Development: Enhances knowledge of front-end technologies (HTML, CSS, JavaScript) and how they interact with backend services.
Internet of Things (IoT): Provides practical insights into IoT concepts and how devices can be controlled over a network.
Practical Applications:
Home Automation: This project can be a stepping stone to more advanced home automation systems, allowing for remote control of lights and appliances.
Prototyping for Larger Projects: The skills and knowledge gained can be applied to develop more complex systems, such as smart home hubs or custom IoT devices.
Customization and Flexibility: Creating a custom web interface allows for personalized control mechanisms, which can be tailored to specific needs or preferences.
Cost-Effective Solutions: Utilizing the ESP32, a cost-effective microcontroller, allows for affordable development of powerful IoT applications.
## Architecture

### Block diagram

<!-- Make sure the path to the picture is correct -->
![Block Diagram](schematics/block_diagram.png)

### Schematic

![Schematic](schematics/kicad_schematic.png)

### Components


<!-- This is just an example, fill in with your actual components -->

| Device | Usage | Price |
|--------|--------|-------|
| ESP32 Wroom Devkit | ESP32 | [39,81 RON](https://www.sigmanortec.ro/placa-dezvoltare-esp32-cu-wifi-si-bluetooth?gad_source=1&gclid=EAIaIQobChMIqLqF6u6rhgMVC7CDBx13rwrIEAQYASABEgJvBPD_BwE) |


### Libraries

<!-- This is just an example, fill in the table with your actual components -->

| Library | Description | Usage |
|---------|-------------|-------|
| [lib-name1](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |
| [lib-name2](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |

## Log

<!-- write every week your progress here -->

### Week 6 - 12 May
I ordered the pieces for the initial project, made my documentation
### Week 7 - 19 May
I started writing the code for my initial project, a jammer.
### Week 20 - 26 May
The pieces arrived but they were wrong, I switched my project to a ESP32  led webserver. I bought the pieces Friday and made it in 2 days. Also I wrote the code Sunday and made the first try. The project was a little more complex, but I didn't find any breadboards in time.

## Reference links

<!-- Fill in with appropriate links and link titles -->



[Building a Simple ESP32 LED Webserver: Step-by-Step Tutorial](https://circuitdigest.com/microcontroller-projects/building-diy-led-webserver-with-esp32)

