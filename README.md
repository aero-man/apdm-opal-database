# APDM Opal Sensor Database
### Using APDM Python SDK

### About
This tool streams data from APDM Opal wearable, wireless sensors to a SQLite database or CSV. APDM Opal sensors are radio-frequency sensors with an on-board inertial measurement unit (IMU). This tool records the gyroscope, accelerometer, and magnetometer data from these sensors.

### Getting Started
Please refer to `Getting_Started_Mac.md` in this repository to set up your computer and the APDM sensors to start streaming. Only setup documentation for MacOS is available. For Windows, refer to APDM's official SDK documentation.

### What you need
* 1+ APDM Opal sensors
* 1+ APDM access point (1 access point can keep track of up to 6 sensors)
* [APDM Python SDK](http://share.apdm.com/libraries/release/apdm_sdk.zip)
* Python 2.7
* The `docopt` Python module (`pip install docopt`)

### Why Python 2.7 instead of 3?
APDM's Python SDK does not work with Python 3.

### Contacts
* Andrew Roman <aeroman2@asu.edu>  

