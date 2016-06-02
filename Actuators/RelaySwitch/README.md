# Cayenne Relay Switch Example

This sketch sample file shows how to connect a Relay Switch.

###### Steps:
1. In the Cayenne Dashboard add a new Custom Widget, and select Button.
2. Select a Virtual channel number.
3. Set VIRTUAL_PIN to the channel number you selected.
4. Connect the Relay Switch to a digital pin.
5. Set RELAY_DIGITAL_PIN to the digital pin number you selected.
6. Set the token variable to match the Arduino token from the Dashboard.
7. Compile and upload this sketch.
8. Once the Arduino connects to the Dashboard use the button widget to turn on/off an LED wired through the Relay.