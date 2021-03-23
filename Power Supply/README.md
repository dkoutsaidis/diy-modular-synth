# Power Supply
Eurorack defines a common power supply and power connector:
- A 10- or 16-pin ribbon cable supplying a dual rail ±12v DC power supply.
- Power connectors can also include a +5V DC power supply, CV and Gate buses.

A classic linear power supply was designed and built for the ±12V. Schematics will be available soon. A [simple DC-to-DC converter](https://www.cableworks.gr/ilektronika/arduino-and-microcontrollers/buck-and-boost-converters/buck-converter-step-down-dc-dc/lm2596-340v-dc-dc-buck-adjustable-converter-step-down-module-for-arduino/) was bought for the +5V.

Generally speaking, linear supplies are quieter in terms of audio noise and use fewer parts, while switching power supplies can cause EMI and aliasing, even though it’s in the megahertz range. Practically, switching power supplies are commonly used because of their lower cost, higher wattage, and comparative immunity to sag. The potential noise issues are mostly minimized and of only small concern. Some audiophiles will spec out linear power supplies, multiple internal supplies, or even substantial external ones to maximize fidelity. They may have their oscillators and filters, their audio path, grouped together on one power supply, while clocking modules would be on a completely separate power supply, and digital modules or 5V-heavy modules on their own supply. It’s power isolation at its finest!

### System Bus
#### Schematic
<img width="1113" alt="Screenshot 2021-03-24 at 1 36 35 AM" src="https://user-images.githubusercontent.com/24361657/112232607-8cec6e80-8c41-11eb-8bc4-ed238d8ed23a.png">

### PCB Dimensions
<img width="1250" alt="Screenshot 2021-03-24 at 1 36 23 AM" src="https://user-images.githubusercontent.com/24361657/112232651-9bd32100-8c41-11eb-8110-9ae15770825d.png">
