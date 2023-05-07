Download Link: https://assignmentchef.com/product/solved-lab-01-knowledge-check-cse-021
<br>
<h1>Getting Started</h1>

After starting Eclipse, create a new project called Lab21_01. Import FindDuplicateCount.java from the assignment page (right click the file and save into the project directory).




<strong>Part 1: Create </strong>RemainderFunc.java

This program asks for two inputs from the user:

<ul>

 <li>Max number, maxnum</li>

 <li>Divisor, divisor</li>

</ul>

Then it displays all numbers that are multiples of divisor starting at 1 up to maxnum (inclusive) as shown in the sample runs below. You must use the remainder (%) operation for this task.




<strong>Sample Runs (user input shown in </strong><strong>blue, with each run separated by a dashed-line): </strong>




<table width="672">

 <tbody>

  <tr>

   <td width="672">Please enter the max number: 10Please enter the divisor: 2Multiples of 2 between 1 and 10 (inclusive) are:246810——————————————————————————————Please enter the max number: -2Invalid input. Please enter a valid max number (&gt;= 0): -8Invalid input. Please enter a valid max number (&gt;= 0): 10Please enter the divisor: 3Multiples of 3 between 1 and 10 (inclusive) are:369——————————————————————————————Please enter the max number: 8Please enter the divisor: -2Invalid input. Please enter a valid divisor (&gt; 0): 0Invalid input. Please enter a valid divisor (&gt; 0): -5Invalid input. Please enter a valid divisor (&gt; 0): 10Multiples of 10 between 1 and 8 (inclusive) are:No number were found. ——————————————————————————————Please enter the max number: -9Invalid input. Please enter a valid max number (&gt;= 0): -10Invalid input. Please enter a valid max number (&gt;= 0): 25 Please enter the divisor: 0</td>

  </tr>

 </tbody>

</table>

Invalid input. Please enter a valid divisor (&gt; 0): 0

Invalid input. Please enter a valid divisor (&gt; 0): -8 Invalid input. Please enter a valid divisor (&gt; 0): 4 Multiples of 4 between 1 and 25 (inclusive) are:

4

8

12

16

20

24

<strong> </strong>

<strong>Part 2: Fill-in </strong>FindDuplicateCount.java

You are given an integer array (arr) declared in the program. Count all the numbers that are repeated in the array entries. If there are no duplicates then your program should output should print out according to the expected output below. If there is only one duplicate then the message should state that. Finally, for two or more duplicates then the output should match the expected output. Your solution should use loops (hint: nested loops) and should work for any integer array.




<strong>Expected Output: </strong>




<table width="671">

 <tbody>

  <tr>

   <td width="671">There are no duplicates with value 1 beyond index 0There are 3 more occurrences of value 2 starting at index 1There are 2 more occurrences of value 2 starting at index 2There are 2 more occurrences of value 3 starting at index 3There is only 1 more occurrence of value 4 starting at index 4There is only 1 more occurrence of value 2 starting at index 5There are no duplicates with value 4 beyond index 6There is only 1 more occurrence of value 3 starting at index 7There are no duplicates with value 0 beyond index 8There are no duplicates with value 5 beyond index 9</td>

  </tr>

  <tr>

   <td width="671">There are no duplicates with value 3 beyond index 10There are no duplicates with value 2 beyond index 11</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<h1>Part 3: (Assessment) Logic Check</h1>

Create a Word document or text file named Part3 that contains answers to the following:

<ol>

 <li>When did you take CSE-020?</li>

 <li>How long did this lab take to finish?</li>

 <li>Any difficult topics for you in these two exercises? If so list them:</li>

 <li>For the array given in java, which index is the last check we need to make to count all the duplicates?</li>

 <li>Interpret the number 101010 in bases 2, 10, 16. For each, convert to the other two bases (for example, when interpreting as base 2, convert to bases 10 and 16; when interpreting as base 10, convert to bases 2 and 16; etc.).</li>

</ol>


