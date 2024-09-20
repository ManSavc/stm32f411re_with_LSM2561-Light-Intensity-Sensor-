There I show how to read light sensor with CubeIde.Sensor have 2 work mode : Standart-Mode 100kHz and Fast-Mode 400kHz, connect VCC, GND(3.3V!) and I2C,
just copy this code and you will see how this(tsl2561)sensor works.There I add a video  

https://github.com/user-attachments/assets/2be87902-cf9e-40f7-8e1a-8b2c0973afce

This sensor have 2 photo diodes, one for visible light and infrared, other - just for infrared.
 After applying VDD, the device will initially be in the power-down state. To operate the device,
 issue a command to access the CONTROL register followed by the data value 03h to power up the 
 device. At this point, both ADCchannels will begin a conversion at the default integration time 
 of 400 ms. After 400 ms, the conversion results will be available in the DATA0 and DATA1 registers.
 In video record you see how to decrease visible light when desk lamp are turn off.
