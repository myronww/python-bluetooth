# python-bluetooth
This repository contains example bluetooth services that implement the BlueZ interfaces below:

* org.bluez.Agent1
* org.bluez.Profile1

The 'bluetooth_pin_agent' service implements the 'org.bluez.Agent1' interface and establishes ssp mode 0 during startup so as to enable bluetooth the legacy PIN based authentication mechanism.

The 'bluetooth_serial_service' service implements the 'org.bluez.Profile1' interface to declare a RFCOMM serial endpoint bound to bluetooth channel 4.

# Testing

Platform           Linux                Bluetooth/BlueZ Ver            Paired With   
-------------------------------------------------------------------------------------
AMD64 Desktop      Ubuntu 18.04         5.48-0ubuntu3.1                 Android
NanoPiNeoAir       Ubuntu 16.04         5.37-0ubuntu5.1                 Android
