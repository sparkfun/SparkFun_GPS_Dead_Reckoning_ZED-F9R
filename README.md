SparkFun GPS-RTK Dead Reckoning Breakout - ZED-F9R (Qwiic)
========================================

[![SparkFun GPS-RTK Dead Reckoning Breakout - ZED-F9R (Qwiic)](https://cdn.sparkfun.com//assets/parts/1/5/0/5/9/16344-SparkFun_GPS-RTK_Dead_Reckoning_Breakout_-_ZED-F9R__Qwiic_-01a.jpg)](https://www.sparkfun.com/products/16344)

[*SparkFun GPS-RTK Dead Reckoning Breakout - ZED-F9R (Qwiic) (GPS-16344)*](https://www.sparkfun.com/products/16344)

The SparkFun ZED-F9R GPS Breakout is a high precision, sensor fusion GPS board with equally impressive configuration options and takes advantage of u-blox's Automotive Dead Reckoning (ADR) technology. The ZED-F9R module provides a highly accurate and continuous position by fusing a 3D IMU sensor, wheel ticks, a vehicle dynamics model, correction data, and GNSS measurements.

The ZED-F9R module is a 184-channel u-blox F9 engine GNSS receiver, meaning it can receive signals from the GPS, GLONASS, Galileo, and BeiDou constellations with ~0.2 meter accuracy! That's right, such accuracy can be achieved with an RTK navigation solution when used with a correction source. Note that the ZED-F9R can only operate as a rover, so you will need to connect to a base station. The module supports concurrent reception of four GNSS systems. The combination of GNSS and integrated 3D sensor measurements on the ZED-F9R provide accurate, real-time positioning rates of up to 30Hz.

Compared to other GPS modules, this breakout maximizes position accuracy in dense cities or covered areas. Even under poor signal conditions, continuous positioning is provided in urban environments and is also available during complete signal loss (e.g. short tunnels and parking garages). The ZED-F9R is the ultimate solution for autonomous robotic applications that require accurate positioning under challenging conditions.

Additionally, this u-blox receiver supports I2C (u-blox calls this Display Data Channel) which makes it perfect for the Qwiic compatibility so we don't have to use up our precious UART ports. Utilizing our handy Qwiic system, no soldering is required to connect it to the rest of your system. However, we still have broken out 0.1"-spaced pins in case you prefer to use a breadboard.

U-blox based GPS products are configurable using the popular, but dense, windows program called u-center. Plenty of different functions can be configured on the ZED-F9R: baud rates, update rates, geofencing, spoofing detection, external interrupts, SBAS/D-GPS, etc. All of this can be done within the SparkFun Arduino Library!

The SparkFun ZED-F9R GPS Breakout is also equipped with an on-board rechargeable battery that provides power to the RTC on the ZED-F9R. This reduces the time-to-first fix from a cold start (~24s) to a hot start (~2s). The battery will maintain RTC and GNSS orbit data without being connected to power for plenty of time.

Repository Contents
-------------------

* **/Documentation** - Data sheets, additional product information
* **/Hardware** - Eagle design files (.brd, .sch)
* **/Production** - Production panel files (.brd)

Documentation
--------------
* **[Library](https://github.com/sparkfun/SparkFun_u-blox_GNSS_Arduino_Library)** - Arduino library for the ZED-F9R.
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/1172)** - Basic hookup guide for the ZED-F9R.

Product Versions
----------------
* [GPS-16344](https://www.sparkfun.com/products/16344)

Version History
---------------
* [v1.0](https://github.com/sparkfun/SparkFun_GPS_Dead_Reckoning_ZED-F9R/releases/tag/v1.0) - Initial Release

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.

_<COLLABORATION CREDIT>_
