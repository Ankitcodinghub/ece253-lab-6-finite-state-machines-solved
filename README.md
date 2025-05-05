# ece253-lab-6-finite-state-machines-solved
**TO GET THIS SOLUTION VISIT:** [ECE253 Lab 6-Finite State Machines Solved](https://www.ankitcodinghub.com/product/ece253-lab-6-finite-state-machines-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94368&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE253 Lab 6-Finite State Machines&nbsp;Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Laboratory Exercise 6

Finite State Machines

The purpose of this lab is to:

1. learn how to write Finite State Machines (FSMs) in Verilog

2. learn how to use an FSM to control the sequencing of logical operations.

1 Workflow

For each part of the lab you should begin by writing and testing Verilog code and compiling it with Quartus. You should be prepared to show schematics, Verilog, and simulations to your TA, if requested. You must simulate your circuit with ModelSim using reasonable test vectors written in the format used in Lab 2 for the simulation files.

For Parts I and II, you are given a lot of code in the form of templates. This provides you with some good examples to use as models for your own code, but they also allow you to focus on the key elements relevant to building the required control sequences without having to write the supporting infrastructure. The amount of code you need to write in these parts is relatively small. Most likely, more of your time will be spent understanding all of the code presented to you and how to modify it.

2 Test Plans: Getting More from Your Simulations

As the complexity of the circuits you build increases, the importance of simulation also increases. Thinking about how you are going to test your circuit is an integral part of doing a design. Without thinking about testing as you do your design, it is possible that you will build a circuit that you cannot properly test, or it will be extremely difficult to test. While the circuits you build for these lab exercises are still basic and straightforward, the goal at this time is for you to start thinking more about how you will do your testing.

Here are the steps you should do. Be prepared to discuss your Test Plans with your TA if requested.

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol>
<li>Write out a Test Plan. The Test Plan lists everything you want to test to show your circuit is working, how you are going to do the test, and the correct result to expect. For example, if you are going to test a 4-bit adder, your test plan might look like:
Test carry in = 0 Add 0000 + 1111 with carry in of 0. Expected output = 1111, carry out = 0;

Test carry in = 1 Add 0000 + 1111 with carry in of 1. Expected output = 0000, carry out = 1;

And so on Other tests …
</li>
<li>As you execute each test, you can document the behaviour of a test by annotating a
screen capture of the waveforms to show the inputs and the outputs.
</li>
<li>If something is not working, indicate the inputs, but then show in the simulation where it is not doing what you expect. This is important if you want to discuss the issue with a TA, or your manager if you are working.</li>
</ol>
The goal of doing the above is to make you think more about the purpose of simulation and how to get the most out of doing simulation.

3 PartI

In this part you will implement a basic finite state machine (FSM) in Verilog. All FSMs you write in Verilog should follow this structure or you can get into lots of trouble.

We wish to implement a FSM that recognizes two specific sequences of applied input symbols, namely four consecutive 1s or the sequence 1101. There is an input w and an output z. Whenever w = 1 for four consecutive clock pulses, or when the sequence 1101 appears on w across four consecutive clock pulses, the value of z has to be 1; otherwise, z = 0. Overlapping sequences are allowed, so that if w = 1 for five consecutive clock pulses the output z will be equal to 1 after the fourth and fifth pulses. Figure 1 illustrates the required relationship between w and z for an example input sequence. A state diagram for this FSM is shown in Figure 2.

Figure 3 shows a partial Verilog file for the required state machine. It is the template code in part1_template.v that you will need to complete for this part. Study and understand this code as it provides a model for how to clearly describe a finite state machine that will both simulate and synthesize properly.

Note that the top-level module of the template has the following signature description:

<pre>                module part1(Clock, Resetn, w, z, CurState);
</pre>
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
!”#$%&amp;

‘&amp;

(&amp;

Figure 1: Required timing for the output z.

This circuit uses a synchronous reset called Resetn. The input of the sequence detector is w

and the output is z. The current state of the FSM is output with CurState.

3.1 What to Do

Perform the following steps:

<ol>
<li>Begin with the template code provided online in part1_template.v.</li>
<li>Complete the state table and the output logic. Look for the question marks (?).</li>
<li>Simulate your part1 module with ModelSim to satisfy yourself that your circuit is working. Be prepared to justify that your test cases are enough to give confidence that your circuit is working. When you are satisfied with your simulations, you can submit to the Automarker.</li>
<li>Create a new Quartus project for your circuit. You will need a top-level module to make connections from the instantiation of your part1 module to the switches, pushbutton and LEDs of the DE1-SoC board. Connect the toggle switch SW0 on the DE1-SoC board as the active-low synchronous reset input Resetn for the FSM, SW1 as the w input, and the pushbutton KEY0 as the Clock input that is applied manually, i.e., you will manually create clock pulses so that you can observe the transitions through the states. The LED LEDR9 is the output z, and the CurState output is assigned to LEDR3−0 .
Simulate your new circuit with the DE1-SoC connections with ModelSim to ensure that you have done the connections correctly.

3
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
01#$

</div>
</div>
<div class="layoutArea">
<div class="column">
01)$

</div>
</div>
<div class="layoutArea">
<div class="column">
,-.-/$ 01#$

!”#$

01)$

