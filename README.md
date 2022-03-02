# Greenhouse_environment
The ESP8266 microcontroller (programmed in C++) receives signals from sensors via I2C and, after being set by the user via HTTP and SPIFFs, controls the operation of relays, presenting the readings in a front-end in HTML, CSS and JavaScript interface.

For PI reasons the Files are hidden. 


## User interface
The user interface has the logo and styles (font and colors) of the brand. Below, a representation of the greenhouse environment using charts.js. At the bottom of the page there are two inputs to set the minimum and maximum humidity.

![cogums estufa](https://user-images.githubusercontent.com/93688426/156463703-09ba9c8f-d8e6-4ac2-b256-fdc7a9bac6e0.png)

## Function
In the demonstration we can see the LCD display showing the current values of the greenhouse environment and also the set values. The same information is available on the local network in real time. The moment the minimum set is reprogrammed to a humidity higher than the current, the humidifier is turned on. Kazam!
