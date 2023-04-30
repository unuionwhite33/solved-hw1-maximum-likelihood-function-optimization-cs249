Download Link: https://assignmentchef.com/product/solved-hw1-maximum-likelihood-function-optimization-cs249
<br>
As in HW0, the basic problem here is to determine, given an input sequence of real values, which distribution it follows. More specifically, for this assignment you are to develop a program that reads in a numeric table, and – for each dataset (i.e., each column in the table) – determines the distribution and parameters that gives the closest match to it.

<em>There are two differences between HW1 and HW0:</em>

<ol>

 <li><em>in HW1, the input data are always drawn from the Gamma distribution.</em></li>

 <li><em>in HW1, you must implement the Likelihood optimization yourself; you cannot use </em>fitdistr()<em>.</em></li>

</ol>

As in HW0, your program could be given an input table like this:

<table width="472">

 <tbody>

  <tr>

   <td width="79">D1</td>

   <td width="79">D2</td>

   <td width="79">D3</td>

   <td width="79">D4</td>

   <td width="79">D5</td>

   <td width="79">D6</td>

  </tr>

  <tr>

   <td width="79">3.3713903</td>

   <td width="79">6.2437282</td>

   <td width="79">0.2138276</td>

   <td width="79">0.1699299</td>

   <td width="79">1.5583491</td>

   <td width="79">0.6543210</td>

  </tr>

  <tr>

   <td width="79">2.7725880</td>

   <td width="79">5.5875745</td>

   <td width="79">0.4583172</td>

   <td width="79">0.3767378</td>

   <td width="79">2.8429449</td>

   <td width="79">1.9559299</td>

  </tr>

  <tr>

   <td width="79">…</td>

   <td width="79">…</td>

   <td width="79">…</td>

   <td width="79">…</td>

   <td width="79">…</td>

   <td width="79">…</td>

  </tr>

  <tr>

   <td width="79">7.2775941</td>

   <td width="79">5.2902876</td>

   <td width="79">0.9740191</td>

   <td width="79">2.6121070</td>

   <td width="79">5.9899608</td>

   <td width="79">6.7003783</td>

  </tr>

 </tbody>

</table>

The columns of this table define six datasets. Your program should produce a CSV file HW1_output.csv giving distributions that (it thinks) best fit the data. A correct output file could then look like this:

gamma,3,1 gamma,3,2 gamma,3,3 gamma,3,4 gamma,3,5 gamma,3,6

For simplicity, the parameters used in this assignment will always be integers, so the printed output should always have integer parameter values.

Your program can determine the distribution that fits best in any way you like. However, the notebook sketches a way to do this, and gives orientation about how to solve this problem in R.

In other words: yes, this is another simple assignment. It is intended as a warmup.

After running your program on the test input file HW1_test.csv, to complete this assignment please upload two files to CCLE:

<ol>

 <li>your output CSV file csv</li>

 <li>your notebook file ipynb</li>

</ol>

The notebook should have the commands you used to produce the output file. All assignment grading in this course will be automated, so please assume that when uploading files.

1