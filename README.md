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

## Lecture 5
<details>
    <summary>How many major parts are in CPU?</summary>
    1. Register Set <br />
    2. ALU <br />
    3. Control <br />
</details>

<details>
    <summary>How many modes are there in 8086?</summary>
    1. Minimum mode <br />
    2. Maximum mode <br />
</details>

<details>
    <summary>What is minimum mode in 8086?</summary>
    the processor works in a single processor environment
</details>

<details>
    <summary>What is maximum mode in 8086?</summary>
    the processor works in a multiprocessor environment
</details>

<details>
    <summary>how many function units is 8086 divided into?</summary>
    1. Bus Interface Unit(BIU)
    2. Execution Unit (EU)
</details>

<details>
    <summary>BIU</summary>
    This unit fetches instructions, reads and writes data from memory and ports
</details>

<details>
    <summary>The ___ interfaces the 8086 to the outside world</summary>
    BIU
</details>

<details>
    <summary>Bus Control Circuitry</summary>
    generates all the bus control signals such as READ, WRITE for memroy or I/O
</details>

<details>
    <summary>How many segment registers does 8086 BIU have?</summary>
    The BIU has four 16 bit registers: <br />
    1. Code Segment <br />
    2. Stack Segment <br />
    3. Data Segment <br />
    4. Extra Segment <br />
</details>

<details>
    <summary>How many bits does each register of the BIU use?</summary>
    16 bits
</details>

<details>
    <summary>Execution Unit</summary>
    is responsible for executing the instructions of the programs and to carry out the required processing
</details>


<details>
    <summary>Control Unit</summary>
    responsible for the coordination of all other units of the processor.
</details>

<details>
    <summary>Instruction decoder</summary>
    translates the instructions fetched from the memory into a series of actions that are carried out by the EU.
</details>

<details>
    <summary>ALU</summary>
    perfomrs various arithmetic and logical operations over the data.
</details>


<details>
    <summary>General Registers</summary>
    used for temporary storage and manipulation of data and instructions.
</details>

<details>
    <summary>Flag register</summary>
    depending upon hte vlaue of result after any arithmetic and logical operation the flag bits become set (1) or reset (0)
</details>

<details>
    <summary>____ is a special purpose register</summary>
    Flag Register
</details>

<details>
    <summary>General purpose regisers</summary>
    used to store temporary data within the microprocessor
</details>

<details>
    <summary>How many general purpose registers are in 8086?</summary>
    8
</details>

<details>
    <summary>What is AX register?</summary>
    this is the accumulator used for arithmetical and logical instructions
</details>

<details>
    <summary>What is BX regsiter?</summary>
    This is the base register used to store the value of the offset.
</details>

<details>
    <summary>What is CX register?</summary>
    This is the counter register used in looping and rotation.
</details>

<details>
    <summary>What is DX register?</summary>
    This is the data register used in multiplication and input/output port addressing.
</details>

<details>
    <summary>What is SP?</summary>
    It points to the top most item of the stack, if the stack is empty it points to FFFE.
</details>

<details>
    <summary>What does SP's offset address relative to?</summary>
    Stack Segment
</details>

<details>
    <summary>What is BP?</summary>
    It is primary used in accessing parameters passed by the stack.
</details>

<details>
    <summary>What does BP's offset address relative to?</summary>
    Stack Segment
</details>

<details>
    <summary>What is SI?</summary>
    used in the pointer addressing of data nad as a source in some string related operatins.
</details>

<details>
    <summary>What does SI's offset address relative to?</summary>
    Data segment
</details>

<details>
    <summary>What is DI?</summary>
    used in the pointer addressing of data and as a destination in some string related operations.
</details>

<details>
    <summary>What does DI's offset address relative to?</summary>
    Extra segment
</details>

<details>
    <summary>Segmentation</summary>
    is the process in which the main memory of the computer is logically divided into different segments
</details>

<details>
    <summary>What is the offset address of CS?</summary>
    IP
</details>

<details>
    <summary>What is the offset address of SS?</summary>
    SS and SP
</details>

<details>
    <summary>What is the offset address of DS?</summary>
    SI and DI
</details>

<details>
    <summary>What is the offset address of ES?</summary>
    DI
</details>

<details>
    <summary>What is CS?</summary>
    All programs instructions are pointed to by the CS in memory
</details>

<details>
    <summary>What is SS?</summary>
    a register that points to the current stack
</details>

<details>
    <summary>What is DS?</summary>
    a register that points to current data segment
</details>

<details>
    <summary>What is ES?</summary>
    a register that points to the extra segment
</details>

<details>
    <summary>What is CS?</summary>
    All programs instructions are pointed to by the CS in memory
</details>

<details>
    <summary>What is IP?</summary>
    a register that is responsible for holding the 16 bit offset of the next code byte within the code segment.
</details>

<details>
    <summary>What is Flag register?</summary>
    A flag is a flip flop which indicates some conditions produced by execution of an instruction.
</details>

<details>
    <summary>What is Physical address?</summary>
    the 20 bit address that is actually put on the address pins.
</details>

<details>
    <summary>What is offset address?</summary>
    tells us how far the location is from the beginning.
</details>

<details>
    <summar>What is Logical address?</summary>
    consists of a segment value and offset address
</details>

<br />

## Formula

###### Address Line
1 Kilo = 2<sup>10</sup> <br />
1 Mega = 2<sup>20</sup> <br />
1 Giga = 2<sup>30</sup> <br />
exapmle: 16 bit address line = 2<sup>16</sup> = 64 k

<br />

###### Address Calculation
Physical_address = x_Segment * 10<sup>H</sup> + offset <br />
<br />
x_segment = $\frac{physical_address - offset}{10H}$ <br />
<br />
Offset = Physical_address  - (x_segment * 10<sup>H</sup>) <br />
<br />
Lower_address = (x_segment * 10<sup>H</sup>) + 0000<sup>H</sup> <br />
<br />
Uppset_address = (x_segmet * 10<sup>H</sup>) + FFFF<sup>H</sup> <br />
<br />
When we say x_segment we mean:
1. Code Segment
1. Stack Segment
1. Data Segment
1. Extra Segment
<br />

When we say offset we mean:
1. Instruction Pointer
1. Stack Pointer
1. Base Pointer
1. Source Index
1. Destination Index



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

<details>
    <summary>BIU</summary>
    Bus Interface Unit
</details>

<details>
    <summary>EU</summary>
    Execution Unit
</details>

<details>
    <summary>SP</summary>
    Stack Pointer
</details>

<details>
    <summary>BP</summary>
    Base Pointer
</details>

<details>
    <summary>SI</summary>
    Source index
</details>

<details>
    <summary>DI</summary>
    Destination index
</details>

<details>
    <summary>CS</summary>
    Code Segment
</details>

<details>
    <summary>SS</summary>
    Stack Segment
</details>

<details>
    <summary>DS</summary>
    Data Segment
</details>

<details>
    <summary>ES</summary>
    Extra Segment
</details>

<details>
    <summary>IP</summary>
    Instruction Pointer
</details>
