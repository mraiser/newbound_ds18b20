# newbound_ds18b20
A collection of useful Newbound Metabot controls for measuring and logging temperature with the DS18B20 on a Raspberry Pi and Pi-compatible computers.

# Dependencies
This project requires an up-to-date working installation of the Newbound software
https://github.com/mraiser/newbound

# Installation
1. Move the data/ds18b20 and runtime/ds18b20 folders into your Newbound installation's data and runtime folders, respectively
2. Launch the Newbound software
3. Publish the "ds18b20" control in the "ds18b20" library using the Metabot app
4. Restart the Newbound software

*Instead of moving the data/ds18b20 and runtime/ds18b20 folders you can create symbolic links to them, leaving your git project folder intact for easy updating*
