Written by Jake Hansen, January 2020

This project is still under development, but in its current state it simulates
a child going down a slide. To run it, you need a linux device
with pybluez / bluez installed to run the "beaconMaster.py" file in the Scripts
folder. Then, you need two iBeacons within range of the linux device. set the
UUID to '636f3f8f-6491-4bee-95f7-d8cc64a863b5' and choose any two distinct
values for the minor variable. The first one simulates the person starting at
the top of a slide, and the second one will end the timing for it.

setting up iBeacon: - http://www.wadewegner.com/2014/05/create-an-ibeacon-transmitter-with-the-raspberry-pi/
(or you can download an app and do it on your phone)

Still to do:

-Connect to Database
-Create model for determining location of "wristband" based on multiple beacon RSSI values, from data set found in citation from western Michigan













Dependencies:

pip install psycopg2
pip install configparser
Linux operating system with bluetooth capabilites and Bluez installed
create Database, host it, connect in in database.ini file in Database folder

Citations:
@article{mohammadi2017semi,
author={M. Mohammadi and A. Al-Fuqaha and M. Guizani and J. S. Oh},
journal={IEEE Internet of Things Journal},
title={{Semi-supervised Deep Reinforcement Learning in Support of IoT and Smart City Services}},
year={2017},
pages={1-12},
publisher={IEEE},
doi={10.1109/JIOT.2017.2712560},
ISSN={2327-4662},
}
