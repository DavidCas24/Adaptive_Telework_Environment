Run Particle library

The Particle Library deployment option packages all your signal processing blocks, configuration and learning blocks up into a single library (.zip file). You can include this library in your own application to run the impulse locally.
​
Particle Libraries

To run your Impulse on your Particle board follow these steps:

1. Open a new VS Code window, ensure that Particle Workbench has been installed.
2. Use VS Code Command Palette and type in Particle: Import Project
	a. Select the project.properties file in the directory that you just downloaded and extracted from the section above.
3. Use VS Code Command Palette and type in Particle: Configure Project for Device
	a. Select deviceOS@5.3.2 (or a later version)
	b. Choose a target. (e.g. P2 , this option is also used for the Photon 2).
4. It is sometimes needed to manually put your Device into DFU Mode. You may proceed to the next step, but if you get an error indicating that “No DFU capable USB device available” then please follow these step.
	a. Hold down both the RESET and MODE buttons.
	b. Release only the RESET button, while holding the MODE button.
	c. Wait for the LED to start flashing yellow.
	b. Release the MODE button.
5. Compile and Flash in one command with: Particle: Flash application & DeviceOS (local).

More information: https://docs.edgeimpulse.com/tutorials/topics/inference/run-particle

