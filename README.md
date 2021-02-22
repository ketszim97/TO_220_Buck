# TO_220_Buck
A buck converter drop in replacement for TO-220 LDOs

There are currently two versions:
- One for [78xx series LDOs](https://github.com/ketszim97/TO_220_Buck/tree/78xx)
- One for the [LM1117 LDO](https://github.com/ketszim97/TO_220_Buck/tree/LM1117)

They are both configured for 3.3V, but replacing R3 allows the output voltage to be set. 

|Output Voltage     |  R3 Value     |
| :---------------: | :-----------: |
| 1.5V              | 86k6          |
| 1.8V              | 60k4          |
| 2.5V              | 35k7          |
| 3.3V              | 24k3          |
| 5.0V              | 14k3          |
| 12V               | 5k36          |
| 24V               | 2k61          |


Please take note of the pinouts as seen in the renders. 

I've been able to test basic functionality of both boards, but I am currently working on extended testing.

# [LM1117 Version](https://github.com/ketszim97/TO_220_Buck/tree/LM1117)
![Fusion Render 1](https://github.com/ketszim97/TO_220_Buck/blob/main/Renders/R1.png)
![Fusion Render 2](https://github.com/ketszim97/TO_220_Buck/blob/main/Renders/R2.png)
![Fusion Render 2](https://github.com/ketszim97/TO_220_Buck/blob/main/Renders/R2.png)

# [78xx Version](https://github.com/ketszim97/TO_220_Buck/tree/78xx)
![Fusion Render 1](https://github.com/ketszim97/TO_220_Buck/blob/main/Renders/78xxR1.png)
![Fusion Render 2](https://github.com/ketszim97/TO_220_Buck/blob/main/Renders/78xxR2.png)
