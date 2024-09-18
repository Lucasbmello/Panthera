## 1. Serial communication.

Right click on the box that contains (at first, there will be only the folder "Scenes") and than on "Create". Create a new script in C#. The code can be found at this GitHub repository named as "serial_unity".

## 2. Important notes.

The Arduino code should return only the sensor values separated by commas. Unity read the values as a string, that is, if the Arduino returns text messages, there will be interferences in the values read by Unity, therefore it's important to Arduino return only floats. Thus, the C# code at Unity does the serial communication and transforms the variables from strings to floats.

Don't forget to close the Arduino serial monitor so that Unity can read the values. Furthermore, check if the "baud rate" and "serial port" objects are configured according to Unity and Arduino.

Finally, it's worth highlighting that this code is a test to see if the Unity is receiveing data correctly, so be sure that Arduino code is running the way you expect it to be. A tip is to use a simple electronic device as a potentiometer, for example, it's easier to see if the communication is working.