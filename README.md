# High-Performance-Binary-to-Gray-CodeConverter-using-Transmission-GATE
# Table of content
- [Abstract]()
- [INTRODUCTION]()
- [Binary to Gray code converter]()
- [Tools Used]()
- [Design Approach]()
- [Author]()
- [Acknowledgements]()
- [References]()
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
# Design Approach

- 2 bit XOR Gate:

![image](https://user-images.githubusercontent.com/100506744/156144062-8af176b9-a8dd-4e3a-b934-4a0dc3edf518.png)
  
- 4-bit Binay to gray Converter using above XOR Gate:

![image](https://user-images.githubusercontent.com/100506744/156144235-49ff4f7e-902d-4ded-8b98-92fc795847f1.png)

- TRANSIENT ANALYSIS
 
 ![image](https://user-images.githubusercontent.com/100506744/156144362-a049877e-b0e3-426c-83a3-aa8d522329fa.png)

- Final WAVEFORM of 4-bit Binary to Gray Conerter:
 
 ![image](https://user-images.githubusercontent.com/100506744/156145083-825ca648-be90-4887-8af5-6f126ad5867d.png)

 # Author
- Ashutosh Kumar, B.Tech Electronics and Communication Engineering, J.C. Bose University of Science and Technology,YMCA.
# Acknowledgements
- [Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/)
- [Cloud Based Analog IC Design Hackathon](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/')
- [Synopsys India](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/')
- [Sameer Durgoji, NIT Karnataka](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/')
- [Chinmay panda, IIT Hyderabad](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/')
# References
- V.Kamalakannan, Shilpakala.V, Ravi.H.N, “Design ofAdder/Subtractor Circuits Based on Reversible Gates”, InternationalJournal of Advanced Research in Electrical Electronics AndInstrumentation Engineering, Vol 2, issue 8,pp.3796-3804, 2013.
- PushpaSaini, Rajesh Mehra:“A Novel Technique for Glitch andLeakage PowerReduction in CMOS VLSI Circuits”, InternationalJournal of Advanced Computer Science and Applications, Vol. 3, No.10,pp.161-168 2013
- Zhanfeng Zhang, Liyuan Sheng, Wenming Jiang, Shuai Tong, HuaCao, “A New Adder Theory Based on Half Adder andImplementation in CMOS Gates”, I.J. Image, Graphics and SignalProcessing, pp.11-17 2012.
- I. Hassoune, D. Flandre, I. O’Connor and J.D.Legat:ULPFA: ANewEfficient Design of A Power Aware Full Adder”, IEEE Transactionson Circuits and Systems I-5438,pp.2066-2074, 2008.
