# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**

**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1464" height="1600" alt="WhatsApp Image 2026-09-12 at 9 14 33 PM" src="https://github.com/user-attachments/assets/92f1c1a8-562e-4cce-a7e3-ed7e9be2ee30" />
  **MODEL GRAPH:**
<img width="1600" height="568" alt="WhatsApp Image 2026-09-12 at 9 14 34 PM" src="https://github.com/user-attachments/assets/05bfc6ad-c563-468a-86f0-340046b62c6e" />

  **TABULATION:**
 <img width="1600" height="1284" alt="WhatsApp Image 2026-09-12 at 9 14 33 PM (1)" src="https://github.com/user-attachments/assets/879c7217-bde1-4290-a5c2-accd68238c06" />
u

**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**

<img width="1600" height="1186" alt="WhatsApp Image 2026-09-12 at 9 17 07 PM (1)" src="https://github.com/user-attachments/assets/b53f5f59-f1b2-4a53-b6c9-107226ac76d5" />

  **MODEL GRAPH:**
<img width="1600" height="923" alt="WhatsApp Image 2026-09-12 at 9 17 06 PM" src="https://github.com/user-attachments/assets/cc6c9a8d-480b-4c9e-a53e-93dd9fb1f8b6" />


  **TABULATION:**
<img width="1600" height="548" alt="WhatsApp Image 2026-09-12 at 9 17 07 PM" src="https://github.com/user-attachments/assets/7aeadb98-43bb-486b-92ca-9a9c1fff2f62" />

  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  **MODEL GRAPH:**
<img width="1482" height="1600" alt="WhatsApp Image 2026-09-12 at 9 18 49 PM" src="https://github.com/user-attachments/assets/ed62ca50-b49f-4e08-b3bc-416e637be4cb" />

  **TABULATION:**
<img width="1600" height="1005" alt="WhatsApp Image 2026-09-12 at 9 18 48 PM" src="https://github.com/user-attachments/assets/6df89275-a336-455b-8a6a-2d13a1eda25d" />

**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**
  <img width="1600" height="827" alt="WhatsApp Image 2026-09-05 at 8 02 02 AM (3)" src="https://github.com/user-attachments/assets/ad7ef2ca-4d65-453a-ad9c-04eb9fa620c7" />
<img width="1600" height="808" alt="WhatsApp Image 2026-09-05 at 8 02 03 AM (2)" src="https://github.com/user-attachments/assets/b3566139-b2bc-4faa-9fd5-d954b9c22273" />
<img width="1600" height="817" alt="WhatsApp Image 2026-09-05 at 8 01 36 AM" src="https://github.com/user-attachments/assets/d01c8519-4c93-4ad0-b062-b5d6e3190335" />


**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






