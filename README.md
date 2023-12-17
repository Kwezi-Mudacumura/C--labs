<h1>My C++ labs consists of the following programs: </h1>
<ul>
<li><h3>Upper.cpp</h3>This following program takes in a number of strings and convert them to their upper case variants.</br></br>
Input:</br>
The first line of input is a single number N, which specifies how many strings is inputted to
the program. N lines of input follow, with a single string on each line. The assumption is that the
strings do not contain spaces.</br>
Output:</br>
For each string received, the program outputs the input after it is converted to upper case.
</li>
  
<li>
<h3>prime2.cpp</h3> <p>A prime number is a number that has no positive divisors, aside from 1 and itself. A twin prime
is a prime number that is either 2 less or 2 more than another prime. The Twin Prime Conjecture,
attributed by some to Euclid (circa 300 BC), proposes that there are an infinite number of twin
primes. This is still an open problem in Number Theory.</p>
The following program takes in a number of integers and determine whether they are twin
primes.
</br></br>
Input:</br>
The first line of input is a single number N, which specifies how many positive integers will be
input to the program. N lines of input follow, with a single positive integer on each line.The assumption is each integer is greater than 2.</br>
Output</br>
For each number, the program outputs true if it is a twin prime. Otherwise, the program outputs false. 
</li>
  
<li>
<h3>percent.cpp</h3> The following program receives a list of non-negative numbers,then works out what percentage each number makes up of the
total list. Formally,the assumption is the program is given a list of numbers x1, x2, . . . xN.</br> </br>For each element xj ,
calculate:</br>
xj/∑(from i=1 to N)xi
</br>

Input:</br>
The first line of input is an integer N. N non-negative integers follow, each on their own line.</br>
Output:</br>
On their own line, the program outputs the percentage each number represents
</li>

<li>
<h3>Hi-Lo.cpp:</h3> The following program receives a list of numbers and determines the second largest and second smallest element.</br></br>
Input:</br>
The first line of input is a single integer N ≥ 2. N real numbers follow, one per line.</br>
Output:</br>
The program outputs the second smallest and second largest value on their own lines.
</li>

<li>
<h3>DynamicMatrix.cpp</h3> The following program uses a 2D
vector, representing a matrix initially populated with zeroes. Based on the user input,the program changes the value of some of these elements.</br></br>
Input:</br>
The first line of input consists of two integers: the number of rows and columns of the matrix.
The next line contains a single integer N, which specifies the number of lines to follow. Each of
the following N lines contains 3 integers in the format <row> <column> <value>. The program sets the element at this specified row and column to the given value. Note that the row
and column are zero-indexed.
</br>
Output:</br>
Display the resulting matrix in a grid, with the appropriate elements altered according to the
input received.
</li>

<li>
<h3>Marks.cpp</h3>The following program receives a list of names and grades and outputs the names in alphabetical order, with their associated
grade.</br></br>
Input:</br>
The first line of input is an integer N. N lines follow, each containing a name and a mark,
separated by a space. The assumption is that the name is a single word, and that the mark is an
integer.</br>
Output:</br>
The program outputs the names and associated grades in alphabetical order. Each name is separated
from its grade by a colon and single space.
</li>

<li>
<h3>GCD.cpp</h3>Euclid’s algorithm is an ancient method for calculating the greatest common divisor (GCD) of
two numbers. To calculate the GCD of two positive numbers x and y, we use the formula:</br>
gcd(x, y) = (x, if y = 0 ; gcd(y, x mod y), if y <> 0).</br>
The following program accepts two integers and computes their GCD using recursion.</br></br>
Input:</br>
Input consists of two positive integers x and y separated by a single space.</br>
Output:</br>
The program outputs the GCD of x and y. 
</li>

<li>
<h3>PascalTriangle.cpp</h3>Pascal’s triangle is a triangular array of the binomial coefficients. The first 5 rows of the triangle
are given below:(It may be easier to visualise if we left-align all the values)</br></br>
1</br>
1 1</br>
1 2 1</br>
1 3 3 1</br>
1 4 6 4 1</br></br>
<p>This reveals a pattern: the values of all elements in column zero are always 1, as are all the
elements along the diagonal. Otherwise, we can calculate the value of an element as the sum
of the element directly above it, and the element directly above it and one to the left.</p>
 The following program is a recursive function that accepts the row and column of an
element, and outputs the value of the element in Pascal’s triangle at that location.</br></br>
Input:</br>
Input is a single line consisting of two integers, the row and column, separated by a space.The assumption is that the row and column are valid entries in Pascal’s triangle. Note that rows
and columns are indexed starting at 0.</br>
Output:</br>
The program outputs the value of the element in Pascal’s triangle at the requested position.  
</li>

<li>
<h3>SecondMax.cpp</h3>Everyone knows that first is the worst, second is the best. The following program accepts a
series of real numbers and outputs the second largest number.</br></br>
Input:</br>
Input consists of a series of real numbers, one per line.The assumption is that at least two
numbers will be provided. The end of the input is signalled by the number −1. When the program
receives a −1, your program then outputs the correct answer and terminates. Note that −1
is completely ignored and thus is not taken into consideration when performing
the calculation.</br>
Output:</br>
Print the second largest number received
</li>

















  
</ul>
