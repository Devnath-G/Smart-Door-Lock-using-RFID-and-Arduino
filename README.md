# Smart Door Lock with RFID using Arduino

This project is about creating a smart door lock system using Arduino and RFID technology. The system allows users to unlock a door by scanning an RFID tag or card, providing a secure and convenient way to control access to a room or building.

## Features

- **RFID Authentication**: Users can unlock the door by scanning their RFID tag or card.
- **Secure Access Control**: Only authorized users with valid RFID tags can unlock the door.
- **Arduino Control**: The system is powered by Arduino, making it easy to customize and expand.
- **LED Feedback**: Visual feedback through LEDs indicates the status of the lock (locked/unlocked).
- **Reliable and Convenient**: Provides a reliable and convenient way to control access without the need for traditional keys.

## Components Required

- Arduino Uno or compatible board
- RFID Reader Module
- RFID Tags or Cards
- Servo Motor (for locking/unlocking mechanism)
- LED(s)
- Buzzer
- Breadboard and Jumper Wires


## How to Identify the UID for your RFID Tags:
- First open up your Arduino IDE and ensure you have the "MFRC522" library installed and connect your components.
- Once coonnected, Go to File > Examples > MFRC522 > DumpInfo.
- Once you click on DumpInfo and new code will open, compile and upload the following code to your Arduino.
- Once that's done open the Serial Monitor and scan your tag, once scanned the UID will be displayed and copy/note down the UID and paste it into your code to ensure the RFID Moduel accepts your tag. 



## Installation

1. **Hardware Setup**: Connect the RFID reader, servo motor, LEDs, and Arduino according to the circuit diagram.
2. **Upload Code**: Upload the Arduino code provided in the repository to your Arduino board.
3. **Configure RFID Tags**: Program the RFID tags/cards with unique IDs for each authorized user. (Please Note: Change the UID Tag according to your tag as every tag has its own unique UID)
4. **Mount the System**: Mount the components on or near the door you want to control access to.

## Usage

1. **Enroll Users**: Add new users by scanning their RFID tags/cards and storing their IDs in the Arduino code.
2. **Lock/Unlock**: To lock the door, simply trigger the locking mechanism using the Arduino code. To unlock, scan an authorized RFID tag/card.
3. **LED Feedback**: LED(s) will indicate the status of the lock (locked/unlocked) for visual confirmation.


