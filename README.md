# Custom-Midi-Controller

I want to build a MIDI controller that I can use on any PC to control my personal room setup, DMX lights via DMXControl 3, or maybe software like Virtual DJ or Voicemeeter.



---



\## Progress (12.12.2025)



\### First thoughts and parts I want to use



\#### Parameters for the project

\- 10 motorized faders (slide potentiometers)

\- 10 small SPI status displays

\- 10.1″ Waveshare DSI touch display

\- Buttons and rotary encoders

\- USB output (MIDI/OSC)



\#### Options for microcontrollers

\- \*\*ESP32\*\*: USB-OTG, good for controlling, software and connectors to parts

\- \*\*ESP32-P4\*\*: DSI support, 32 MB RAM, USB-OTG, great for the touch display

\- \*\*Teensy 4.1\*\*: many GPIOs, fast, great for periphery, but no DSI

\- \*\*RP2040\*\*: cheap, many GPIOs → budget option for periphery, but no DSI



\#### First decision

\- ESP32-P4 as main controller for GUI and DSI display

\- Second controller (ESP32, RP2040 or Teensy) for faders, buttons, encoders and SPI displays

\- Communication over USB-MIDI, I²C/SPI bridge or serial networking



\#### Parts I am going to use

\- Motorized faders: Behringer X32 motor fader

\- Touch display: 10.1″ Waveshare DSI touch display

\- SPI status displays: 1.14″ TFT LCD 135×240 (Senzooe)

\- ESP32-P4 as main controller for GUI and DSI display

\- If needed: second controller for additional pins or processing power

