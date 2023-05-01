Download Link: https://assignmentchef.com/product/solved-cecs328-hw4
<br>
<strong>Homework assignment 4:  </strong>




<ul>

 <li>Suppose a machine on average takes 10<sup>-8</sup> seconds to execute a single algorithm step. What is the largest input size for which the machine will execute the algorithm in 2 seconds assuming the number of steps of the algorithm is T(n) = a. log n

  <ol>

   <li><em><sup>n</sup></em></li>

   <li>n</li>

   <li>n<sup>2</sup></li>

   <li>n<sup>3</sup></li>

   <li>2<sup>n</sup></li>

  </ol></li>

</ul>




<ul>

 <li>For the machine in the previous example, how long will it take to run the algorithm for an input of size 1,000, assuming the time complexities from the same example?</li>

</ul>




<ul>

 <li>An algorithm takes <em>5</em> seconds to run on an input of size <em>100</em>. How long will it take to run on an input of size <em>1000</em> if the algorithm has a running time that is <em>linear? quadratic? log-linear? cubic? </em></li>

</ul>




<ul>

 <li>An algorithm is to be implemented and run on a processor that can execute a single instruction in an average of <em>10<sup>-9</sup></em> What is the largest problem size that can be solved in <em>one hour </em>by the algorithm on this processor if the number of steps needed to execute the algorithm is <em>n, n<sup>2</sup>, n<sup>3</sup>, log n?</em> Assume n is the input size.</li>

</ul>




<ul>

 <li>Determine the asymptotic running time for the following piece of code, assuming that n represents the input size.</li>

</ul>




<ol>

 <li>sum = 0;</li>

</ol>

for(i=0; i &lt; n; i++)

sum++;







<ol>

 <li>sum=0;</li>

</ol>

for(i=0;i&lt;n;i++)

for(j=0; j&lt; n*n;j++) sum++;







<ol>

 <li>sum=0;</li>

</ol>

for(i=0;i&lt;n;i++)

for(j=0; j&lt; i;j++)

sum++;







<ol>

 <li>sum = 0;</li>

</ol>

for(i=0; i &lt; n; i++) for(j=0; j &lt; i*i; j++)

for(k=0; k &lt; j; k++)

sum++;

<ol>

 <li>sum = 0;</li>

</ol>

for(i=0; i &lt; n/2; i++)

for(j=0; j &lt; (i*i)/2; j++)

sum++;




<ol>

 <li>for(i=0; i &lt; length(a) ; i++) binary_search(a, a[i]); //key = a[i]</li>

</ol>




<ol>

 <li>for(i=0; i &lt; n; i++) for(j=0; j &lt; n; j++)</li>

</ol>

linear_search(a, key); //key is not in array, length(a) == n







<ul>

 <li>What is the <em>largest</em> value of <em>n</em> such that an algorithm whose running time is 10n<sup>2</sup> runs faster than an algorithm whose running time is <em>50n</em> on the same machine?</li>

</ul>


