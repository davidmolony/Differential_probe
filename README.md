# Differential_probe
Differential probe, 4 channel for motor control (e.g. IGBT inverters). This is an alternative to using expensive and unobtainable isolation amplifiers.

Be careful. High voltage is dangerous, You are on your own. You take responsibility for yourself and any consequences entirely.

Untested 18/01/2023, on order. 

If you are planning on attaching this to high voltage, 
use UL rated 3kV resistors e.g. Bourns CHV2512-FX-1004ELF and ensure you do not breach the resistor pseudo isolation barrier.
Ground the low voltage side if possible. DO NOT put only capacitors to ground, as this could result in the 1Mohm charging them to mid rail voltage.

The ones specified for JLCPCB are not safety rated, they are for prototyping or non safety or low voltage application.