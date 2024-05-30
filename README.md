# Digital Circuits
This repository contains some basic circuits and implementations of experiments covering the fundamentals of digital logic and the design of digital systems using Tinkercad & Circuitverse. It also includes the implementations & solutions to some interesting real-life problems which involve the use of digital logic.

## Lab 1
1. [Verifying De-morgan's Theorem](https://www.tinkercad.com/things/2ix1efBCijO) 
(A + B)’ = A’ • B’ and (A •B)’ = A’ + B’.

2. [Constructing a Binary Half Adder using Gates ](https://www.tinkercad.com/things/1S3xlKnvGRu) 
A binary Half Adder adds two bits A and B to generate SUM and CARRY bits.  
SUM = A’ •B + A • B’ = A ⊕ B and CARRY = A •B.

3. [Constructing a Binary Full Subtractor using Gates](https://www.tinkercad.com/things/fAS6163doq4)  
A binary Full Subtractor subtracts the Subtrahend bit B and a Borrow-in bit Bin from the Minuend bit A to generate DIFFERENCE and BORROW bits as output.   
DIFFERENCE = A ⊕B ⊕ Bin and
BORROW (Bout) = A’ .B + (A⊕Β)’.Bin.

4. [Gemstone](https://www.tinkercad.com/things/fI0HpT71k48)  
A private collector has received a valuable gemstone which they wish to put on display. Due to its value, the collector has proposed an idea to prevent thieves from stealing the gemstone or escaping after attempting to steal it. The gemstone rests on top of a pressure plate on a pedestal, surrounded by a glass case. If glass is removed with weight intact or weight is removed from pressure plate with glass not removed a warning is issued. If the glass is broken and the gemstone’s weight is removed
from the pressure plate, the alarm is set on. Design the logic circuit required for this trap, modelling the glass case, pressure plateand steel barrier as follows:  
→ Glass case (input J): 0 – Glass not removed 1 – Glass removed  
→ Pressure plate (input K): 1 – Weight removed 0 – Weight applied  
→ Alarm (output X): 0 – Alarm off 1 – Alarm On  
→ Warning (output Y): 0 – Warning off 1 - Warning On

## Lab 2

1. Designing a [2x1](https://www.tinkercad.com/things/7KMekcnKwZ4), [4x1](https://www.tinkercad.com/things/8s8rvAxyum9) & [8x1](https://www.tinkercad.com/things/eZsHV4Mkvdq) Multiplexer
2. [Lock](https://www.tinkercad.com/things/7dxqmCkwKJf)  
A pound lock is used to raise and lower boats on rivers and canals. They consist of a pair of gates creating a chamber (lock) in which the water level is varied using valves.
To go upstream, the boat enters the drained lock through the bottom gate and the gate is closed behind it. The lock is then filled with water by opening the filling valve. Once full, the top gate is opened and the boat leaves. To go downstream, the boat enters the filled lock through the top gate and the gate is closed behind it. The lock is then drained by opening the drain valve. Once drained, the bottom gate is opened and the boat leaves. In both cases, the gates are controlled manually by a single lever. When the lever is not pulled, both gates should be closed. When pulled, it must open only the correct gate for the current water level. Hence, the top gate must only open if the lock is full, and the bottom gate must only open if the lock is drained. Design the logic circuit required for the lock controller, modelling the gate lever, valve
control and gates as follows:  
→ Gate lever(input J):  
0 – Closes both gates, 1 – Opens one gate depending on water level    
→ Valve control (input K):  
0 – Lock drained (drain valve open),  1 – Lock filled (filler valve open)  
→ Gates:  
0 – Gate closed (outputs X (bottom) and Y (top)) 1 – Gate opened

## Lab 3

1. [Designing a Programmable 1-bit Arithmetic and Logic Unit(ALU)](https://circuitverse.org/users/116991/projects/lab4_mux)
2. [Radioactive](https://www.tinkercad.com/things/59mL6o6nsF4)  
Spent fuel from nuclear reactors remains dangerously radioactive for long periods of time. This radiation must be contained. Spent fuel pools are often used to store the spent fuel underwater, because water cools the fuel down and blocks the radiation. Several conditions must be monitored and controlled to ensure that radioactive materials are not released into the environment. One facility monitors the radioactive concentrations of both the water in the pool and the air surrounding the pool. If both concentrations differ from normal levels, then the main alarm turns on, indicating a major problem. The water level of the pool is also monitored. If the water level drops below a certain threshold, or if only one of the concentrations differ from normal levels, then the minor alarm turns on.
Design the logic circuit required to turn the alarms on and off, modelling the radioactive concentrations, water level and alarms as follows:  
→ Radioactive concentrations (inputs J (water) and K (air))
0 – Same as normal level  
1 – Differs from normal level  
→ Water level (input L)  
0 – Above or at safe threshold  
1 – Below safe threshold  
→ Alarms (outputs X (main) and Y (minor))  
0 – Alarm on  
1 – Alarm off

3. [Ejector Seats](https://circuitverse.org/users/116991/projects/678935)  
Ejector seats are designed to rescue the crew of an aircraft during an emergency. To reduce the risk of injury to the occupants during ejection, several ejection modes are
available depending on the environmental conditions. For example, one ejector seat selects from three modes based on the orientation of the aircraft and the air pressure:  
• Mode 1 – Used while the aircraft is upright and air pressure is high  
• Mode 2 – Used while the aircraft is upright and air pressure is low  
• Mode 3 – Used while the aircraft is upside-down regardless of air pressure  
A condition sensor measures the orientation and air pressure and sends this information to a mode selector. The mode selector then selects the appropriate mode and activates
subsystems, such as rockets and parachutes, for that mode.
Design the logic circuit required to select the mode, modeling the orientation, air pressure and mode selector as follows:  
● Orientation (Input J)  
0 – Aircraft upright  
1 – Aircraft upside down  
● Air Pressure (Input K)  
0 – High pressure  
1 – Low pressure  
● MODES (output X,Y, Z)  
X at logic 1 – Mode 1  
Y at logic 1 – Mode 2  
Z at logic 1 – Mode 3  
(Other outputs in each mode are logic 0)

4. [Traffic Congestion](https://circuitverse.org/users/116991/projects/678935)  
A local council has received numerous reports of congestion occurring at a roundabout. In order to confirm these reports and determine the severity of the issue, a monitoring
system has been proposed to analyze traffic coming from the three entrances to the roundabout. At each entrance, a sensor has been set up to detect whether traffic is waiting at that entrance. A logging device is then activated when at least two of these sensors have been triggered, allowing the council to evaluate how often and how long traffic is waiting, and whether any improvements to the roads are required.
Design the logic circuit required for this congestion detection system, modeling the sensors and logging device as follows:  
● Sensors (Input J, K, L)  
0 – Entrance Clear (No traffic congestion)  
1 – Traffic Congestion  
● Logic Device (output X)  
0 – No congestion (Inactive)  
1 – Congestion Detected (Logging)

## Lab 4

1. [Encrypted Communication System](https://circuitverse.org/users/116991/projects/693539)  
Designing, assembling and testing a circuit for implementing an encrypted communication system that sends decimal digits encoded by a 4-bit binary code C3C2C1C0
according to the following scheme, where N denotes the value of the digit:  
For 4>=N>=0, C3C2C1C0 = 13 – N (in decimal)  
for 9>=N>=5, C3C2C1C0 = N – 3 (in decimal)  
Design a decoder for recovering the normal BCD representation (DCBA) of a decimal digit from its C3C2C1C0 representation.    

2. [Division](https://circuitverse.org/users/116991/projects/689603)  
Design a combinational circuit for dividing a 2-bit number N1 N0 by another 2-bit number D1 D0 and (D1 D0 is not equal to 0) to generate a 2-bit quotient Q1 Q0 and a 2-bit remainder R1 R0.

## Lab 5

1. [Latches](https://www.tinkercad.com/things/19XbmYBy8A3-lab7/editel?sharecode=LFBA3NWp8AJvSNIn3MPHEfrasqKcHwKAfxjnRZLxgw8)  
Latches have a feedback path and it can be a memory device. Latch can store one bit of data as long as the device is powered. It is an important element for sequential circuit design. Latches are asynchronous and do not operate on clocks, hence its state changes with the change in inputs. Here I have implemented a NOR and a NAND Latch.

## Lab 6

1. [Flip-Flops](https://www.tinkercad.com/things/2KlCKzN7BsJ-lab8/editel?sharecode=-HvFvxppp3aDUeuRL7F25hKRgC64hMWhPenlFeac6Kk)  
Flip flops have memory and constitute an important element of a sequential circuit. Flip-flops have clock input which makes them synchronous. They are edge-triggered devices as the output of a flip-flop can only change at the positive or negative edge of the clock. Here I have implemented a J-K Flip-flop & a D-Flip-flop.  

## Lab 7

1. [Binary Ripple Counter](https://www.tinkercad.com/things/gOsvlYuo1CI-lab9a-upcounter/editel?sharecode=mcc4-WswMf672ZR4XIOMR9j7XvK9h7UiMWBIgrAW9KE)  
A binary counter is required to count in the binary number sequence – either in the increasing order (UP counting) or in the decreasing order (DOWN counting). A ripple
counter consists of T flip-flops with T = 1 connected in cascade.

2. [Decade Ripple Counter](https://www.tinkercad.com/things/kpxgTM5LYtQ-copy-of-lab9a-upcounter/editel?sharecode=7D1Wo_gdAy1Q72IcV086O1QZppgdTUGt8D0Q_zh8jpY)
A decade counter has the count sequence 0→1→2→.....→8→9→0.., which can be achieved by making Reset = (Q3∙Q1)’ for all the flip-flops in a 4-bit binary counter. This
forces the state to become 0000 as soon as the counter makes the transition to the state1010 from the state 1001 according to the normal UP counting sequence.





