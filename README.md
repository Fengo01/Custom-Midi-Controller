# Custom-Midi-Controller

I Want to build a Midi Controller, that i can use on any PC, to controll my personal Room, DMX Lights via DMXC3 or maybe Virtual Dj or Voicemeeter or some of these Stuff



Progress 12.12.2025:

\# First thougts and parts i  want to use



\## Parameters for the Projekt

\- 10 motorized Fader --> Slide Potentiometer

\- 10 small SPI-Statusdiplays

\- 10.1″ Waveshare DSI-Touchdisplay

\- Buttons and Rotary Potentiometers

\- USB-Out to (MIDI/OSC)



\## Options for Microcontrollers

\- \*\*ESP32\*\*: USB-OTG, great for Controlling, Software and Connectors to Parts.

\- \*\*ESP32-P4\*\*: DSI-Support, 32 MB RAM, USB-OTG, Great for the Touchdisplay, Software and Connectors to Parts.

\- \*\*Teensy 4.1\*\*: many GPIOs, fast, great for Pherepherie, but no DSI.

\- \*\*RP2040\*\*: cheap, many GPIOs → Budget-Option for Peripherie, but no DSI.



\## First Decision

\- ESP32-P4 as Main-Controller for GUI and DSI-Display.

\- Secound Controller (ESP32, RP2040 or Teensy) for Fader, Buttons, Encoder and SPI-Displays.

\- Communication over USB-MIDI or I²C/SPI-Bridge or Serial Networking.



\## Parts i am going to use for the Projekt:

-- Slide Potentiometer: Behringer X32 Motor Fader

-- Big Touchdisplay: 10.1″ Waveshare DSI-Touchdisplay

-- small SPI-Statusdiplays: 1.14 inch TFT LCD 135 x 240 interface SPI (Made by Senzooe)

-- ESP32-P4 as Main-Controller for GUI and DSI-Display

-- If needed Secound Controller for additional Pins or Prozessing power

