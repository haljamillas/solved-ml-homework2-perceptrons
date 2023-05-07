Download Link: https://assignmentchef.com/product/solved-ml-homework2-perceptrons
<br>
<h1></h1>

<ol>

 <li>Which of the following set of <strong>x </strong>∈ R<sup>3 </sup>can be shattered by the 3D perceptron hypothesis set? The set contains all hyperplanes of the form with our usual notation of <em>x</em><sub>0 </sub>= 1:</li>

</ol>

<em> .</em>

Choose the correct answer; explain your answer.

<ul>

 <li>{(7<em>,</em>8<em>,</em>9)<em>,</em>(17<em>,</em>18<em>,</em>19)<em>,</em>(27<em>,</em>28<em>,</em>29)}</li>

 <li>{(1<em>,</em>1<em>,</em>1)<em>,</em>(7<em>,</em>8<em>,</em>9)<em>,</em>(15<em>,</em>16<em>,</em>17)<em>,</em>(21<em>,</em>23<em>,</em>25)}</li>

 <li>{(1<em>,</em>1<em>,</em>3)<em>,</em>(7<em>,</em>8<em>,</em>9)<em>,</em>(15<em>,</em>16<em>,</em>17)<em>,</em>(21<em>,</em>23<em>,</em>25)}</li>

 <li>{(1<em>,</em>3<em>,</em>5)<em>,</em>(7<em>,</em>8<em>,</em>9)<em>,</em>(15<em>,</em>16<em>,</em>17)<em>,</em>(21<em>,</em>23<em>,</em>25)}</li>

 <li>{(1<em>,</em>2<em>,</em>3)<em>,</em>(4<em>,</em>5<em>,</em>6)<em>,</em>(7<em>,</em>8<em>,</em>9)<em>,</em>(15<em>,</em>16<em>,</em>17)<em>,</em>(21<em>,</em>23<em>,</em>25)}</li>

</ul>

<ol start="2">

 <li>What is the growth function of axis-aligned perceptrons in 2D for <em>N </em>≥ 4? Those perceptrons are all perceptrons with <em>w</em><sub>1</sub><em>w</em><sub>2 </sub>= 0. That is, they are vertical or horizontal lines on the 2D plane. Choose the correct answer; explain your answer.

  <ul>

   <li>4<em>N </em>+ 4</li>

   <li>4<em>N </em>+ 2 <strong>[c] </strong>4<em>N</em></li>

  </ul></li>

</ol>

<strong>[d] </strong>4<em>N </em>− 2 <strong>[e] </strong>4<em>N </em>− 4

<ol start="3">

 <li>What is the VC dimension of positively-biased perceptrons in 2D? The positively-biased perceptrons are all perceptrons with <em>w</em><sub>0 </sub><em>&gt; </em> Choose the correct answer; explain your answer.

  <ul>

   <li>0</li>

   <li>1</li>

   <li>2</li>

   <li>3</li>

   <li>4</li>

  </ul></li>

</ol>

<h1>Ring Hypothesis Set</h1>

<ol start="4">

 <li>The “ring” hypothesis set in R<sup>3 </sup>contains hypothesis parameterized by two positive numbers <em>a </em>and <em>b</em>, where</li>

</ol>

+1      if

(<strong>x</strong>) =

−1      otherwise<em>.</em>

What is the growth function of the hypothesis set? Choose the correct answer; explain your answer.

<strong>[e] </strong>none of the other choices

<ol start="5">

 <li>Following the previous problem, what is the VC dimension of the ring hypothesis set? Choose the correct answer; explain your answer.

  <ul>

   <li>1</li>

   <li>2</li>

   <li>3</li>

   <li>6</li>

   <li>none of the other choices</li>

  </ul></li>

</ol>

<h1>Deviation from Optimal Hypothesis</h1>

<ol start="6">

 <li>In Lecture 7, the VC bound was stated from the perspective of <em>g</em>, the hypothesis picked by the learning algorithm. The bound itself actually quantifies the BAD probability from <em>any </em>hypothesis <em>h </em>in the hypothesis set. That is,</li>

