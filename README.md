# birthday cake PCB
Slack User: Vincent

With birthdays always coming around the corner, it's always hard to gift something that feels like it's truly from you. In this project, I tried to solve that issue by designing a PCB that could be given as a birthday gift. It's in the shape of a birthday cake, accordingly, and has a decorative silkscreen, including a party popper and "Happy Birthday" text. On the electronics side, there are two circuits going on: a continuously "on" LED (candle) and a pair of alternating LEDs (decorative fruits?). For the alternating LEDs, given the provided components, I opted for an astable multivibrator circuit, which uses NPN transistors, capacitors, and some resistors to create two asynchronous outputs. Those outputs are directly connected to the pair of LEDs to generate a flashing effect. 

## Bill of materials
*resistor 47k ohm (2x)\
resistor 220 ohm (3x)\
LED (3x)\
2N3904 transistors (2x)\
10uF capacitors (2x)\
CR2032 battery cell (1x)*

**PCB Design Photos:**
![image](https://github.com/user-attachments/assets/c8e7c925-b67c-4b79-bf9f-9a38ab4ba0a0)
![image](https://github.com/user-attachments/assets/aa57932c-3778-43a8-aa95-58f858be8962)
![image](https://github.com/user-attachments/assets/6e665076-5a25-4d51-8a6a-6ec7463f2e04)


