# High-Performance-Binary-to-Gray-CodeConverter-using-Transmission-GATE
# Abstract
The circuit gives an idea to improve power efficiency and effective area of binary to gray code converter using very popular transmission gate technology. Some sensors send information in gray code. So this must be important to convert a given binary stream into its equivalent gray code. In this paper the binary to gray code converter has been developed using gate, circuit level. The conversion has beendone using conventional and transmission gate level and comparing these two in terms of power, number of transistors used and last but not the least area. The simulation result shows that binary to gray code converter using transmission gate has improved power efficiency and area by 76.22% and 72.3% respectively.
# INTRODUCTION
Low power and area efficient technologies are the primeconcern for VLSI system designers. Together with that, the high speed binary to gray code converter that use low power consumption have indisputably become one of the most crucial components of a processor because they are mostly used in arithmetic logic unit.

Second term of consideration for designing of low power area efficient binary to gray code converter is delay which affects the overall performance of circuit to be concern.The extensive development in the field of portable system and cellular network has intensified the research efforts in low power micro-electronics. This paper concern with 3XOR gate as one unit which is the basic building block in various circuit especially arithmetic circuit .Here we propose a new design of XOR gate using transmission gate with CMOS inverter circuit. It cover less area compared to 12 transistor X-OR with CMOS circuit as well as less power with smaller delay.The strength of a signal is measured by how closely it approximates an ideal voltagesource.Transmission gates require lower switching energy and it reduces the count of transistors used to make different logic gates.In VLSI implementation, major problems are heat dissipation and power consumption. To solve this problem it is required to reduce power supply voltage, switching frequency and capacitance of transistor. Area, delay and power dissipation have emerged as the major concern of the designers. The performance of the complex logiccircuits is affected by XNOR-XOR circuits.To summarize, this paper focused on some of the performance criteria are considered in the designing and evaluation of this converter cells while some are utilized for the ease of design, robustness, silicon area, delay and last but not the least power consumption.The technology used in this paper i.e. Transmission gate use less area and less transistors compare with conventional design logic.
# Binary to Gray code converter
This code converter combinational circuit is designed to convert binary to gray code. The input code of code converter is binary and output code of code converter is gray code.
- Truth table of 4-bit Binary to Gray code converter:
  ![image](https://user-images.githubusercontent.com/100506744/156110599-81adddac-7166-4304-bfbe-089dfbf0ca1a.png)

- Logic circuit design of binary to gray code converter:

  ![image](https://user-images.githubusercontent.com/100506744/156110733-a0a9c00c-3928-4e84-ae7b-4d47ba2fb7c6.png)

- CMOS implementation using transmission gates:
 
   ![image](https://user-images.githubusercontent.com/100506744/156111650-180ad7ce-bf1f-47b6-8364-524a4fe15e67.png)

# Tools Used:
- Synopsys Custom Compiler:  The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.
- Synopsys Primewave:  PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.
- Synopsys 28nm PDK:  The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.
# DEsign Approach
- 2 bit XOR Gate:
  
- 4-bit Binay to gray Converter using above XOR Gate:
  
 
