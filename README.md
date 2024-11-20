# Micro-Line-Follower
This is a conversion of the SparkFun Arduino Line Follower Array code built for MicroPython
## Original Library
SparkFun's original library can be found [here](https://github.com/sparkfun/SparkFun_Line_Follower_Array_Arduino_Library/tree/master).
## Current Features
This library only includes the basic Line Follower Array code to get the position, this library will continue to be updated until all features from the original code are present.

# MicroPython Code Usage
Simple object intialization with default I2C pins for Pi Pico (SDA = 1, SCL = 0):
```python
from sensorbar import SensorBar

mySensor = SensorBar()

```

Object initialization with different I2C pins:

```python
from sensorbar import SensorBar

mySensor = SensorBar(sda = 10, scl = 11)
```
# Functions
The begin function starts the array
```python

mySensor.begin()

```
The GetPosition function returns a value from -127 to 127 with 0 in the middle of the sensor

```python

position = mySensor.GetPosition()

```
