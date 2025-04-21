# Nicholas's 1-Bit Logic Gate Computer
A 1-bit computer built by Nicholas (My first PCB!) (@Nicholas1023 on the Hack Club Slack) that uses AND and NOT gates as its processor, Push buttons as input, and LEDs as output.
## 3D View
![3D View](https://raw.githubusercontent.com/Nicholas1023/computer/refs/heads/main/3D_View.png)<br>**Board size: 53.55x49.05 mm**<br>**Note:** The processor symbol next to the transistors is not a component.
## PCB Layout
![PCB Layout](https://raw.githubusercontent.com/Nicholas1023/computer/refs/heads/main/PCB.png)
## Schematic
![Schematic](https://raw.githubusercontent.com/Nicholas1023/computer/refs/heads/main/Schematic.png)
## Bill of Materials
|Qty|Ref. Designator |Name                 |Mounting Type|
|:-:|:---------------|:--------------------|:------------|
|1  |BT1             |CR2032 Battery holder|SMD          |
|1  |R1              |Resistor             |THT          |
|1  |J1 (IO Pins)    |1x04 2.54mm Connector|THT          |
|3  |D1, D2, D3 (LED)|5mm LED              |THT          |
|3  |SW1, SW2, SW3   |6mm Push button      |THT          |
|3  |Q1, Q2, Q3      |2N3904 NPN Transistor|THT          |
## Pinout
GND: Ground<br>+3V: Power (3V)<br>AND: AND Output<br>NOT: NOT Output<br>
**Warning:** To avoid damaging the components, do not insert CR2032 battery when the GND and +3V pins are connected.
