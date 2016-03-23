[![MS5637-02BA03](MS5637-02BA03_I2CS.png)](https://www.controleverything.com/content/Analog-Digital-Converters?sku=MS5637-02BA03_I2CS)
# MS5637-02BA03
MS5637-02BA03 Pressure and Temperature Sensor.

The MS5637-02BA03 device provides a digital 24-bit pressure and temperature value.

This Device is available from ControlEverything.com [SKU: MS5637-02BA03_I2CS]

https://www.controleverything.com/content/Analog-Digital-Converters?sku=MS5637-02BA03_I2CS

This Sample code can be used with Raspberry pi.

## Java
Download and install pi4j library on Raspberry pi. Steps to install pi4j are provided at:

http://pi4j.com/install.html

Download (or git pull) the code in pi.

Compile the java program.
```cpp
$> pi4j MS5637_02BA03.java
```

Run the java program.
```cpp
$> pi4j MS5637_02BA03
```

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python MS5637_02BA03.py
```

#####The code output is the pressure in mbar and temperature reading in degree celsius and fahrenheit.
