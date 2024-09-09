# Treadmill-Interface
 Treadmill Interface 
Provides an interface to a treadmill that uses an incremental encoder to monitor speed and distance.
The speed and distance are calculated at each increment of the encoder. Time, speed, and distance are sent out a serial-USB port. The minimum time between readinsg can be set, as well as the time to wait to set zero speed.
The absolute value of speed is also sent out to an SMA connector as an analog signal. Direction is sent out another SMA connector as a 3.3V digital signal. 
The design utilizes a Teensy 4.0.
The encoder voltage provided is 5 volts.

PCB design done in Eagle
Firmware design in Arduino with Teensy extensions
Processor - Teensy 4.0
