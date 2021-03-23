# SND/RTN - AISynthesis
A simple send/return module for IO with external guitar pedals ([link](https://aisynthesis.com/how-to-build-ai006-eurorack-send-return-module/)).

Next, there are some voltage-conversion-related useful info:

### Line Level
detailed info [here](https://en.wikipedia.org/wiki/Line_level)
| Use |	Nominal level	| Nominal level, VRMS |	Peak amplitude, VPK	| Peak-to-peak amplitude, VPP |
| --- | --- | --- | --- | --- |
| Professional | +4 dBu	| 1.228	| 1.736	| 3.472 |
| Consumer | −10 dBV | 0.316 |	0.447	| 0.894 |

### Microphone Level
We could roughly say that the microphone level is in the region of  -60dBV (0.001 volt) to -40dBV (0.010 volt).  

### Instrument Level
Electric guitars/basses supposedly put out around 0.15 to 0.5 volts p-p AC (some hotter humbucker guitars can put out over 1V p-p) and pedals can boost this quite a bit. The max theoretical output of any pedal is the available supply voltage (usually 9V p-p).  In reality, you hardly ever see this much because most devices don't operate rail-to-rail (some opamps do though). Generally, there is no safe limit on the output of a pedal.

### dBV / dB(VRMS)
Voltage relative to 1 volt, regardless of the impedance. This is used to measure microphone sensitivity, 
and also to specify the consumer line-level of −10 dBV, in order to reduce manufacturing costs relative to 
equipment using a +4 dBu line-level signal.

### dBu / dBv
RMS voltage relative to V=0.7746 (i.e. the voltage that would dissipate 1 mW into a 600Ω load). 
An RMS voltage of 1 V therefore corresponds to 2.218dBu.
