# Tell Me Something

For my Interconnected Embedded Systems class (6.08) in Spring 2018, a third of the class was spent working on a final project with a group of 3 other students. This repository showcases that work. The original file structure is preserved, and I collected the code that I wrote myself or was the primary contributor to in the main directory.

The goal of the project was to create a useful, effective, and reliable home monitoring solution. This required developing a device-side solution to expose the appropriate sensors and manage power, and a server-side solution to interface with the device and expose the collected data to the user via a webpage.

My primary responsibility was designing the device-side infrastructure. I developed the libraries for communication with the server, created the structure of the code allowing the device to carry out requests from the server, and handled the particularly challenging aspect of recording and uploading audio data while staying within the memory constraints of the ESP32 Arduino-based system.

I also designed the schema for communication between the device and the server, developed some of the code to interface with the SQL database, and solved the problem of displaying the audio recorded on the device in a browser interface.
