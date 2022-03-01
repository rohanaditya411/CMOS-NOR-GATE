# CMOS-NOR-GATE
This repository contains the design of 2-input nor gate using pMOS and nMOS and implemented using synopsys custom complier on 28nm cmos technology.
# TABLE OF CONTENT

1. [Reference circuit details](https://github.com/rohanaditya411/CMOS-NOR-GATE/blob/main/README.md#reference-circuit-details)</br>
2. [Reference circuit diagram](https://github.com/rohanaditya411/CMOS-NOR-GATE/blob/main/README.md#reference-circuit-digram)</br>
3. [Reference circuit waveform](https://github.com/rohanaditya411/CMOS-NOR-GATE/blob/main/README.md#reference-circuit-waveform)</br>
4. [Truth table](https://github.com/rohanaditya411/CMOS-NOR-GATE/blob/main/README.md#truth-table)</br>
5. [Tools used](https://github.com/rohanaditya411/CMOS-NOR-GATE/blob/main/README.md#tools-used)</br>
6. [Simulation In Synopsys](https://github.com/rohanaditya411/CMOS-NOR-GATE/blob/main/README.md#simulation-in-synopsys)</br>
   -  [Schematic Diagram Of NOR Gate](https://github.com/rohanaditya411/CMOS-NOR-GATE/blob/main/README.md#schematic-diagram-of-nor-gate)</br>
   - [Symbol of NOR Gate](https://github.com/rohanaditya411/CMOS-NOR-GATE/blob/main/README.md#symbol-of-nor-gate)</br>
   - [Output Waveform](https://github.com/rohanaditya411/CMOS-NOR-GATE/blob/main/README.md#output-waveform)</br>
   - [Netlist](https://github.com/rohanaditya411/CMOS-NOR-GATE/blob/main/README.md#netlist)</br>
7. [Conclusion](https://github.com/rohanaditya411/CMOS-NOR-GATE/blob/main/README.md#conclusion)</br>
8. [Author]()</br>
9. [Acknowledgement](https://github.com/rohanaditya411/CMOS-NOR-GATE/blob/main/README.md#acknowledgement)</br>
10. [References](https://github.com/rohanaditya411/CMOS-NOR-GATE/blob/main/README.md#references)</br>
# REFERENCE CIRCUIT DETAILS

To design a 2-input CMOS, two pMOS are connected in series and two
nMOS are connected in parallel.</br>
When the input, A = 0 and B = 0 both nMOS transistors are OFF and
both pMOS transistors are ON. Hence, the output is
connected to VDD and we get logic high at the output.</br>
 When the input, A = 1 and B = 0 the upper pMOS is OFF and lower
pMOS is ON. So, output cannot be connected to the VDD
Under this condition, left nMOS is ON and right nMOS is
OFF. Hence, the output is connected to the ground and we
get logic low at the output.</br>
When the input, A = 0 and B = 1, the upper pMOS is ON and lower
pMOS is OFF. So, output cannot be connected to VDD. Under
this condition, left nMOS is OFF and right nMOS is ON.
Hence, the output is connected to the ground and we get
logic low at the output.</br>
When the input, A = 1 and B = 1, both nMOS transistors are ON and
both pMOS transistors are OFF. Hence, the output is
connected to VDD and we get logic low at the output. This
proves the truth table of NOR gate.</br> 

# REFERENCE CIRCUIT DIGRAM

![image](https://user-images.githubusercontent.com/100359672/155544322-f8d1c05b-d9ce-4145-8b5f-02988efcc8a7.png)


# REFERENCE CIRCUIT WAVEFORM
![ee7a4915-32a7-4187-90c5-6e71686a29e6](https://user-images.githubusercontent.com/100359672/155647645-84865a5a-7788-40b9-a1c8-487119d7a5ec.jpg)

# TRUTH TABLE

![rohan pdf - Adobe Acrobat Pro DC (32-bit) 24-02-2022 20_05_18 (2)](https://user-images.githubusercontent.com/100359672/155544981-ee5535a9-67af-4a46-a8d5-287a546da467.png)

# TOOLS USED
## 1. Synopsys Custom Compiler:  
The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.</br>
## 2. Synopsys Primewave: 
PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.</br>
## 3. Synopsys 28nm PDK:  
The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.</br>

# SIMULATION IN SYNOPSYS

## SCHEMATIC DIAGRAM OF NOR GATE

![139 59 246 100 - Google Chrome 24-02-2022 20_24_36 (2)](https://user-images.githubusercontent.com/100359672/155564256-b61fe868-4250-4d21-89ca-4414d22f1472.png)

## SYMBOL OF NOR GATE
![139 59 246 100 - Google Chrome 25-02-2022 09_11_52 (2)](https://user-images.githubusercontent.com/100359672/155649522-63d1646c-3545-466d-a11d-5222c116f256.png)

## OUTPUT WAVEFORM
![139 59 246 100 - Google Chrome 24-02-2022 23_08_44 (2)](https://user-images.githubusercontent.com/100359672/155649757-5d131e44-5566-404e-9a41-a2b3e4b188ef.png)

## NETLIST
for Netlist of circuit click here [NETLIST.txt](https://github.com/rohanaditya411/CMOS-NOR-GATE/files/8147858/NETLIST.txt)


## CONCLUSION
We have designed and implemented the 2-input nor gate using synopsys custom complier on 28nm cmos technology and we observed that when both the input is zero then only output is one.
## ACKNOWLEDGEMENT
1.Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd. </br>
2.Chinmay panda, IIT Hyderabad </br>
3.Sameer Durgoji, NIT Karnataka </br>
4.VLSI System Design(VSD) Corp. Pvt. Ltd. India  </br>
5.Synopsys Team </br>
## REFERENCES
[1] CMOS Digital integrated circuits, analysis and design, by
Sung-Mo kang/ Yusuf Leblebici</br>
[2] https://www.allaboutcircuits.com/textbook/digital/chpt-3/cmos-gate-circuitry/





