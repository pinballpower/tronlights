# LED light sources

## Aluminium houses 3-color LEDs

![](led_aluminium_enclosure.jpg)

RGB LED, common anode, rated 3W, tested up to about 2.5W per color

Continuous power of about 2W for 30minutes+ working well.

### U/I characteristics

|Current|R|G|B|
|---|---|---|---|
|200mA|2.5V|3.1V|3.3V|
|300mA|2.7V|3.3V|3.6V|
|400mA|3.0V|3.5V|3.8V|
|500mA|3.2V|3.7V|4.1V|
|600mA|3.5V|3.9V|4.4V|

Temperature of the aluminoium enclosure running on a single color at 400mA is <50°C. Running on a single color at 600mA, the device heats up to 65°C, which is still unproblematic. However, as the additional luminosity is minimal, it's probably best to drive these with about 400mA per color.

This results in the following resistor values when running at 5V or 6V operating voltage

|Voltage|R|G|B|
|---|---|---|---|
|5V|5&Omega;|3.8&Omega;|3&Omega;|
|6V|7.5&Omega;|6.3&Omega;|5.5&Omega;|


