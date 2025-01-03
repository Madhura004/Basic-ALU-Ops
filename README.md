## Basic-ALU-Ops
## BASIC-ARITHMETIC-LOGIC-UNIT-OPERATIONS USING VERILOG,AND TESTBENCH AND ITS SIMULATION.
## NAME: MADHURA MAHESH PAWAR
## COMPANY : CODETECH IT SOLUTIONS PVT.LTD
## INTERN ID : CT08FEE
## DOMAIN : VLSI
## Mentor : Neela Santosh Kumar
## STEPS INCLUDED TO EXECUTE THE OPERATION:
   1.Requirements :
    Identified the core operations required for the ALU: addition, subtraction, AND, OR, and NOT.Two inputs A and B for binary operations.
    A single input A for unary operations like NOT. An operation selector signal (OpCode) to determine the desired operation. 
    Output for the operation's result and a CarryOut signal for addition/subtraction if applicable.

   2.IMPLEMENTATION :
    Implemented the following functional blocks: Addition Block: Used a binary adder (Ripple Carry Adder or any efficient method). 
    Subtraction Block: Leveraged two's complement addition to perform subtraction. 
    Logic Blocks: Designed basic gates for AND, OR, and NOT operations. 
    Integrated all functional blocks using a multiplexer controlled by the OpCode.

   3.TESTING AND VERIFICATION :
    Performed testbench to simulate the ALU in a hardware simulation tool. 
    Tested for all possible combinations of inputs and operation codes. 

   4.DOCUMENTATION :
    Provided detailed comments in the code explaining each module's functionality. 
    Added performance analysis and possible improvements.

   5.OUTCOME :
   A functional Basic ALU is capable of performing addition, subtraction, AND, OR, and NOT operations with the correctness and the testbench.

## SIMULATION REPORT OF THE OPERATION :
   After running the simulation, you should observe the following:

   Addition: When opcode = 3'b000, the result will be the sum of A and B.

   Subtraction: When opcode = 3'b001, the result will be the difference of A and B.

   AND: When opcode = 3'b010, the result will be the bitwise AND of A and B.

   OR: When opcode = 3'b011, the result will be the bitwise OR of A and B.

   NOT: When opcode = 3'b100, the result will be the bitwise NOT of A.

   For each operation, you can also monitor the carryout and zero flags to verify the correctness of the ALU's functionality. You can expand the testbench with more 
   test cases to ensure all possible scenarios are covered.

   Feel free to run the simulation and let me know if you have any questions or need further assistance!
   
