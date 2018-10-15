# 3v-pwm-controller
An Arduino M0 PWM controller with 3 mosfets designed to perform PWM on 3V or 5V with a 3A 3V supply

This PWM controller provides 3 PWM channels designed to sink current.
Due to the back EMF protection diodes, do not exceed 5v.

The 3V supply is capable of providing up to 3A of current and is designed
to be powered by a 5V supply.

Each PWM channel should be able to handle at least 3A of current at up to 5V.
The MOSFETs are rated at over 8A each.

J1:
1: +5V
2: +5V
3: PWM0 connected to PA00
4: PA08
5: PWM1 connected to PA01
6: PA09
7: PWM2 connected to PA02
8: PA10
9: +3V
10: +3V
11: GND
12: GND

J2:
1: D_P (D+) USB signal
2: D_N (D-) USB signal
3: PA22
4: PA21
5: PA19
6: PA18
7: +3V
8: GND

J3:
1: +5V
2: GND

SW1: Reset
