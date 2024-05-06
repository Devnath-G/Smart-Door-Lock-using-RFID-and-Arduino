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

## Installation

1. **Hardware Setup**: Connect the RFID reader, servo motor, LEDs, and Arduino according to the circuit diagram.
2. **Upload Code**: Upload the Arduino code provided in the repository to your Arduino board.
3. **Configure RFID Tags**: Program the RFID tags/cards with unique IDs for each authorized user.
4. **Mount the System**: Mount the components on or near the door you want to control access to.

## Usage

1. **Enroll Users**: Add new users by scanning their RFID tags/cards and storing their IDs in the Arduino code.
2. **Lock/Unlock**: To lock the door, simply trigger the locking mechanism using the Arduino code. To unlock, scan an authorized RFID tag/card.
3. **LED Feedback**: LED(s) will indicate the status of the lock (locked/unlocked) for visual confirmation.


