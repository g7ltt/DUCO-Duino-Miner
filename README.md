# DUCO/Duino-Miner

Here you will find designs for DUCO/DuinoCoin mining rigs based on various microcontrollers

# 5DN

Uses a Wemos D1 and 5 arduino Nano's. I2C communications between the Wemos and the Nano's with the Wemos handling the network connection via WiFi. An LCD can be added for diagnostic output adn the boards can be "stacked" via the I2C bus. When stacked only a single Wemos is required. Uses code by Ricuan and JK Rolling

# 16-01

Uses 16 ESP-01 modules in one of 2 configurations; I2C Master/Slave mode or WiFi only. In I2C mode uses 1 of the ESP-01's as a Master talking to 15 slaves. wiFi only uses the WiFi radio on all the devices.
