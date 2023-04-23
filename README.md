Download Link: https://assignmentchef.com/product/solved-24677-homework3-controllability-and-observability
<br>
<strong>Exercise 1. </strong><em>Controllability and Observability </em>

Is the state equation

Controllable?Observable?<strong> </strong>Provide your derivation.

<strong>Exercise 2. </strong><em>Jordan form test </em><em>(15 points)</em>

Is the Jordan-form state equation controllable and observable?

<table width="311">

 <tbody>

  <tr>

   <td width="62">2<sub></sub>00<em>x</em>˙ = <sup></sup><sub></sub>0 0<sub></sub>00</td>

   <td width="21">1200000</td>

   <td width="21">0020000</td>

   <td width="21">0002000</td>

   <td width="21">0000100</td>

   <td width="21">0000110</td>

   <td width="33">00<sub></sub>0 0<sub></sub><em>x</em>0<sub></sub>0<sub></sub>1</td>

   <td width="60"> 2<sub> </sub>2  1 + <sub> </sub>3 <sup></sup>−1<sub> </sub>11</td>

   <td width="21">1112000</td>

   <td width="30">01<sub></sub>1<sub> </sub>1<sub></sub><em>u</em>1<sub></sub>1<sub></sub>0</td>

  </tr>

  <tr>

   <td rowspan="2" width="62"></td>

   <td rowspan="2" width="21">211</td>

   <td rowspan="2" width="21">111</td>

   <td rowspan="2" width="21">321</td>

   <td rowspan="2" width="21">−101</td>

   <td rowspan="2" width="21">101</td>

   <td width="33">1</td>

   <td width="60"> </td>

   <td rowspan="2" width="21"> </td>

   <td rowspan="2" width="30"> </td>

  </tr>

  <tr>

   <td colspan="2" width="93"></td>

  </tr>

 </tbody>

</table>







<strong>Exercise 3. </strong><em>Controllability </em>

Recall the Exercise 3 of Homework 2 from last week. Is that system controllable? <strong> </strong>Why?

Now lets move the inlet pipe from tank 1 to tank 2, as shown in the figure. Is this system controllable now? <strong> </strong>Why?

Figure 1: Revised Tank Problem

The system dynamics are

<strong>Exercise 4. </strong><em>Gauss Elimination and LU Decomposition </em><em>(20 points)</em>

<ol>

 <li>Solve the following system of linear equations using Gauss Elimination Method

  <ol>

   <li><em>x </em>+ <em>y </em>+ <em>z </em>= 3 <em>x </em>+ 2<em>y </em>+ 3<em>z </em>= 0 <em>x </em>+ 3<em>y </em>+ 2<em>z </em>= 3</li>

  </ol></li>

</ol>

<ul>

 <li><em>x </em>+ 2<em>y </em>− <em>z </em>= 1 2<em>x </em>+ 5<em>y </em>− <em>z </em>= 3 <em>x </em>+ 3<em>y </em>+ 2<em>z </em>= 6</li>

</ul>

<ol>

 <li><em>x</em><sub>1 </sub>+ <em>x</em><sub>2 </sub>− <em>x</em><sub>3 </sub>+ <em>x</em><sub>4 </sub>= 1 2<em>x</em><sub>1 </sub>+ 3<em>x</em><sub>2 </sub>+ <em>x</em><sub>3 </sub>= 4</li>

</ol>

3<em>x</em><sub>1 </sub>+ 5<em>x</em><sub>2 </sub>+ 3<em>x</em><sub>3 </sub>−<em>x</em><sub>4 </sub>= 5

<ol start="2">

 <li>Solve the following system of linear equations using LU Decomposition Method</li>

</ol>

<em>x</em><sub>1 </sub>+ 2<em>x</em><sub>2 </sub>+ 4<em>x</em><sub>3</sub>= 3

3<em>x</em><sub>1 </sub>+ 8<em>x</em><sub>2 </sub>+ 14<em>x</em><sub>3</sub>=13

2<em>x</em><sub>1 </sub>+ 6<em>x</em><sub>2 </sub>+ 13<em>x</em><sub>3</sub>= 4

Provide your derivation.

<strong>Exercise 5. </strong><em>SVD </em><em>(15 points)</em>

Use SVD to compress the following image to 50%, 10%, and 5% of the original file size. You will find the image in the Canvas homework folder. For this problem you need to upload code and attached the corresponding compressed images.

Figure 2: CMU Grayscale.png

<strong>Exercise 6. </strong><em>Design for Controllability and Observability </em><em>(20 points)</em>

Given the following Linear Time Invariant (LTI) system with a tunable parameter <em>γ</em>,

<ol>

 <li>What values of <em>γ </em>makes the system controllable but not observable? <strong>(10 points)</strong></li>

 <li>What values of <em>γ </em>makes the system observable but not controllable? <strong>(10 points)</strong></li>

</ol>

<strong>Exercise 7. </strong><em>State Space Representation, Controllability </em><em>(10 points)</em>

We have an LED strip with 5 red LEDs whose brightnesses we want to set. These LEDs are addressed as a queue: at each time step, we can push a new brightness command between 0 and 255 to the left-most LED. Each of the following LEDs will then take on the brightness previously displayed by the LED immediately to its left.

<ol>

 <li>Model the system as a discrete system with input <em>u</em>(<em>t</em>) as the brightness command to the left-most LED. The state to be the brightness of the five LEDs. Output equals to the state. Write out the state equations in matrix form. <strong>(5 points)</strong></li>

 <li>Check the system’s controllability. Explain intuitively what the controllability means in this system. <strong>(5 points)</strong></li>

</ol>

Note: you do NOT need to consider the 0-255 constraints on the input.