%”#$

01)$

&amp;”#$

01)$

01#$

‘” #$

01)$

(“)$

</div>
</div>
<div class="layoutArea">
<div class="column">
01#$

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 2: A state diagram for the FSM.

4

</div>
</div>
<div class="layoutArea">
<div class="column">
01#$

01#$

*”#$

01)$

+” )$

</div>
<div class="column">
01#$

</div>
</div>
<div class="layoutArea">
<div class="column">
01)$

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Figure 3: Verilog code for the FSM. 5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
4

</div>
</div>
<div class="layoutArea">
<div class="column">
5. 6. 7.

</div>
<div class="column">
Compile the project to generate a bitstream to make sure your code can at least be synthesized.

If you have a board, download the compiled circuit into the FPGA chip. Test the functionality of the circuit by toggling the various inputs and observing the outputs.

If you do not have a board, you can use fake fpga to test that your circuit behaves as expected.

Part II

</div>
</div>
<div class="layoutArea">
<div class="column">
Please note that there is a lot written here. Most of it is explanation and guidance, so please read carefully.

A finite state machine (FSM) on its own, like the one built in Part I, cannot do much and is not what you usually do with an FSM except to teach how to build an FSM. The primary use of FSMs is to act as the main control for digital systems that require functions like sequencing or responding in different ways to some stimuli. This part will show you how to use an FSM to do something more interesting than recognizing a pattern of bits. To help you focus on the FSM design, you are provided an entire datapath and example FSM that performs a computation. Your task will be to change the FSM to do a different computation.

Most non-trivial digital circuits can be separated into two main functions. One is the datapath where the data flows and the other is the control path that manipulates the signals in the datapath to control the operations performed and how the data flows through the datapath. In previous labs, you learned how to construct a simple ALU, which is a common datapath component. In Part I of this lab you have already constructed a simple FSM, which is the most common component used to implement a control path. Now you will see how to implement an FSM to control a datapath so that a useful operation is performed. This is an important step towards building a microprocessor as well as any other computing circuit.

In this part, you are given a datapath and an FSM that controls the datapath so that it computes A2 + C. Observe that the example code loads four values, despite using only two of the values in the computed result. This will give you a head start because you will need all four values loaded for the task you will do. Also, often when you inherit code, there might be parts of it that may not be used or be relevant because of how the code evolved. It is up to you to figure out what is relevant for the task you are given. Feel free to modify the code you are given, if you feel it is necessary to achieve the final result required.

Using the given datapath, you are required to implement an FSM that controls the datapath so that it performs the computation:

Ax2 +Bx+C 6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
data_in

</div>
</div>
<div class="layoutArea">
<div class="column">
ld_alu_out

</div>
</div>
<div class="layoutArea">
<div class="column">
ld_c ld_x

alu_select_a

alu_op

ld_r

</div>
<div class="column">
ld_a

</div>
<div class="column">
ld_b

alu_select_b

</div>
</div>
<div class="layoutArea">
<div class="column">
C

