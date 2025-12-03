# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.
## AC INPUT WAVEFORM:

![WhatsApp Image 2025-11-29 at 19 00 04_0cb9141c](https://github.com/user-attachments/assets/70223808-7ee5-4da2-b6c1-6171a20208f6)

## OUTPUT GRAPH:
## SIGNAL OUTPUT(WITHOUT FILTER)
![WhatsApp Image 2025-11-29 at 19 00 05_6d41035d](https://github.com/user-attachments/assets/41bc93c8-3940-4fa5-a221-2c2c4fef55d6)

## SIGNAL OUTPUT(WITH FILTER)
![WhatsApp Image 2025-11-29 at 19 00 05_3ca86c8c](https://github.com/user-attachments/assets/1a7635bc-0cf0-410a-9b79-7483e7d14603)



## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
