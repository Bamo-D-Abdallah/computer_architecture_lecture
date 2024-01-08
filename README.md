## Lecture 1
<details>
    <summary>Computer Architecture</summary>
    is teh study of building entire computer systems.
</details>

<details>
    <summary>How many point of view do we have regarding computer hardware?</summary>
    1. Computer Organization <br />
    2. Computer Design <br />
    3. Computer Architecture <br />
</details>

<details>
    <summary>Computer Organization</summary>
    deals with <b style="color: red">structural relationships</b> that are <b style="color: red">not visible to the programmer</b>
</details>

<details>
    <summary>Computer Design</summary>
    Hardware Design/Implementation
</details>

<details>
    <summary>Computer Architecture</summary>
    deals with the <b style="color: red">functional behavior</b> of a computer as <b style="color: red">viewed by a programmer</b>
</details>

<details>
    <summary>Computer Organization</summary>
    deals with **structural relationships** that are **not visible to the programmer**
</details>
<br />

## Lecture 2
<details>
    <summary>Computer</summary>
    is an advanced electornic device that takes raw data as input and processes these data under a set of instructions and gives the output and saves the output.
</details>

<details>
    <summary>How many functions does a computer have and what are they?</summary>
    1. accept data: Input <br />
    2. process data: Processing <br />
    3. produces output: Output <br />
    4. stores results: Storage <br />
</details>

<details>
    <summary>how many entities digital computer system is divided into?</summary>
    1. software <br />
    2. hardware <br />
</details>

<details>
    <summary>Software system</summary>
    Operating system, application programs, programming languages.
</details>

<details>
    <summary>Hardware system</summary>
    printer, mouse, keyboard, .., etc.
</details>


<details>
    <summary>what are the steps of instructing a computer?</summary>
    1. write a program <br />
    2. compile it <br />
    3. execute it <br />
</details>

<details>
    <summary>how many components does Von Neumann consist?</summary>
    1. input unit <br />
    2. output unit <br />
    3. arithmetic logic unit <br />
    4. memory unit <br />
    5. control unit <br />
</details>

<details>
    <summary>The System Bus Model</summary>
    It is a refinement of the von Neumann model which has a CPU, memory and IO unit.
</details>

<details>
    <summary>draw image/diagram of System Bus Model</summary>
    <img src="images/lec2_bus_model.png" />
</details>

<details>
    <summary>What system bus is made up of?</summary>
    1. data bus <br />
    2. address bus <br />
    3. control bus <br />
</details>

<details>
    <summary>ISA</summary>
    it is the semantics of all instructions supported by a processor.
</details>

<details>
    <summary>What features an ISA must contain?</summary>
    1. Complete <br />
    2. Concise <br />
    3. Generic <br />
    4. Simple <br />
</details>

<details>
    <summary>Complete in ISA</summary>
    It should be able to implement all the programs that users may write.
</details>

<details>
    <summary>Concise in ISA</summary>
    The instruction set should have a limited size 32 - 1000 instructions.
</details>

<details>
    <summary>Generic in ISA</summary>
    Instructions should not be too specialized
</details>

<details>
    <summary>Simple in ISA</summary>
    should not be very compliated
</details>

<details>
    <summary>How many ISA paradigms do we have?</summary>
    1. RISC <br />
    2. CISC <br />
</details>

<details>
    <summary>RISC</summary>
    Implements simple instructions that have a simple regular structure.
</details>

<details>
    <summary>CISC</summary>
    implements complex instructions that are highly irregular, take multiple operands.
</details>
<br />

## Lecture 3

<details>
    <summary>computers use ___ to represent information</summary>
    voltages
</details>

<details>
    <summary>Modern processor's voltages are limited to around ___ to reduce power consumption</summary>
    1.5V
</details>

<details>
    <summary>Decimal numbers onsist of digits from ___  to ___</summary>
    0 <br />
    9 <br />
</details>

<details>
    <summary>What is the base of decimal numbers?</summary>
    10
</details>

<details>
    <summary>Binary numbers consist of only ___ and ___</summary>
    0 <br />
    1 <br />
</details>

<details>
    <summary>what is the base of binary numbers?</summary>
    2
</details>

<details>
    <summary>How many digits does Hexadecimal use?</summary>
    16 digits
</details>

<details>
    <summary>What is the base of Hexadecimal?</summary>
    16
</details>

<details>
    <summary>How do you represent voltages in boolean value?</summary>
    0 voltage => false <br />
    1 voltage => true <br />
</details>

<details>
    <summary>How many ways do we have to express mathematical functions?</summary>
    1. <b>expression</b>: finite but not unique<br />
    2. <b>function table</b>: unique but infinite<br />
</details>

<details>
    <summary>literal in boolean expression</summary>
    any occurrence of an input variable or its complement.
</details>

<details>
    <summary>truth table</summary>
    shows all possible inputs and outputs of a Boolean function
</details>

<details>
    <summary>a function with n variables has __ possible combinations of inputs</summary>
    2<sup>n</sup>
</details>

<br />

## Lecture 4
<details>
    <summary>digital circuits are constructed with ___</summary>
    Integrated Circuits
</details>

<details>
    <summary>Decoder</summary>
    a combinational circui that converts binary information from the n coded inputs to a maximum of 2<sup>n</sup> unique outputs
</details>

<details>
    <summary>Toggle Switch</summary>
    Foldable Content[enter image description here][1]
</details>

<details>
    <summary>Encoder</summary>
    inverse operation of a decoder
</details>

<details>
    <summary>Multiplexer(MUX)</summary>
    Foldable Content[enter image description here][1]
</details>

<details>
    <summary>Register</summary>
    A group of flip-flops with each flip-flo p capable of storing one bit of information
</details>

<details>
    <summary>Shift Register</summary>
    A register capable of shifting its binary information in one or both directions.
</details>

<details>
    <summary>unidirectional shift register</summary>
    a register capable of shifting in one direction only
</details>

<details>
    <summary>bidirectional shift register</summary>
    A register that can shift in both directions. 
</details>

<details>
    <summary>Binary Counter</summary>
    A register goes thorugh a predetermined sequence of state.
</details>

<details>
    <summary>Memory Unit</summary>
    A collection of storage cells together with associated circuits needed to transfer information in and out of storage.
</details>

<details>
    <summary>Word</summary>
    A group of bits
</details>

<details>
    <summary>Byte</summary>
    A group of 8 bits
</details>

<details>
    <summary>Nibble</summary>
    A group of 4 bits
</details>

<details>
    <summary>Which type of memory is volatile?</summary>
    RAM
</details>

<details>
    <summary>Which type of memory is non-volatile</summary>
    ROM
</details>

<details>
    <summary>What are the two operations that RAM can perform?</summary>
    1. Read <br />
    2. Write <br />
</details>

<br />

## Formula

###### Address Line
1 Kilo = 2<sup>10</sup> <br />
1 Mega = 2<sup>20</sup> <br />
1 Giga = 2<sup>30</sup> <br />
exapmle: 16 bit address line = 2<sup>16</sup> = 64 k

<br />

## Abbrevations
<details>
    <summary>ALU</summary>
    Arithmetic and Logic Unit
</details>

<details>
    <summary>I/O</summary>
    Input and Output
</details>

<details>
    <summary>ISA</summary>
    instruction set architecture
</details>

<details>
    <summary>RISC</summary>
    Reduced instruction set computer
</details>

<details>
    <summary>CISC</summary>
    Complex instructions set computer
</details>

<details>
    <summary>MUX</summary>
    Multiplexer
</details>