</div>
</div>
<div class="layoutArea">
<div class="column">
X

</div>
</div>
<div class="layoutArea">
<div class="column">
A

</div>
</div>
<div class="layoutArea">
<div class="column">
B

</div>
</div>
<div class="layoutArea">
<div class="column">
R

</div>
</div>
<div class="layoutArea">
<div class="column">
data_result

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 4: Block diagram of datapath.

The values of x, A, B and C will be preloaded by the user on the switches before the computation begins.

Figure 4 shows the block diagram of the datapath you will build. Resets are not shown, but do not forget them. The datapath will carry 8-bit unsigned values. Assume that the input values are small enough to not cause any overflows at any point in the computation, i.e., no results will exceed 28 − 1 = 255. The ALU needs only to perform addition and multiplication, but you could use a variation of the ALU you built previously to have more operations available for solving other equations if you wish to try some things on your own. There are four registers Rx, RA, RB and RC used at the start to store the values of x, A, B and C, respectively. The registers RA and RB can be overwritten during the computation. There is one output register, RR, that captures the output of the ALU and displays the value in binary on the LEDs and in hex on the HEX displays. Two 8-bit-wide, 4-to-1 multiplexers at the inputs to the ALU are used to select which register values are input to the ALU.

All registers have enable signals to determine when they are to load new values and an active low synchronous reset.

The provided circuit operates in the following manner. After an active low synchronous reset using Resetn, you will input the value for RA on switches at the port DataIn. When Go is set and released, RA will be loaded and then you will input the next value at DataIn that will be loaded into RB. Set and release Go again. Repeat these steps to load RC and RX. Computation will start after Go is set and released for loading RX. When computation is finished, the final result will be loaded into RR. This final result should be output on port

7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
Table 1: Register contents and control signals for computing A2 + C

</div>
</div>
<div class="layoutArea">
<div class="column">
datain RA RB RC

Rx

RR

lda

ldb

ldc

ldx

ld alu out alu select a alu select b alu op

</div>
<div class="column">
Reset12345 6 7 5432222

055552525

0044444

0003333

0000222

00000028

1000101

0100000

0010000

0001000

0000100 1 = select alu output 0000000 0 = select A 0000020 2 = select C 0000100 0 = add, 1 = multiply 0000010

</div>
</div>
<div class="layoutArea">
<div class="column">
ldr

DataResult in binary. The clock for the circuit is input at port Clock.

</div>
</div>
<div class="layoutArea">
<div class="column">
4.1 What to Do

Perform the following steps:

</div>
</div>
<div class="layoutArea">
<div class="column">
1. Examine the Verilog code provided online in part2_template.v. This is a major step in this part of the lab. You will not need to write much Verilog, but you will need to fully understand the provided Verilog to make your modifications and build a simulation script. Here’s how to read the code and what to look for:

<ol>
<li>(a) &nbsp;The part2 module has two modules called datapath and control, which is the explicit partitioning of the control logic and the datapath logic. The code has been organized this way to make it very clear where the control logic is written versus the datapath logic. Most important is that you can clearly see what control signals coming from the control logic connect to the datapath.</li>
<li>(b) &nbsp;Read the datapath code and identify all the components shown in Figure 4 when looking at the datapath module.</li>
<li>(c) &nbsp;Identify all the control signals shown in Figure 4 and where they are generated in the control module. You should see that all the control signals are generated by the FSM in the control module.
8
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
<ol start="4">
<li>(d) &nbsp;Find the case statement that defines the state table for the FSM. Also, find the case statement that defines the outputs that are set in each state. It is important that the state transitions and the output logic be in separate case statements. This makes it explicitly clear what logic is being generated from your Verilog. If you start mixing the state transitions with the outputs, the code becomes very challenging to understand, with the risk that the Verilog compilation will also do something you did not intend.
By looking at the state transitions and what outputs are set in each state, observe how the loading of the four registers is done and how the sequence of the loading is done according the specification. How does the FSM handle the setting and releasing of the input Go signal? Ultimately, the Go signal will be connected to a pushbutton on the DE1-SoC board, which is a mechanical device that runs in human time. If the clock is running at 50 MHz how many clock pulses might there be during the time that the Go signal is set high by a human? How does the FSM account for human time? Take this into account when doing your simulations.