</ol>

P[∃<em>h </em>∈ H s.t. <em>.</em>

Define the best-<em>E</em><sub>in </sub>hypothesis <em>g </em>= argmin<em><sub>h</sub></em><sub>∈H</sub><em>E</em><sub>in</sub>(<em>h</em>)

and the best-<em>E</em><sub>out </sub>hypothesis (which is optimal but can only be obtained by a “cheating” algorithm)

<em>g</em>∗ = argmin<em>h</em>∈H<em>E</em>out(<em>h</em>)<em>.</em>

Using the VC bound above, with probability more than 1 − <em>δ</em>, which of the following is an upper bound of <em>E</em><sub>out</sub>(<em>g</em>) − <em>E</em><sub>out</sub>(<em>g</em><sub>∗</sub>)? Choose the correct answer; explain your answer.

<h1>The VC Dimension</h1>

<ol start="7">

 <li>For a finite hypothesis set H = {<em>h</em><sub>1</sub><em>,h</em><sub>2</sub><em>,…,h<sub>M</sub></em>}, where each hypothesis is a binary classifier from X to {−1<em>,</em>+1}, what is the largest possible value of <em>d</em><sub>vc</sub>(H)? Choose the correct answer; explain your answer.

  <ul>

   <li><em>M</em></li>

   <li>2<em>M </em><strong>[c] </strong><em>M</em><sup>2</sup></li>

   <li>blog<sub>2 </sub><em>M</em>c</li>

   <li>2<em><sup>M</sup></em></li>

  </ul></li>

 <li>A boolean function <em>h</em>: {−1<em>,</em>+1}<em><sup>k </sup></em>→ {−1<em>,</em>+1} is called <em>symmetric </em>if its value does not depend on the permutation of its inputs, i.e., its value only depend on the number of ones in the input. What is the VC dimension of the set of all symmetric boolean functions? Choose the correct answer; explain your answer.

  <ul>

   <li><em>k </em>− 2</li>

   <li><em>k </em>− 1</li>

   <li><em>k</em></li>

   <li><em>k </em>+ 1</li>

   <li><em>k </em>+ 2</li>

  </ul></li>

 <li>How many of the following are necessary conditions for <em>d</em><sub>vc</sub>(H) = <em>d</em>? Choose the correct answer; state which conditions correspond your answer and explain them.

  <ul>

   <li>some set of <em>d </em>distinct inputs is shattered by H</li>

   <li>some set of <em>d </em>distinct inputs is not shattered by H</li>

   <li>any set of <em>d </em>distinct inputs is shattered by H</li>

   <li>any set of <em>d </em>distinct inputs is not shattered by H</li>

   <li>some set of <em>d </em>+ 1 distinct inputs is shattered by H</li>

   <li>some set of <em>d </em>+ 1 distinct inputs is not shattered by H</li>

   <li>any set of <em>d </em>+ 1 distinct inputs is shattered by H</li>

   <li>any set of <em>d </em>+ 1 distinct inputs is not shattered by H</li>

   <li>1</li>

   <li>2</li>

   <li>3</li>

   <li>4</li>

   <li>5</li>

  </ul></li>

 <li>Which of the following hypothesis set is of VC dimension ∞? Choose the correct answer; explain your answer.

  <ul>

   <li>the rectangle family: the infinite number of hypotheses where the boundary between ±1 regions of each hypothesis looks like a rectangle (including axis-aligned ones and rotated ones) for <strong>x </strong>∈ R<sup>2</sup></li>

   <li>the intersected-interval family: the infinite number of hypotheses where the positive region of each hypothesis can be represented as an intersection of any finite number of “positive intervals” for <em>x </em>∈ R</li>

   <li>the sine family: the infinite number of hypotheses {<em>h<sub>α</sub></em>: <em>h<sub>α</sub></em>(<em>x</em>) = sign(sin(<em>α </em> <em>x</em>))} for <em>x </em>∈ R</li>

   <li>the scaling family: the infinite number of hypothesis for <strong>x </strong>∈ R<em><sup>d</sup></em></li>

   <li>none of the other choices</li>

  </ul></li>

</ol>

<h1>Noise and Error</h1>

<ol start="11">

 <li>Consider a binary classification problem where we sample (<strong>x</strong><em>,y</em>) from a distribution P with <em>y </em>∈ {−1<em>,</em>+1}. Now we define a distribution P<em><sub>τ </sub></em>to be a “noisy” version of P. That is, to sample from P<em><sub>τ</sub></em>, we first sample (<strong>x</strong><em>,y</em>) from P and flip <em>y </em>to −<em>y </em>with probability <em>τ </em> Note that P<sub>0 </sub>= P. The distribution P<em><sub>τ </sub></em>models a situation that our training data is labeled by an unreliable human, who mislabels with probability <em>τ</em>.</li>

</ol>

Define <em>E</em><sub>out</sub>(<em>h,τ</em>) to be the out-of-sample error of <em>h </em>with respect to P<em><sub>τ</sub></em>. That is, <em>E</em>out(<em>h,τ</em>) = E(<strong>x</strong><em>,y</em>)∼P<em>τ h</em>(<strong>x</strong>) 6= <em>y .</em>

J                 K

Which of the following relates <em>E</em><sub>out</sub>(<em>h,τ</em>) to <em>E</em><sub>out</sub>(<em>h,</em>0)? Choose the correct answer; explain your answer.

<ol start="12">

 <li>Consider <strong>x </strong>∈ R<sup>3 </sup>and a target function <em>f</em>(<strong>x</strong>) = argmax<em><sub>i</sub></em><sub>=1<em>,</em>2<em>,</em>3</sub><em>x<sub>i</sub></em>, with ties broken, if any, by choosing the smallest <em>i</em>. Then, assume a process that generates (<strong>x</strong><em>,y</em>) by a uniform <em>P</em>(<strong>x</strong>) within [0<em>,</em>1]<sup>3 </sup>and</li>

</ol>

<sup> </sup>0<em>.</em>7       <em>y </em>= <em>f</em>(<strong>x</strong>)

<ol>

 <li><strong>x</strong>) mod 3 + 1</li>

