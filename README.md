# Micro-Line-Follower
This is a conversion of the SparkFun Arduino Line Follower Array code built for MicroPython
## Original Library
SparkFun's original library can be found [here](https://github.com/sparkfun/SparkFun_Line_Follower_Array_Arduino_Library/tree/master).
## Current Features
This library only includes the basic Line Follower Array code to get the position, this library will continue to be updated until all features from the original code are present.

# MicroPython Code Usage
Simple object intialization with default pins for Pi Pico (SDA = 1, SCL = 0):
```python
from sensorbar import SensorBar

mySensor = SensorBar()

```

