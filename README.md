Download Link: https://assignmentchef.com/product/solved-ee6225-assignment-3
<br>
In Part 1, you have used Decentralised, Sparse, and Decoupling control methods for a 3 × 3 process. In this assignment, you will design a MPC for the same 3 × 3 process:

The main aim of this assignment is to let students compare (a) the multivariable control design techniques learned in Part 1 and (b) the Model Predictive Control (MPC) method learned in Part 2.

1

Answer as many questions as you can.

<ol>

 <li>Compare your best MPC design with those you obtained in Part 1. Simulate theclosed-loop step responses for the set-point profile:</li>

</ol>



<sub> </sub><em>R</em>1(<em>t</em>) = 1<em>,              t &gt; </em>0 <em>R</em><sub>2</sub>(<em>t</em>) = 1<em>,   t &gt; </em>50

<sup></sup><sub> </sub><em>R</em><sub>3</sub>(<em>t</em>) = 1<em>,        t &gt; </em>100

<ol start="2">

 <li>Discuss how did you select an appropriate sampling time for your MPC design.What were your considerations?</li>

 <li>Include the MATLAB code you have used to obtain the state space representationof the plant model (with <em>u</em>(<em>k</em>) as input). What are the dimensions of the <em>A<sub>p</sub></em>, <em>B<sub>p </sub></em>and <em>C<sub>p </sub></em></li>

 <li>Include the MATLAB code you have used to obtain the plant model <em>A</em>, <em>B</em>, and <em>C </em>for your MPC design with ∆<em>u</em>(<em>k</em>) as input. What are the dimensions of the <em>A</em>, <em>B </em>and <em>C </em></li>

 <li>Discuss the effects of the MPC tuning knobs, <em>N</em><sub>2</sub>, <em>N<sub>u </sub></em>and <em>λ </em>on the closed-loop step response performance. Support your observations with simulation examples.</li>

 <li></li>

</ol>

<table>

 <tbody>

  <tr>

   <td width="118"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Comment on the pros and cons of the MPC method based on this case study.</li>

</ul>

<strong>Bonus:</strong>

<ol start="7">

 <li>If you had knowledge of the future set-points at the start, how would you modify your MPC to take account of this future set-point information? Perform a simulation to compare with and without future set-point scenarios.</li>

 <li>Does your MPC design has integral action? How can you demonstrate this?</li>

 <li>Any other investigation or innovation not mentioned above.</li>

</ol>