</ol>

 0<em>.</em>2         <em>y </em>= ( (<strong>x</strong>) + 1) mod 3 + 1

The operation of “<em>a </em>mod 3” returns the residual when the integer <em>a </em>is divided by 3. When using the squared error, what is <em>E</em><sub>out</sub>(<em>f</em>) subject to the process above? Choose the correct answer; explain your answer. (<em>Note: This is in some sense the “price of noise”</em>)

<ul>

 <li>0<em>.</em>3</li>

 <li>0<em>.</em>6</li>

 <li>0<em>.</em>9</li>

 <li>1<em>.</em>2 <strong>[e] </strong>1<em>.</em>5</li>

</ul>

<ol start="13">

 <li>Following Problem 12, the squared error defines an ideal target function</li>

</ol>

<em>,</em>

as shown on page 11 of the Lecture 8 slides. Unlike the slides, however, we denote this function as <em>f</em><sub>∗ </sub>to avoid being confused with the target function <em>f </em>used for generating the data. Define the squared difference between <em>f </em>and <em>f</em><sub>∗ </sub>to be

∆(<em>f,f</em><sub>∗</sub>) = E<strong>x</strong><sub>∼<em>P</em>(<strong>x</strong>)</sub>(<em>f</em>(<strong>x</strong>) − <em>f</em><sub>∗</sub>(<strong>x</strong>))<sup>2</sup><em>.</em>

What is the value of ∆(<em>f,f</em><sub>∗</sub>)? Choose the correct answer; explain your answer. (<em>Note: This means how much the original target function f was dragged by the noise in P</em>(<em>y</em>|<strong>x</strong>) <em>to the “new” target function f</em><sub>∗</sub><em>.</em>)

