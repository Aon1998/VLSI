# VLSI
GE characterization team
Despite the fact that Electrical and Comoputer engineering considered one of the most broad and complex specialty,out of all majors the VLSI will be explained in this repsitory, in order to understand it in an effecient way, it will be splitted into 3 main sections:
1) overview of the whole VLSI desgin flow
2) Since we will focus on the standard library design -semi custom-, the CMOS will be explained briefly
3) specialize in library generation


Thanks for A2A.Let me share my own love story with VLSI which started 3 years ago. Our relationship has come a long way & I know a bit more of her each day. The journey has made me understand both the breadth & depth of the subject. Its a very very vast field with a lot of interdependent & co-related topics [RTL design, Functional/Physical/Timing Verification, Testing, DFT, Synthesis, Physical Design, Standard cell design etc. to name a few]. You cannot master it quickly. Your understanding of the subject will get better with time & persistent effort. But, most importantly with the curiosity to know more & more of her. I have enumerated the basic things you must know to succeed in the field of ASIC (not FPGA)/SoC design. Just follow it & you will surely have a strong foundation to be a successful VLSI Engineer.

1. Logic Design (LD)
Yes, this by far is the single most important skill you must possess. Programming is a mere implementation of your idea but LD is the thinking process itself. You must be able to design a module using min. Gates, min. Power & max. Performance. This step comes higher in the design hierarchy and affects the entire flow from there on. So its really important to get your LD concepts bang on. Ex: FSM design, MUX based design, Flops-latches based design, Sync.-Aysnc design.
How to learn: Take an interesting problem statement, come up with an optimized FSM design & try to implement the same using min. resources at the gate-level.

2. HDL/RTL/HVL Coding
Yes yes, the industry needs you to code & code well. There is a difference between RTL coding & C-coding. Here, 'timing' comes into play. You must learn to code in either Verilog/VHDL (I learnt Verilog). With RTL, you are basically expressing the LD you came up with in 1 using a Hardware language.
How to learn: Start coding simple modules straight away. Don't waste time trying to master the syntax. Learn to express the module behavior in RTL & the compiler will teach you the rest. Start writing simple testbenches to verify for its logic/functional correctness. Then later learn Synthesizable RTL Coding.
Note: One step further would be learning SV, UVM, RAL, SVA etc to write fully automated TBs. This is a vast field in itself. I was in FV at LSI & found it interesting. If you like coding then this is for you.

3. CMOS fundamentals
It depends whether you will work on frontend design or backend design. This is highly needed in Backend/Physical design & full-custom circuit design/standard cell design. But having good MOS basics is always a bonus. It a must need for all R&D jobs.
How to learn: Start designing a simple circuit like SRAM/DRAM block & verify its timing & functional correctness using SPICE simulations. I have done the same.

4. EDA Tools
Now this is a must for all industry jobs.Since almost the entire VLSI flow is automated using EDA tools, its a must to gain expertise in handling them. I have learnt Cadence Virtuoso, Synopsys ICC, DC, PT etc. It's a must for almost all Backend jobs.
How to learn: The tools are expensive. You college will provide you if it's part of the syllabus. But if you are lucky to get an internship in a semiconductor company then its even better.

5. Computer Architecture/ Microprocessor basics
Almost all chips designed today are ASICs/SoCs. This means we must understand how the CPU is organized & how the various parts work together. You will ultimately end up working on just a single block withing the CPU but having knowledge of many blocks will help you to better understand the chip & eases integration job.
How to learn: First learn the basic theory. Then try to design & implement a single CPU component ex: ALU or a DMA controller. Take it through the entire flow from RTL->Netlist->PD.

6. Protocol/Algorithm implementation
VLSI is just an implementation technology. Ultimately you are designing a chip for a specific application ex: Image processors, Networking processors, wireless chips etc. So it becomes important to understand the common on-chip protocols & implement the same on hardware like FPGA
How to learn: Take a simple crypto algorithm ex: RC6 & implement the same on FPGA.
Note: One step ahead would be learning AMBA Protocols like AHB,APB,AXI etc.

7. Timing Analysis
TA forms the pillars of VLSI. Its important to undertand clocks, Metastability, STA & analysing a circuit for setup & hold violations and ways to fix the same.
How to learn: Learn STA theory first. I have worked on STA in the backend flow. You can do the same. Synopsys PT/ICC is needed to generate timing reports, analyse them & later fix those violations.

8. Scripting & UNIX basics
Scripts are written to automate routine tasks. Its needed in both Frontend & Backend flow.
In frontend flow we predominantly use Perl scripting for regression testing, register verification etc. In backend we use Tcl scripting to execute various commands for PD. Learn baisc UNIX commands.
How to learn: There are numerous online tutorials to learn. Start writing simple scripts to execute routine tasks. Leave Windows and start using UNIX. You must know the UNIX environment well.

There is so much to cover but I am tired of typing. So PM me to know more.
