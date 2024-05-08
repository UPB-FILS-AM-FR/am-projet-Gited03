# Your Project Name

| | |
|-|-|
|`Author` | NAZGODINEANU Eduard

## This project aims to develop a comprehensive RFID reader and writer program using an Arduino microcontroller and an RFID module RC-522. RFID (Radio Frequency Identification) technology is widely used for various applications such as access control, inventory management, and identification systems. The program will allow users to interact with RFID tags, both reading and writing data to them.

## Motivation

## Architecture for Arduino RFID Reader and Writer Program

1. Hardware Components:
Arduino Uno or similar microcontroller board.
RFID Module RC-522.
RFID tags (passive, writable).

2. Software Components:
Arduino IDE for writing and uploading code.
Arduino libraries for RFID module (e.g., MFRC522 library for RC-522).

3. System Flow:
Initialization:

The Arduino initializes communication with the RFID module using SPI protocol.
Setup function initializes the RFID module and serial communication for debugging.
Read RFID Tags:

The program continuously scans for RFID tags in its vicinity.
Upon detecting a tag, it reads its unique identifier (UID) and any additional data stored on the tag.
The UID and data are then displayed on the serial monitor for user observation.
Write to RFID Tags:

When triggered by user input, the program enters the writing mode.
User inputs data to be written to the tag through the serial monitor.
The program writes the provided data to a blank or rewritable RFID tag.
User Interface:

The user interacts with the program through the Arduino serial monitor.
Options for reading and writing data to RFID tags are displayed.
Feedback messages are provided to the user indicating the success or failure of operations.

### Block diagram

<!-- Make sure the path to the picture is correct -->
![Block Diagram](schematics/block_diagram.png)

### Schematic

![Schematic](schematics/kicad_schematic.png)

### Components


<!-- This is just an example, fill in with your actual components -->

| Device | Usage | Price |
|--------|--------|-------|
| Activ Buzzer | Buzzer | [1.5 RON](https://www.optimusdigital.ro/ro/audio-buzzere/635-buzzer-activ-de-3-v.html?search_query=buzzer&results=61) |
| Push Button | Button | [1 RON](https://www.optimusdigital.ro/ro/butoane-i-comutatoare/1119-buton-6x6x6.html?search_query=buton&results=222) |
| Jumper Wires | Connecting components | [7 RON](https://www.optimusdigital.ro/ro/fire-fire-mufate/884-set-fire-tata-tata-40p-10-cm.html?search_query=set+fire&results=110) |
| Breadboard | Project board | [10 RON](https://www.optimusdigital.ro/ro/prototipare-breadboard-uri/8-breadboard-830-points.html?search_query=breadboard&results=145) |

### Libraries

<!-- This is just an example, fill in the table with your actual components -->

| Library | Description | Usage |
|---------|-------------|-------|
| [lib-name1](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |
| [lib-name2](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |

## Log

<!-- write every week your progress here -->

### Week 6 - 12 May

### Week 7 - 19 May

### Week 20 - 26 May


## Reference links

<!-- Fill in with appropriate links and link titles -->

[Tutorial 1](https://www.youtube.com/watch?v=wdgULBpRoXk&t=1s&ab_channel=BenEater)

[Article 1](https://www.explainthatstuff.com/induction-motors.html)

[Link title](https://projecthub.arduino.cc/)
