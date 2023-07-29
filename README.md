# ALU_Verification
<p align = "justify">A testbench was implemented using  verification methodology, for verifying an ALU RTL to ensure that the ALU functions correctly and reliably, and to detect the present bugs if any.</p>
<p align = "justify">The ALU has 3 inputs and 2 outputs.</p>
<p align = "justify">
<b>Inputs</b> 
  <ul>
  <li><i>A</i>: First Operand (8-Bit)</li>
  <li><i>B</i>: Second Operand (8-Bit)</li>
  <li><i>ALU_Sel</i>: Selection Line (4-Bit)</li>
  </ul>
  </p>
<p align = "justify">
<b>Oututs</b> 
  <ul>
  <li><i>ALU_Out</i>: ALU Output (8-Bit)</li>
  <li><i>CarryOut</i>: Carry Out Flag (1-Bit)</li>
  </ul>
  </p>
<p align = "justify">
The ALU (Device Under Test) had 3 bugs, namely Subtraction,  Logical OR and Logical NAND operations, which were detected using the testbench. Furthermore, html coverage report was generated, and detailed coverage report was generated as well using <i>coverage report -detail</i> command.
</p>

![Screenshot 2023-07-28 230255](https://github.com/MayaLasheen/ALU_Verification/assets/137602736/8a7a2cc2-cb57-4d25-b429-eda9868064a3)

![Screenshot 2023-07-29 014322](https://github.com/MayaLasheen/ALU_Verification/assets/137602736/40ef1121-de28-43c5-8dcc-025e4c9c4d4e)


