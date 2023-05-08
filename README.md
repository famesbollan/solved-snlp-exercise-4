Download Link: https://assignmentchef.com/product/solved-snlp-exercise-4
<br>
<h3>1) Information content</h3>

Assume that the probability of being male is <em>p</em>(<em>M</em>) = 0<em>.</em>5 and so likewise for being female <em>p</em>(<em>F</em>) = 0<em>.</em>5. Suppose that 20% of males are T (i.e. tall) and that 6% of females are tall.

Calculate the probability that if somebody is “tall” (meaning taller than 6 ft or whatever), that person must be male.

Now, if you know that somebody is male, how much information do you gain (in bits) by learning that he is also tall? How much do you gain by learning that a female is tall? Finally, how much information do you gain from learning that a tall person is female?

<strong>2</strong>) <strong>Entropy </strong>

Consider a binary symmetric communication channel (see figure 1), whose input source is the alphabet <em>X </em>= 0<em>,</em>1 with probabilities 0<em>.</em>5<em>,</em>0<em>.</em>5; whose output alphabet is <em>Y </em>= 0<em>,</em>1 and the channel is:

Figure 1: Binary symmetric communication channel with inputs <em>X </em>on the left side, outputs <em>Y </em>on the right side and <em>p </em>is the probability of transmission error.

<ul>

 <li>What is the entropy of the source, <em>H</em>(<em>X</em>)?</li>

 <li>What is the probability distribution of the outputs, <em>p</em>(<em>Y </em>), and the entropy of this output distribution, <em>H</em>(<em>Y </em>)?</li>

 <li>What is the joint probability distribution for the source and the output, <em>p</em>(<em>X,Y </em>), and what is the joint entropy, <em>H</em>(<em>X,Y </em>)?</li>

 <li>(0.5 points) What is the mutual information of this channel, <em>I</em>(<em>X</em>;<em>Y </em>)? See: <a href="https://en.wikipedia.org/wiki/Mutual_information">https://en.wikipedia.org/wiki/Mutual</a> <a href="https://en.wikipedia.org/wiki/Mutual_information">information</a></li>

</ul>

<h3>3) Kullback-Leibler Divergence</h3>

First, provide proof that the Kullback-Leibler Divergence does not follow the triangle inequality and thus cannot be considered a true distance metric .

Now, let the random variable <em>X </em>have three possible outcomes <em>a,b,c</em>. Consider two distributions on this random variable:

<table width="149">

 <tbody>

  <tr>

   <td width="63">Symbol</td>

   <td width="51"><em>p</em>(<em>x</em>)</td>

   <td width="35"><em>q</em>(<em>x</em>)</td>

  </tr>

  <tr>

   <td width="63">a b c</td>

   <td width="51"></td>

   <td width="35"></td>

  </tr>

 </tbody>

</table>

Calculate <em>H</em>(<em>p</em>), <em>H</em>(<em>q</em>), <em>D</em>(<em>p</em>||<em>q</em>) and <em>D</em>(<em>q</em>||<em>p</em>). Verify that in this case <em>D</em>(<em>p</em>||<em>q</em>) 6= <em>D</em>(<em>q</em>||<em>p</em>) .

<strong>4</strong>) <strong>Codes </strong>

Consider the following source alphabet and its letter probabilities:

<h4>                                                             A      B      C      D</h4>

<ul>

 <li>What is the entropy H, in bits, of the above source alphabet?</li>

 <li>Why are fixed length codes inefficient for alphabets whose letters are not equiprobable? Discuss this in relation to Morse Code.</li>

 <li>Offer an example of a uniquely decodable prefix code for the above alphabet. What features make it a uniquely decodable prefix code?</li>

</ul>

<h3>5) Martian codes and Kraft’s inequality</h3>

Martians have landed on earth and you have found one of their code books. In it you find a code entry of the form:

The <em>S<sub>i</sub></em>’s are encoded into strings from a D-symbol output alphabet in a uniquely decodable manner. If <em>m </em>= 6 and the code word lengths are (<em>l</em><sub>1</sub><em>,l</em><sub>2</sub><em>,…,l</em><sub>6</sub>) = (1<em>,</em>1<em>,</em>2<em>,</em>3<em>,</em>2<em>,</em>3), what is the most likely base for the Martian code (i.e. what is a good lower bound for D)?