# Cayenne 2 State Widget Example

This sketch shows how to set up a 2 State Widget with Cayenne.

###### Steps:
1. In the Cayenne Dashboard add a new 2 State Custom Widget.
2. Select a digital pin number.
3. Attach a digital input device (e.g. a button) to the digital pin on your Arduino matching the selected pin.
4. Set the token variable to match the Arduino token from the Dashboard.
5. Compile and upload this sketch.
6. Once the Arduino connects to the Dashboard it should automatically update the 2 State widget with data.

Notice that there isn't much coding involved to interact with the digital pins.
Most of it is handled automatically from the Cayenne library.

For further examples of how to send data to Cayenne see the example sketches under Sensors.