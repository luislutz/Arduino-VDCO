# Arduino-VDCO
Voltage Controlled Digital Core Multimode Oscillator using Mozzi library on Arduino

Its a digital Oscillator/Voice for the Eurorack Standart, its based on three different modules from HAGIWO Modular, merged into one small 4HP Module, with added CV input too choose the Synthesis Mode. The Modes are FM Synthesis, Additive Synthesis and a Chord generator with lots of waveforms! Ive alse implemented a simple digital VCA with a Gain CV input which is normalled to 5 Volts, so it can be used as VCO+VCA. little Bonus: It gets in the digital clipping range when the voltage on the gain input exceeds 5 Volts!
It has V/Oct pitch tracking and CV inputs for all Parameters. The Sketch uses about 95% of the Memory on an Arduino Nano :)

