# DUCO/Duino-Miner

Here you will find designs for DUCO/DuinoCoin mining rigs based on various microcontrollers

# 5DN
![DUCO-Miner 5DN](https://github.com/g7ltt/Duino-Miner/blob/main/Duco%20Miner%205DN/DUCO%20Miner%205DN%20built%20-%20completed.jpg)
Uses a Wemos D1 and 5 arduino Nano's. I2C communications between the Wemos and the Nano's with the Wemos handling the network connection via WiFi. An LCD can be added for diagnostic output adn the boards can be "stacked" via the I2C bus. When stacked only a single Wemos is required. Uses code by Ricuan and JK Rolling

# 16-01
![DUCO-Miner 16-01](https://github.com/g7ltt/Duino-Miner/blob/main/DUCO%20Miner%2016-01/DUCO%20Miner%2016-01%20built.jpg)
Uses 16 ESP-01 modules in one of 2 configurations; I2C Master/Slave mode or WiFi only. In I2C mode uses 1 of the ESP-01's as a Master talking to 15 slaves. wiFi only uses the WiFi radio on all the devices.
