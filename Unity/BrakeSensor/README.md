## Notes

This section presents the configurations and the code to change the color of the brakes based on the data received from the brake pressure sensor.

Look at main to see the changes in the SerialCommunication code.

## Unity configurations

- First, you will need to have your model in the project.
- In the folder named codes, create a new C# script named "BrakeSensor" and write the code from this GitHub folder.
- Drag this code to the object components (Inspector tab) you want to change the color. In this case, front brake and rear brake.
- Then, still in the Inspector tab, drag the mesh renderer from the object to the script.
- Create an empty object named SerialManager, it will control de main code.
- Drag the SeriaCommunication script from this section to SerialManager components. Now you are able to change the colors of the brakes using data sensor!