# Two-Factor-Authentication-System-using-RFID-Sensor-and-Keypad

##Overview
This project implements a two-factor authentication (2FA) system that uses both RFID (Radio Frequency Identification) and a keypad for enhanced security. Users must present an RFID card and enter a correct PIN code to gain access.

##Features
RFID Authentication: Uses RFID cards to identify users.
Keypad Input: Requires a PIN code entered via a keypad.
Two-Factor Authentication: Combines something you have (RFID card) with something you know (PIN code) for secure access.
Access Control: Only grants access when both the RFID card and PIN code are correct.
Components
RFID Reader: Reads RFID cards.
Keypad: Allows users to input their PIN codes.
Microcontroller: Processes the RFID and keypad inputs (e.g., Arduino, Raspberry Pi).
Access Control System: Acts upon successful authentication (e.g., unlocks a door).
Installation
Hardware Setup:

Connect the RFID reader to the microcontroller.
Connect the keypad to the microcontroller.
Connect the access control system (e.g., door lock) to the microcontroller.
Software Setup:

Install the required libraries for the RFID reader and keypad.
Upload the provided code to the microcontroller.
Example Wiring (Arduino)
Component	Arduino Pin
RFID Reader	RX, TX
Keypad	Digital Pins (e.g., 2-9)
Door Lock	Digital Pin (e.g., 10)
Usage
Add Authorized RFID Cards:

Modify the code to include the unique identifiers (UIDs) of authorized RFID cards.
Set PIN Codes:

Modify the code to set the corresponding PIN codes for each authorized RFID card.
Operation:

Present the RFID card to the reader.
Enter the corresponding PIN code on the keypad.
If both the RFID card and PIN code are correct, the access control system will be triggered (e.g., door will unlock).
