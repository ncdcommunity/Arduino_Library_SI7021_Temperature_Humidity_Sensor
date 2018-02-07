[![SI7021](SI7021_I2C.png)](https://store.ncd.io/product/si7021-humidity-and-temperature-sensor-%C2%B13rh-%C2%B1-4c-i2c-mini-module/)

# SI7021

The Si7021 I2C Humidity and Temperature Sensor is a monolithic CMOS IC integrating:humidity and temperature sensor elements,an analog-to-digital converter,signal processing,calibration data, and an I2C Interface.
This Device is available from www.ncd.io 

[SKU: SI7021_I2CS]

(https://store.ncd.io/product/si7021-humidity-and-temperature-sensor-%C2%B13rh-%C2%B1-4c-i2c-mini-module/)
This Sample code can be used with Arduino.

Hardware needed to interface SI7021 sensor with Arduino

1. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-nano/">Arduino Nano</a>

2. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-micro-with-i2c-expansion-port/">Arduino Micro</a>

3. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-uno/">Arduino uno</a>

4. <a href="https://store.ncd.io/product/dual-i2c-shield-for-arduino-due-with-modular-communications-interface/">Arduino Due</a>

5. <a href="https://store.ncd.io/product/si7021-humidity-and-temperature-sensor-%C2%B13rh-%C2%B1-4c-i2c-mini-module/">SI7021 Temperature and humidity Sensor</a>

6. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

SI7021:

The Si7021 I2C Humidity and Temperature Sensor is a monolithic CMOS IC integrating:humidity and temperature sensor elements,an analog-to-digital converter,signal processing,calibration data, and an I2C Interface.

Applications:

• Respiratory therapy

• Defogging

• Mobile phones and tablets

• White goods

• Indoor weather stations

• Asset/goods tracking

• Automotive climate controls

• Micro-environments/data center monitoring.

How to Use the SI7021 Arduino Library

The SI7021 has a number of settings, which can be configured based on user requirements.
          
1.Address calling:The following command is used to call the SI7021 sensor to begin the transmission.

          si.getAddr_SI7021(SI7021_DEFAULT_ADDRESS);   // 0x40
            
2.Resolution setup:The following command is used to set the resolution.

          si.setResolution(RESOLUTION_0);             // RH: 12 bit, Temp: 14 bit
             
3.Voltage setup:The following command is used to set the voltage.             
             
          si.setVoltage(VOLTAGE_OK);                  // VDD OK      

4.Heater status:The following command is used to ENABLE the heater.

           si.setHeaterStatus(HEATER_ENABLE);          // On-chip Heater Enable
             
5.Heater current:The following command is used to set the heater current.        
             
          si.setHeaterCurrent(HEATER_3_09);           // Heater Current: 3.09 mA
             
6.Temperature mode:The following command is used to measure temperature in NO HOLD master mode.             
             
           si.setTempMode(TEMP_NO_HOLD);               // Measure Temperature, No Hold Master Mode   
           
7.Humidity mode:The following command is used to measure humidity in NO HOLD master mode.             
             
          si.setHumidityMode(HUMIDITY_NO_HOLD);       // Measure Humidity, No Hold Master Mode
          
