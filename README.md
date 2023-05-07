Download Link: https://assignmentchef.com/product/solved-math3315_cse3365-project-1
<br>
<strong>Project Description</strong>

This project studies numerical errors, which are composed of two parts: the <em>roundoff errors </em>and the <em>truncation errors</em>. We will first work on the truncation errors by numerically approximating the second derivative of a given function at a point with two methods of different accuracy as in a) and b). Following that, in c) we will keep on reducing the truncation error (using smaller and smaller <em>h</em>) until roundoff error in Matlab starts to dominate the truncation error.

<ol>

 <li>Recall that given function <em>f</em>(<em>x</em>), the second order derivative of <em>f</em>(<em>x</em>), <em>f</em><sup>00</sup>(<em>x</em>) can be approx<em>h h</em></li>

</ol>

imated by the forward difference approximation,.

Let <em>f</em>(<em>x</em>) be a function of your pick (do not use <em>f</em>(<em>x</em>) = <em>e<sup>x</sup></em>), and compute <em>f</em><sup>00</sup>(<em>x</em>) numerically at <em>x </em>= <em>a </em>of your pick with <em>h </em>= 0<em>.</em>1<em>,</em>0<em>.</em>05<em>,</em>0<em>.</em>025<em>,</em>0<em>.</em>0125<em>,</em>0<em>.</em>00625<em>,</em>0<em>.</em>003125. Present a table with the following format. column 1: <em>h</em>, column 2: ), column 3: ), column 4: (<em>f</em><sup>00</sup>(<em>a</em>) − <em>D</em><sub>+</sub><em>f</em><sup>2</sup>(<em>a</em>))<em>/h</em>, column 5: (. column 6: order. Output your table in a <em>professional </em>way by formatting the tabular data appropriately.

<ol>

 <li>Repeat for the centered difference approximation,, which also approximates <em>f</em><sup>00</sup>(<em>x</em>).</li>

 <li>Modify the Matlab code given in class to plot the error in) and ) for step size <em>h </em>= 1<em>/</em>2<em><sup>j </sup></em>with <em>j </em>= 0 : 64. Use log scales for the error |<em>f</em><sup>00</sup>(<em>a</em>) − <em>D</em><sup>2</sup><em>f</em>(<em>a</em>)| and step size <em>h</em>. Plot both cases on the same graph in a <em>professional </em> (hint: use “hold on” command).</li>

</ol>

<strong>Project Specification</strong>

Your project submission is composed two parts: the paper submission and the e-submission. The paper submission includes 1) (hand written or print) the front page with project title, course, section, date, name, department/program, etc.; 2) (hand written or print) the page for deriving the convergence order of) and); 3) (print) the published results which should be divided into sections and include comments in discussing the pattern observed from tables and graphs. Note the discussion will contribute significantly to your project score thus please be comprehensive, precise, and concise. The e-submission is the matlab code (in one .m file) uploaded via link provided from Canvas. I will grade on the paper submission but will download and run your code when needed.

Note: You can discuss the project with each other but coding must be finished <em>independently</em>.