<ul>

 <li>0<em>.</em>01</li>

 <li>0<em>.</em>14</li>

 <li>0<em>.</em>16</li>

 <li>0<em>.</em>25</li>

 <li>0<em>.</em>42</li>

</ul>

<h1>Decision Stump</h1>

In page 22 of the Lecture 5 slides (the Fun Time that you should play by yourself), we taught about the learning model of “positive and negative rays” (which is simply one-dimensional perceptron). The model contains hypotheses of the form:

<em>h<sub>s,θ</sub></em>(<em>x</em>) = <em>s </em>· sign(<em>x </em>− <em>θ</em>)<em>,</em>

where <em>s </em>∈ {−1<em>,</em>+1} is the “direction” of the ray and <em>θ </em>∈ R is the threshold. You can take sign(0) = −1 for simplicity. The model is frequently named the “decision stump” model and is one of the simplest learning models. As shown in class, the growth function of the model is 2<em>N </em>and the VC Dimension is 2.

<ol start="14">

 <li>When using the decision stump model, given 1 and <em>δ </em>= 0<em>.</em>1, among the five choices, what is the smallest <em>N </em>such that the BAD probability of the VC bound (as given in the beginning of Problem 6) is ≤ <em>δ</em>? Choose the correct answer; explain your answer.

  <ul>

   <li>6000</li>

   <li>8000</li>

   <li>10000</li>

   <li>12000</li>

   <li>14000</li>

  </ul></li>

</ol>

In fact, the decision stump model is one of the few models that we could minimize <em>E</em><sub>in </sub>efficiently by enumerating all possible thresholds. In particular, for <em>N </em>examples, there are at most 2<em>N </em>dichotomies (see page 22 of the Lecture 5 slides), and thus at most 2<em>N </em>different <em>E</em><sub>in </sub>values. We can then easily choose the hypothesis that leads to the lowest <em>E</em><sub>in </sub>by the following decision stump learning algorithm.

<table width="501">

 <tbody>

  <tr>

   <td width="501">(1)   sort all <em>N </em>examples <em>x<sub>n </sub></em>to a sorted sequence such that(2)   for each         1 and <em>x</em><sup>0</sup><em><sub>i </sub></em>6= <em>x</em><sup>0</sup><em><sub>i</sub></em><sub>+1</sub>} and <em>s </em>∈ {−1<em>,</em>+1},calculate <em>E</em><sub>in</sub>(<em>h<sub>s,θ</sub></em>)(3)   return the <em>h<sub>s,θ </sub></em>with the minimum <em>E</em><sub>in </sub>as <em>g</em>; if multiple hypotheses reach the minimum <em>E</em><sub>in</sub>, return the one with the smallest <em>s </em>+ <em>θ</em>.(<em>Hint: CS-majored students are encouraged to think about whether the second step can be carried out efficiently, i.e. O</em>(<em>N</em>)<em>, using dxxxxxc pxxxxxxxxxg instead of the naive implementation of O</em>(<em>N</em><sup>2</sup>)<em>.</em>)</td>

  </tr>

 </tbody>

</table>

Next, you are asked to implement such an algorithm and run your program on an artificial data set. We shall start by generating (<em>x,y</em>) with the following procedure. We will take the target function <em>f</em>(<em>x</em>) = sign(<em>x</em>):

<ul>

 <li>Generate <em>x </em>by a uniform distribution in [−1<em>,</em>+1].</li>

 <li>Generate <em>y </em>from <em>x </em>by <em>y </em>= <em>f</em>(<em>x</em>) and then flip <em>y </em>to −<em>y </em>with <em>τ </em>probability independently</li>

</ul>

