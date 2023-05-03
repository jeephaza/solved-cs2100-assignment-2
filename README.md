Download Link: https://assignmentchef.com/product/solved-cs2100-assignment-2
<br>
<h1>Question 0.</h1>

<ul>

 <li>You have named your file with your student number, i.e., <strong>pdf</strong>.</li>

 <li>You have submitted your assignment as a <strong>single PDF file</strong> and no multiple copies, i.e. there should only be ONE file in your submission folder.</li>

 <li>Your assignment submission has your <strong>tutorial group number</strong>, <strong>student number</strong> and <strong>name</strong> at the top of the first page of your file. (All three items must be present.</li>

</ul>

<strong>Qestion 1. Datapath  </strong>

[Past-year’s exam question] Consider the MIPS datapath with the values of the registers shown below. All values are in hexadecimal.

R0  (r0) = 0x00000000 | R1  (at) = 0x00002000

R2  (v0) = 0x00000001 | R3  (v1) = 0x0000000a

R4  (a0) = 0x00000005 | R5  (a1) = 0x7ffff000

R6  (a2) = 0x7ffff004 | R7  (a3) = 0x000000b0

R8  (t0) = 0x00000001 | R9  (t1) = 0x00000c00

R10 (t2) = 0x0000c000 | R11 (t3) = 0xfffffff0

R12 (t4) = 0xf0000000 | R13 (t5) = 0x00000fff

R14 (t6) = 0x00006200 | R15 (t7) = 0x00000e00

R16 (s0) = 0x00300000 | R17 (s1) = 0x00000c00

R18 (s2) = 0x00040200 | R19 (s3) = 0x00011000

R20 (s4) = 0x00030200 | R21 (s5) = 0x10000000

R22 (s6) = 0x00055000 | R23 (s7) = 0xf0000000

R24 (t8) = 0x00000005 | R25 (t9) = 0x0000d000

R26 (k0) = 0x00000000 | R27 (k1) = 0x00000000

R28 (gp) = 0x10008000 | R29 (sp) = 0x7fffeff4

R30 (s8) = 0x1000000f | R31 (ra) = 0x00400018







<strong>uestion 1. (continue…) </strong>

The current PC value is <strong>200</strong> and the instruction being executed is:

<strong>lw $t6, -24($sp) </strong>

Fill in the values of the fields in the table below.

For the 8<sup>th</sup> data row onwards in the table below, if your value is not in base ten, make sure you write the prefix (eg: 0x123) or subscript (eg: 123<sub>16</sub>) to specify the base. Values without prefix or subscript will be treated as if they are in base ten by default.

<table width="387">

 <tbody>

  <tr>

   <td width="194"><strong>Field </strong></td>

   <td width="194"><strong>Value </strong></td>

  </tr>

  <tr>

   <td width="194">RegDst</td>

   <td width="194"></td>

  </tr>

  <tr>

   <td width="194">MemRead</td>

   <td width="194"></td>

  </tr>

  <tr>

   <td width="194">Branch</td>

   <td width="194"></td>

  </tr>

  <tr>

   <td width="194">MemtoReg</td>

   <td width="194"></td>

  </tr>

  <tr>

   <td width="194">MemWrite</td>

   <td width="194"></td>

  </tr>

  <tr>

   <td width="194">ALUSrc</td>

   <td width="194"></td>

  </tr>

  <tr>

   <td width="194">RegWrite</td>

   <td width="194"></td>

  </tr>

  <tr>

   <td width="194">Instruction[31-26]</td>

   <td width="194"></td>

  </tr>

  <tr>

   <td width="194">Instruction[25-21]</td>

   <td width="194"></td>

  </tr>

  <tr>

   <td width="194">Instruction[20-16]</td>

   <td width="194"></td>

  </tr>

  <tr>

   <td width="194">Instruction[15-11]</td>

   <td width="194"></td>

  </tr>

  <tr>

   <td width="194"></td>

   <td width="194"><strong> </strong></td>

  </tr>

  <tr>

   <td width="194"></td>

   <td width="194"><strong> </strong></td>

  </tr>

  <tr>

   <td width="194"></td>

   <td width="194"></td>

  </tr>

  <tr>

   <td width="194"></td>

   <td width="194"></td>

  </tr>

  <tr>

   <td width="194"></td>

   <td width="194"></td>

  </tr>

 </tbody>

</table>




<strong>             </strong>

<h1>uestion 2. Simplification</h1>

(a) Simplify the following Boolean expression into its <u>simplest SOP expression</u>, showing each step with justification (i.e. citing the law/theorem used). Marks will be deducted if a step is not justified or wrongly justified.

<h1>                          <em>A</em><em>B’</em><em>E</em><em>L’</em><em>O</em><em>P’</em><em>T’</em><em>W</em><em>H’</em> + <em>A</em><em>L</em> +<em> A</em><em>L’</em><em>T’</em></h1>

You may skip obvious steps, such as (<em>A</em><em>B’</em>)<em>‘</em> straight to (<em>A’</em>+<em>B</em>) [De Morgan’s theorem] instead of first to (<em>A’</em>+(<em>B’</em>)’) [De Morgan’s] then to (<em>A’</em>+<em>B</em>) [involution]; or (<em>A’</em><em>B</em> + <em>A</em>) straight to (<em>A</em>+<em>B</em>) [absorption theorem 2] instead of first to (<em>A</em> +<em> A’</em><em>B</em>) [commutative law] then to (<em>A</em>+<em>B</em>) [absorption theorem 2].

Recall that the AND operator  must be present. Writing <em>AB</em> instead of <em>A</em><em>B</em> will incur penalty.

<strong> </strong>

For each of the Boolean functions in parts (b) and (c) below, write (i) the number of PIs (prime implicants) in the K-map of the function, (ii) the number of EPIs (essential prime implicants) in the K-map of the function, (iii) its simplest SOP expression, and (iv) its simplest POS expression. If there are more than one simplest SOP/POS expression, you need to give only one.

You may show your K-maps but they won’t be graded. Your K-maps may be useful for us to locate the mistakes you made. If you are drawing the K-maps, please use the following layout. You may use X for don’t cares.

<table width="173">

 <tbody>

  <tr>

   <td width="34"></td>

   <td width="139">


    <table width="137">

     <tbody>

      <tr>

       <td width="34"></td>

       <td width="34"></td>

       <td width="34"></td>

       <td width="34"></td>

      </tr>

      <tr>

       <td width="34"></td>

       <td width="34"></td>

       <td width="34"></td>

       <td width="34"></td>

      </tr>

      <tr>

       <td width="34"></td>

       <td width="34"></td>

       <td width="34"></td>

       <td width="34"></td>

      </tr>

      <tr>

       <td width="34"></td>

       <td width="34"></td>

       <td width="34"></td>

       <td width="34"></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>







<table width="627">

 <tbody>

  <tr>

   <td width="384">(b) <em>F</em>(<em>A</em>,<em>B</em>,<em>C</em>,<em>D</em>) = m(0,1,2,13) + X(4,9,12,14). </td>

   <td width="243"></td>

  </tr>

  <tr>

   <td width="384">(c) <em>G</em>(<em>A</em>,<em>B</em>,<em>C</em>,<em>D</em>) = M(3,4,5,6,11,15)  X(0,2,8,10).</td>

   <td width="243"></td>

  </tr>

 </tbody>

</table>







<strong>             </strong>




<strong> </strong>

<h2>Question 3. Circuit Analysis</h2>

The following circuit diagram is taken from the data sheet of an IC chip. Identify the circuit below, which takes in C<sub>0</sub>, A<sub>1</sub>, A<sub>2</sub>, A<sub>3</sub>, A<sub>4</sub>, B<sub>1</sub>, B<sub>2</sub>, B<sub>3</sub> and B<sub>4</sub> as inputs and generates V, W, X, Y and Z as the outputs. Give the <strong>name</strong> of this circuit <u>and</u> <strong>describ</strong>e what it does by relating the outputs with the inputs.

<h2>Question 4. Circuit Design</h2>

A combinational circuit takes in a 5-bit input <em>ABCDE</em> which is a value in excess 8 representation, and generates an output <em>P</em> such that <em>P</em>=1 if <em>ABCDE</em> represents a prime number, or <em>P</em>=0 otherwise.

For example, if <em>ABCDE</em>=10001, then <em>P</em>=0; if <em>ABCDE</em>=11001, then <em>P</em>=1.

You may assume that negative values will not be supplied to this circuit.

<ul>

 <li>Draw a 5-variable K-map for <em>P</em> (draw one K-map with <em>A</em>=0 and another with <em>A</em>=1).</li>

 <li>Write out the simplified SOP expression for <em>P</em>.</li>

 <li>Let <em>V</em>(<em>A</em>,<em>B</em>,<em>C</em>,<em>D</em>,<em>E</em>) be the validity function, that is, <em>V</em> returns 1 if the input is valid, or 0 otherwise. Implement <em>V</em> using the fewest number of gates with the fewest number of inputs.</li>

</ul>

Draw your circuit for <em>V</em>.




<h2>Question 5. Block-level design</h2>

Note:

&#x25aa; Boolean constants (0 and 1) are always available; &#x25aa; Complemented literals are <u>not</u> available.

<ul>

 <li>Implement the following Boolean function using a single 2-bit magnitude comparator with no additional logic gates.</li>

</ul>

<em>G</em>(<em>A</em>,<em>B</em>,<em>C</em>,<em>D</em>) = m(1, 4, 5, 6, 7, 13)

The block diagram of a 2-bit magnitude comparator is shown below.

<ul>

 <li>A circuit takes in a 5-bit code <em>ABCDE</em> and generates <em>P</em>, the parity bit for the code, assuming even parity scheme, which means that the total number of 1s in <em>ABCDE</em> and <em>P</em> must be even. For example, if <em>ABCDE</em> = 00110, then <em>P</em>=0; if <em>ABCDE</em> = 10101, then <em>P</em>=1.</li>

</ul>

Implement the above circuit using the fewest number of half adders (HA) and 2-bit parallel adders, and no other logic gates. The block diagrams for a half adder and a 2-bit parallel adder are shown below. You are not allowed to change the block diagrams.