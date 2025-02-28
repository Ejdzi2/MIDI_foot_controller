# MIDI_foot_controller
This is the subjective project for creating the MIDI_foot_controller aka Bass Pedal using an Arduino micropro board and https://github.com/tttapa/MIDI_controller library - a great library for creating a MIDI controllers using an Arduino boards.  
This library has been obsoleted by its successor, the [**Control Surface**](https://github.com/tttapa/Control-Surface) library but for this particular project (foot controler) it was enough.

The MIDI_controller library was sligthtly modified to suit my needs. Particulary MIDI_OUTPUTS src (Digital.cpp and DigitalCC.cpp).

# Installation
Installing the MIDI_foot_controller library

To install this library, download it s a .ZIP file. Then open the Arduino IDE, go to Sketch > Include Library > Add .ZIP library, and open the .ZIP file you just downloaded. 

Dependencies
The MIDI_controller library depends on the PJRC Encoder library for using rotary encoders and jog wheels. Download the .ZIP library from GitHub and install it.
If you are using an Arduino with native USB support, like the Leonardo, Due, Zero, Micro ... you'll need to install the MIDIUSB library. Install it using the Arduino IDE's library manager (Sketch > Include Library > Manage Libraries). Search for 'MIDIUSB', and install it. Alternatively, download the .ZIP library from GitHub and install it.

# Uploading
Arduino boards with native USB support (Arduino micropro)

Open controller_foot.ino, connect your Arduino, select the right port from the Tools menu, and hit upload.

# Diagram

![obraz](https://user-images.githubusercontent.com/81420520/146534655-2f38a112-d62d-41f1-814b-bcae3a70d481.png)
