# cmpe230-project-1-solved
**TO GET THIS SOLUTION VISIT:** [CMPE230 Project 1 Solved](https://www.ankitcodinghub.com/product/cmpe230-project-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93960&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPE230 Project 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this project, you will implement a translator for a language called MatLang that will translate MatLang code to C language code. The C language code generated can then be compiled by a C compiler to produce an executable file.

MatLang language statements will be as follows:

<ol>
<li>Matlang programs will have two sections: The first will be a variable definitions section,
followed by the executable statements section.
</li>
<li>Variable definitions section will allow scalar, one-dimensional, two dimensional number
variable definitions. For example:

scalar x vector y[4] matrix z[3,4]

Assume all array dimensions are given as integer constants. In the above example x is a scalar variable, y is a vector (i.e. matrix of size 4×1) and z is a 3×4 matrix. Assume that each line contains a single definition. A definition cannot be written on more than one line.
</li>
<li>Executable statements will consist of one line statements and for loop compound statements. Note that no nested for loops are allowed.</li>
<li>One line statements are either assignment statements or print statements which print the value(s) of a scalar, vector, or a matrix variable or a separator.</li>
<li>A vector or a matrix varieble can be assigned values in curly brackets. Note that such assignment should fit on line. For the vector y[4] and z[3,4], the following example
assignment can be made:

y={1234}

z ={1234532221 01} Note that array indices start with 1.
</li>
<li>There are no if statements in the language.</li>
<li>As operations in expressions, you are required to implement only multiplication, addition
and subtraction: *,+,- . These are binary operand operations. Unary minus operation is not supported. Note that these are to be interpreted as either matrix or scalar operations depending on the context (i.e. type of operands). When a scalar expression multiplies a matrix or a vector, its meaning is multiplication of each individual component of a matrix or vector.
</li>
<li>A function tr(expr) is also available which transposes a scalar, vector or a matrix.</li>
<li>A function sqrt(expr) is also available which takes square root of a scalar expression.</li>
<li>A function choose(expr1,expr2,expr3,expr4) which returns expr2 if expr1 is equal
to 0, returns expr3 if expr1 is positive and returns expr4 if expr1 is negative.

Note that expr1, expr2, expr3 and expr4 are expressions that evaluate to a scalar.
</li>
<li>On a line, everything after the # sign are considered as comments.</li>
<li>For loop will have the following formats:
for (id in expr1:expr2:expr3) { …..

….. }

Here,idisa variable,expr1isstartingvalueofid,expr2istheboundonthevalueofid during the loop iteration and expr3 is the added value to id at each iteration.

For loop can also have the following syntax:

for (id1,id2 in expr1:expr2:expr3, expr4:expr5: expr6) { …..
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
….. }

This will be equivalent to doubly nested loops in languages like C/Java. You can assume that the values of ids id1,id2 and expressions expr1,expr2,expr3,expr4,expr5

and expr6 cannot be changed inside the for loop body. You can also assume that expr1 &lt; expr2 and expr4 &lt; expr5 and that expr3 and expr6 evaluate to a

positive value.

<ol start="13">
<li>print(id) statement, prints the value of variable id.</li>
<li>printsep() statement, prints a separator line “———-“</li>
</ol>
15. Please note that the C code generated must compute the MatLang outputs. You should not

generate C code that just prints MatLang program outputs.

Some example programs in the MatLang language are given below. Note that MatLang language programs have .mat extension.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
ex1.mat

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Output when compiled and executed

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# this program computes fibonacci # numbers

# variable definitions scalar i

scalar n

vector x[2]

vector y[2] matrix A[2,2] matrix B[2,2]

# statements

n = 10 x={11} A={1110} B={1001} print(x)

for(i in 1:n:1) { B = A*B

y = B*x

print(y[1]) }

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>1
1
2
3
5
8
13
21
34
55
89
144
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
ex2.mat

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Output when compiled

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# variable definitions vector z[3]

vector y[4]

matrix A[2,2]

matrix B[2,3] z = A*B*y

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Error (Line 6): matrix dimensions in expression do not match.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
ex3.mat

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Output when compiled and executed

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# simple pageranking # algorithm

matrix A[3,3]

matrix T[1,1]

vector x[3] vector y[3] scalar r scalar i

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0.7071068 0.6123724 0.4677072 0.3852759 0.3093592 0.2509747 0.2028243 0.1641555 0.1327838 0.1074308

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 3">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
A={0.5 00.5000.50.510} x={111}

for(i in 1:10:1) {

y = A*x

T = tr(y-x)*(y-x) r = sqrt(T[1,1]) print(r)

x=y

} printsep() print(x)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
———— 1.2148438 0.6240234 1.1611328

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
ex4.mat

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Output when compiled and executed

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
matrix A[4,4]

matrix T[1,1]

vector x[4] vector xy2[4] scalar s

A = {0 1 2 3 4 5 6 7 8 9 1 1 1 2 3 4 } x = {1 1 1 1 }

xy2 = { 2 1 3 1 }

print(s)

</div>
</div>
<div class="layoutArea">
<div class="column">
T = tr(x)*A*xy2

</div>
</div>
<div class="layoutArea">
<div class="column">
s = T[1,1]

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
94

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
ex5.mat

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Output when compiled and executed

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# count how many elements are # greater than or equal to 4 matrix A[4,4]

scalar count

scalar incr scalar i scalar j

A = {0 1 2 3 4 5 6 7 8 9 1 1 1 2 3 4} count = 0

for (i,j in 1:4:1,1:4:1) {

incr = choose(A[i,j]-4,1,1,0)

count = count + incr }

print(count)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Your project will be graded according to the following criteria:

Documentation (written document describing 12% how you implemented your project)

Comments in your code 8% Implementation and tests 80%

</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