You may find it helpful to draw a state diagram for the FSM because you can then just modify it for Step 5.
</li>
<li>(e) &nbsp;Which states do the actual computation? Identify those states and find the se- quence of control signals. Observe how the computation is done by using Figure 4 and seeing how that sequence of control signals does the required operation. Can you figure out what is being computed by looking at the FSM?</li>
</ol>
<ol start="2">
<li>Table 1 shows a table of the sequence of register contents and control signals to do the computation of A2 + C. You should be able to see the control signals changing the same way in part2 template.v. in the controller state machine output logic. See the supplemental notes NotesForControlContentSignalsLab6.pdf for a further explanation of Table 1.</li>
<li>Simulate part2 template.v using ModelSim starting with the values in Table 5 and some other values of your choosing. Remember that the registers are only eight bits wide, so make sure all values will fit in the correct range.
Observe the state register of the FSM so that you can watch the state transitions. This is usually helpful when things are not working as getting the control sequences correct is usually the hardest part of a design.

You should be able to use the same simulation script after you modify the circuit to do the new computation, except you may need to account for there being more operations being performed, so more simulation time will be needed.

Before making changes to any design, it is always good to start from a known state, which in this case is a working example and a working simulation script. You are pro- vided part2 template.v, which is working code and you will build the corresponding simulation script. After this step, you will have both before you start making changes

9
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
to the code. If something goes wrong, go back to when the design last worked and figure out what change caused the error.

<ol start="4">
<li>Following the model of part2 template.v and Table 5, build the table for computing Ax2 +Bx+C.</li>
<li>Draw a state diagram for your controller starting with the register load states provided in part2 template.v.</li>
<li>Modify part2 template.v to implement your controller. You should only need to modify the control module.</li>
<li>Simulate your circuit with ModelSim for a variety of inputs. Since you are modifying the controller it is recommended that you simulate the controller module by itself first. Only when you are satisfied that it is working individually should you add it into the full design for a full system simulation. Why is this approach better? (Hint: Consider the case when your design has 20 different modules.) When you are satisfied with your simulations, you can submit to the Automarker,</li>
<li>Create a new Quartus project for your circuit. You will need a top-level module to make connections from the instantiation of your part2 module to the switches, pushbuttons, LEDs and HEX displays of the DE1-SoC board. Connect KEY0 to Resetn and switches SW[7 : 0] to DataIn. The Go input should be driven by KEY1. The final result at DataResult should be displayed on LEDR7−0 in binary and HEX0 and HEX1 in hex. Connect CLOCK 50 to the Clock input. Remember that the pushbuttons on the DE1-SoC board are active low.
Simulate your new circuit with the DE1-SoC connections with ModelSim to ensure that you have done the connections correctly.
</li>
<li>To examine the circuit produced by Quartus open the RTL Viewer tool (Tools&gt;Netlist Viewers &gt; RTL Viewer). Find (on the left panel) and double-click on the box shown in the circuit that represents the finite state machine, and determine whether the state diagram that it shows properly corresponds to the one you have drawn. To see the state codes used for your FSM, open the Compilation Report, select the Analysis and Synthesis section of the report, and click on State Machines.
The state codes after synthesis may be different from what you originally specified. This is because the tool may have found a way to optimize the logic better by choosing a different state assignment. If you really need to use your original state assignment, there is a setting to keep it.
</li>
<li>Compile the project to generate a bitstream to make sure your code can at least be synthesized.</li>
<li>If you have a board, download the compiled circuit into the FPGA chip. Test the functionality of the circuit.
10
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
12. If you do not have a board, you can use fake fpga to test that your circuit behaves as expected.

5 Part III (Optional – For Bonus Marks)

In this part, you will have to build a complete datapath and corresponding state machine. We recommend that you still have two separate modules for the datapath and the control just to help you understand the separation of what is in a datapath and what is in a controller. In Part II, the control logic just generated control signals that were inputs to the datapath. In this part, you will see that there is a signal that needs to go from the datapath into the controller so make sure you account for it accordingly.

