# bme280-rpi4

## Hardware setup
Here is a diagram of a breadboard setup.

![board setup](BME280-Module-Setup.png)

Before running the script you should check that your device is connected

```bash
sudo i2cdetect -y 1
```

## Running the script

```bash
python bme280.py
```

**Terminal output**

![teminal](bme280_setup.png)

**Reference**
https://www.raspberrypi-spy.co.uk/2016/07/using-bme280-i2c-temperature-pressure-sensor-in-python/