<ol start="15">

 <li>For <em>θ </em>∈ [−1<em>,</em>+1], what is <em>E</em><sub>out</sub>(<em>h</em><sub>+1<em>,θ</em></sub><em>,</em>0), where <em>E</em><sub>out</sub>(<em>h,τ</em>) is defined in Problem 11? Choose the correct answer; explain your answer.</li>

 <li>(*) For <em>τ </em>= 0, which means that your data is noiseless. Generate a data set of size 2 by the procedure above and run the decision stump algorithm on the data set to get <em>g</em>. Repeat the experiment 10000 times, each with a different data set. What is the mean of <em>E</em><sub>out</sub>(<em>g,τ</em>) − <em>E</em><sub>in</sub>(<em>g</em>) within the 10000 results? Choose the closest value. (<em>By extending the results in Problem 11 and Problem 15, you can actually compute any E</em><sub>out</sub>(<em>h<sub>s,θ</sub>,τ</em>) <em> But if you do not trust your math derivation, you can get a very accurate estimate of E</em><sub>out</sub>(<em>g</em>) <em>by evaluating g on a separate test data set of size </em>100000<em>, as guaranteed by Hoeffding’s inequality</em>).

  <ul>

   <li>0<em>.</em>00</li>

   <li>0<em>.</em>02</li>

   <li>0<em>.</em>05</li>

   <li>0<em>.</em>30</li>

   <li>0<em>.</em>40</li>

  </ul></li>

 <li>(*) For <em>τ </em>= 0, generate a data set of size 20 by the procedure above and run the decision stump algorithm on the data set to get <em>g</em>. Repeat the experiment 10000 times, each with a different data set. What is the mean of <em>E</em><sub>out</sub>(<em>g,τ</em>) − <em>E</em><sub>in</sub>(<em>g</em>) within the 10000 results? Choose the closest value.

  <ul>

   <li>0<em>.</em>00</li>

   <li>0<em>.</em>02</li>

   <li>0<em>.</em>05</li>

   <li>0<em>.</em>30</li>

   <li>0<em>.</em>40</li>

  </ul></li>

 <li>(*) For <em>τ </em>= 0<em>.</em>1, generate a data set of size 2 by the procedure above and run the decision stump algorithm on the data set to get <em>g</em>. Repeat the experiment 10000 times, each with a different data set. What is the mean of <em>E</em><sub>out</sub>(<em>g,τ</em>) − <em>E</em><sub>in</sub>(<em>g</em>) within the 10000 results?

  <ul>

   <li>0<em>.</em>00</li>

   <li>0<em>.</em>02</li>

   <li>0<em>.</em>05</li>

   <li>0<em>.</em>30</li>

   <li>0<em>.</em>40</li>

  </ul></li>

 <li>(*) For <em>τ </em>= 0<em>.</em>1, generate a data set of size 20 by the procedure above and run the decision stump algorithm on the data set to get <em>g</em>. Repeat the experiment 10000 times, each with a different data set. What is the mean of <em>E</em><sub>out</sub>(<em>g,τ</em>) − <em>E</em><sub>in</sub>(<em>g</em>) within the 10000 results? Choose the closest value.

  <ul>

   <li>0<em>.</em>00</li>

   <li>0<em>.</em>02</li>

   <li>0<em>.</em>05</li>

   <li>0<em>.</em>30</li>

   <li>0<em>.</em>40</li>

  </ul></li>

 <li>(*) For <em>τ </em>= 0<em>.</em>1, generate a data set of size 200 by the procedure above and run the decision stump algorithm on the data set to get <em>g</em>. Repeat the experiment 10000 times, each with a different data set. What is the mean of <em>E</em><sub>out</sub>(<em>g,τ</em>) − <em>E</em><sub>in</sub>(<em>g</em>) within the 10000 results? Choose the closest value.

  <ul>

   <li>0<em>.</em>00</li>

   <li>0<em>.</em>02</li>

   <li>0<em>.</em>05<span style="text-decoration: line-through;">nbz</span></li>

   <li>0<em>.</em>30</li>

   <li>0<em>.</em>40</li>

  </ul></li>

</ol>