Division in hardware is the most complex of the four basic arithmetic operations. Add, subtract and multiply are much easier to build in hardware. For this part, you will be designing a 4-bit restoring divider using a finite state machine.

Figure 5 shows an example of how the restoring divider works. This mimics what you do when you do long division by hand. In this specific example, number 7 (Dividend) is divided by number 3 (Divisor). The restoring divider starts with Register A set to 0. The Dividend is shifted left and the bit shifted out of the left most bit of the Dividend (called the most significant bit or MSB) is shifted into the least significant bit (LSB) of Register A as shown in Figure 6.

The Divisor is then subtracted from Register A. If the MSB of Register A is a 1, then we restore Register A back to its original value by adding the Divisor back to Register A, and set the LSB of the Dividend to 0. Else, we do not perform the restoring addition and immediately set the LSB of the Dividend to 1. You may use the subtract (−) and addition (+) operators in Verilog to perform the subtraction and addition. The 1 in the MSB of Register A means that the value in Register A after the subtraction is a negative number, meaning that the Divisor is larger than the original value in Register A. That is why Register A is restored by adding back the Divisor.

This sequence of steps is performed until all the bits of the Dividend have been shifted out. Once the process is complete, the new value of the Dividend register is the Quotient, and Register A will hold the value of the Remainder.

5.1 What to Do

The top-level module of your design should have the following declaration:

11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
Figure 5: An example showing how the restoring divider works.

12

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
Figure 6: Block diagram of restoring divider.

<pre>  module part3(Clock, Resetn, Go, Divisor, Dividend, Quotient, Remainder);
</pre>
Divisor and Dividend are the input values for the division and Quotient and Remainder are the outputs of the division. Resetn is a synchronous active low reset. Go starts the division after the inputs are valid.

Perform the following steps.

<ol>
<li>Draw a schematic for the datapath of your circuit. It will be similar to Figure 6. You should show how you will initialize the registers, where the outputs are taken, and include all the control signals that you require. Do not forget the clock and resets.</li>
<li>Draw the state diagram to control your datapath. Check it by hand simulating the example shown in Figure 5. Hand simulation just means to work through the steps using your schematic and state diagram to check whether you can do the required operations before going through the effort of setting up the simulator. This may not catch all bugs, but it is a good step to make sure you have a design that has a chance of working.</li>
<li>Draw the schematic for your controller module.</li>
<li>Draw the top-level schematic showing how the datapath and controller are connected as well as the inputs and outputs to your top-level circuit.
13
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 14">
<div class="layoutArea">
<div class="column">
8.

9. 10.

6

</div>
</div>
<div class="layoutArea">
<div class="column">
5. 6.

7.

</div>
<div class="column">
Write the Verilog code that realizes your circuit. Structure your code in the same way as you were shown in Part II.

Simulate your circuit with ModelSim for a variety of input settings, ensuring the output waveforms are correct. Start with Figure 5 as an example because it shows you all the steps with the values that should be in the registers at each step.

Create a new Quartus project for your circuit. You will need a top-level module to make connections from the instantiation of your part3 module to the switches, pushbuttons, LEDs and HEX displays of the DE1-SoC board. Connect SW3−0 to Divisor and SW7−4 to Dividend. Use KEY0 as the synchronous active low Resetn and KEY1 as the Go signal to start computation. The Divisor should be displayed on HEX0, the Dividend should be displayed on HEX2, the Quotient on HEX4, and the Remainder on HEX5. Also display the Quotient in binary on LEDR3−0. Connect CLOCK 50 to the Clock input. Remember that the pushbuttons on the DE1-SoC board are active low.

Simulate your new circuit with the DE1-SoC connections with ModelSim to ensure that you have done the connections correctly.

Compile the project to generate a bitstream to make sure your code can at least be synthesized.

If you have a board, download the compiled circuit into the FPGA chip. Test the functionality of the circuit by toggling the various inputs and observing the outputs.

If you do not have a board, you can use fake fpga to test that your circuit behaves as expected.

</div>
</div>
</div>
