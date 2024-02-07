## Pseudo codes
<details>
<summary>DANZU Template</summary>
 <a href="https://dhanushgopi.github.io/">Concept</a>
 <p>Just code template the write the documentation of the pseudo codes!</p> 
 <ol>
  <li>Start the program</li>
    <li></li>
  <li>Stop the program</li>
  </ol>
</details>
<details>
<summary>Reverse a number and some of its digits </summary>
 <a href="https://medium.com/@ManBearPigCode/how-to-reverse-a-number-mathematically-97c556626ec6">Concept</a>
  <ol>
    <li>get the number</li>
    <li>create a var to store reverse number.</li>
    <li>create a var to store the summation number.</li> 
    <li>while num is not equal to zero, the enter the module.</li>
    <li>"num % 10" - gets the last number.</li>
    <li>"rev_num * 10 + digit" - adding up in reverse positional.</li>
    <li>"num // 10" - removes the last digit.</li>
    <li>"sum_num += digit" - summing up the last digit.</li>
    <li>print the reverse number and summation number.</li>
  </ol>
</details>

<details>
<summary>Armstrong Number </summary>
 <a href="https://pages.mtu.edu/~shene/COURSES/cs201/NOTES/chap04/arms.html">Concept</a>
  <p>sample numbers : 0, 1, 153, 370, 371, 407 1634, 8208 and 9474</p>
  <ol>
    <li>get the number a string</li>
    <li>create a "temp" var and store the getted str as int</li>
    <li>create a "arm" var to store the summation of squares.</li>
   <li>while temp is not equal to proceed in the module.</li>
    <li>"digit = temp % 10" - gets the last number.</li>
    <li>"squares = digit**len(str)" - digit gets squared by the len of the given digits</li>
    <li>"temp // 10" - removes the last digit for and make the next loop to access the next number.</li>
    <li>"arm+=squares" - summing up the last digit.</li>
   <li>if arm equals with the given number.</li>
    <li>print the Armstrong Number.</li>
   <li>else no</li>
  </ol>
</details>

<details>
<summary>Check it's a Prime or Not</summary>
 <a href="https://www.cuemath.com/numbers/prime-numbers/">Concept</a> 
 <p> "n" number will be get divisible by the "n" times and any of the divisibles gives "remainder as zero" it will be a "composite number". else it will be a "Prime Number"</p>
 <ol>
    <li>Get the number as int and store in a var as "number".</li>
    <li>Create a var as "flag" to store the flag value./li>
    <li>create a "for loop" and initiate from 2 to "number".</li>
    <li>"if number % i == 0". then, increment the flag.</li>
    <li>Break the loop.</li>
    <li>"if flag == 1" it's a Composite Number</li>
    <li>Else it will be a Prime Number</li>
  </ol>
</details>
<details>
<summary>Check its a Perfect Number or Not</summary>
 <p><a href="https://www.cuemath.com/numbers/perfect-numbers/">Concept</a></p>
 <p><a href="https://www.splashlearn.com/math-vocabulary/division/divisor">What is Divisor?</a></p>
 <p>The given number should be equal to the sum of it divisors is known as Perfect number. ex: 6, 1+2+3 = 6 </p> 
 <ol>
  <li>starts</li>
    <li>Get the "number"</li>
    <li>Create a "sum" var to hold the summation of the divisor</li>
  <li>Initate a "for loop" from "1 to number"</li>
  <li>if the "number % i == 0", then "sum" will increment by the "i" for the summation of the divisor and loops end.</li>
  <li>if "sum = number", then its a perfect number else it is a not perfect number</li>
  <li>Stops</li>
  </ol>
</details>


<details>
<summary>Check the between of number are Perfect Number or Not</summary>
 <a href="https://www.cuemath.com/numbers/perfect-numbers/">Concept</a>
 <p>The given number should be equal to the sum of it divisors is known as Perfect number. ex: 6, 1+2+3 = 6 </p> 
 <p>Just code template the write the documentation of the pseudo codes!</p> 
 <ol>
    <li>Get the "start" number and "end" number</li>
  <li>Create a "sum" to hold the summation of the divisor</li>
  <li>create a empty "list" to hold the founded perfect number</li>
  <li>Create "for loop with j" from "start to end+1"</li>
  <li>Create a another "for loop with i" from "1 to j"</li>
  <li> "j loop" is used to generate the "numerator" and "i loop" is used to generate the "denominator or divisors"</li>
  <li>Create a var "divisor" to perform the "j%i"</li>
  <li>if the "divisor == 0", then i variable will get added in the "sum" and both i and j loop ends</li>
  <li>if, "sum == j", then "j" will append in the "list" and "sum" will be made to "0" for the next "numerator or j"</li>
  <li>else, "sum" will be made to "0" for the next "numerator or j" </li>
  <li>Print the "List"</li>
  <li>Ends</li>
  </ol>
</details>
<details>
<summary>Swap the first and last elements in a list</summary>
 <a href="https://dhanushgopi.github.io/">Concept</a>
 <ol>
    <li>Start the program</li>
    <li>Creating a "genlist()" function to generate the list</li>
    <li>Inside the function, create a var "listlen" to get the length of the list</li>
    <li>A empty list "finallist" to hold the all elements</li>
    <li>Creating a "for i loop" in the range from "1 to listen" to append the each element in the "finallist".</li>
    <li>Inside the i loop, "listvalue" used to get the value for the list.</li>
  <li>"append" method will be used to append in the "finallist".</li>
  <li>outside the i loop, "finallist" will be "return and printed."</li>
  <li>"genlist()" stop</li>
  <li>create a "swapstart2end(list)" function and pass a formal paramter</li>
  <li> "a" var to hold the "list[0]"starting element and "b" var to hold the "list[-1]"last element in the list</li>
  <li>Remove the elements using the "index position" from the "list"</li>
  <li>"insert" method is used to insert the first element and "append" method is used to appended in last</li>
  <li>print and return the "list"</li>
  <li>"swapstart2end()" stop</li>
    <li>stop the program</li>
  </ol>
</details>


<details>
<summary>Sorting the elements in Ascending Order using Bubble Sort</summary>
 <a href="https://www.geeksforgeeks.org/bubble-sort/">Concept</a> 
 <ol>
  <li>Start the program</li>
    <li>Creating a "genlist()" function to generate the list</li>
    <li>Inside the function, create a var "listlen" to get the length of the list</li>
    <li>A empty list "finallist" to hold the all elements</li>
    <li>Creating a "for i loop" in the range from "1 to listen" to append the each element in the "finallist".</li>
    <li>Inside the i loop, "listvalue" used to get the value for the list.</li>
  <li>"append" method will be used to append in the "finallist".</li>
  <li>outside the i loop, "finallist" will be "return and printed."</li>
  <li>"genlist()" stop</li>
    <li>Create the "bubblesort()" function and pass the formal argument as "listhere"</li>
  <li>Inside the "bubblesort", create a var "listduplicate" and copy the entire elements from the "genlist()" function/li>
   <li>  create a for "i loop" from "0 to len(listduplicate)" to access the starting index element in the "listduplicate".</li>
  <li>Inside the "i loop", create an another for "j loop" from "i+1 to len(listduplicate)".</li>
  <li>Inside the "j loop", create a if condition to check the two adjacent elements as " listduplicated[i] >= listduplicated[i]" then, need to be swap there places.</li>
  <li>Swapping or interchanging the elements using the "temp" var.</li>
  <li>Then, print and return the "listduplicate" outside of the both "i and j loop"</li>
  <li>Program Stopped</li>
 </ol>
</details>

<details>
<summary>Falling Steps Pattern</summary>
 <a href="https://dhanushgopi.github.io/">Concept</a>
 <p>Just code as i wished to print the pattern</p> 
 <ol>
    <li>Start the program</li>
  <li>Create function as "fallingsteps()".</li>
  <li>Inside the function, create a var for the "pattervalue" and create a empty list as "patternholder" to hold the "pattervalue"</li>
  <li>Create a var to get the length of the patter "patternlength".</li>
  <li>Create a for 'i loop' from '0 to patternlength' for the increment of the pattern and append() used to add the element in the "patternholder" and 'i loop' ends</li>
  <li>Create a for 'j loop' from '0 to patternlength' for the decrement of the pattern and pop() used to remove the last element in the 'patternholder' and j loop 
 ends</li>
  <li>Stop the program</li>
  </ol>
</details>

<details>
<summary>Check Odd or Even for the given number and print with no duplication.</summary>
 <a href="https://dhanushgopi.github.io/">Concept</a>
 <ol>
  <li>Start the program</li>
    <li>Creating a "genlist()" function to generate the list</li>
    <li>Inside the function, create a var "listlen" to get the length of the list</li>
    <li>A empty list "finallist" to hold the all elements</li>
    <li>Creating a "for i loop" in the range from "1 to listen" to append the each element in the "finallist".</li>
    <li>Inside the i loop, "listvalue" used to get the value for the list.</li>
  <li>"append" method will be used to append in the "finallist".</li>
  <li>outside the i loop, "finallist" will be "return and printed."</li>
  <li>"genlist()" stop</li>
  <li>create function as "oddoreven()" and pass a formal argument as "listpassed"</li>
  <li>Create a two new list as respective "even and odd" to hold the elements.</li>
  <li>inside the oddoreven() function, create a for "j loop" from "0 to len(listpassed)" for access the element in the "listpassed".</li>
  <li>inside the "j loop", create elif block to check the accessed element is already in the "even an odd list"</li>
  <li>Inside the else, create another if else statement to check the accessed element is Odd or Even.</li>
  <li>append method is used to added the even elements to the even list and vice versa</li>
 <li>Print and return the Even and Odd list.</li>
  <li>Stop the program</li>
  </ol>
</details>

<details>
<summary>Rock Paper Scissor Game</summary>
 <a href="https://realpython.com/python-rock-paper-scissors/#play-a-single-game-of-rock-paper-scissors-in-python">Concept</a> 
 <ol>
  <li>Start the program</li>
   <li>import the random module to use the random methods.</li>
<li>create a list as 'cards' and hold the rock, paper, scissor values.</li>
<li>create two var as 'userscore and enemy score' to hold the score.</li>
<li>Using while make it loop, if the both scores are less than 3 proceed to the loop block</li>
<li>get the "user" value in a var and covert into lower case using "lower()" method</li>
<li>create a var as 'Enemy' to hold the random value from the "card"</li>
<li>If both are equal, print tie</li>
<li>elif user = 'rock', inside if has "enemy = scissor" then, print rock won. else, scissor is won </li>
<li>elif user = 'paper', inside if has "enemy = rock" then, print paper won. else, rock is won  </li>
<li>elif user = 'rock', inside if has "enemy = scissor" then, print rock won. else, scissor is won  </li>
<li>elif user = 'scissor', inside if has "enemy = paper" then, print scissor won. else, paper is won  </li>
<li>On each elif, respective score will be incremented</li>
<li>else, failed to give proper input</li>
<li>Both scores will be printed</li>
<li>If else block is used to print the winner!</li>
  <li>Stop the program</li>
  </ol>
</details>


<details>
<summary>Generate List of values</summary>
 <a href="https://dhanushgopi.github.io/">Concept</a>
 <ol>
  <li>Start the program</li>
    <li>Creating a "genlist()" function to generate the list</li>
    <li>Inside the function, create a var "listlen" to get the length of the list</li>
    <li>A empty list "finallist" to hold the all elements</li>
    <li>Creating a "for i loop" in the range from "1 to listen" to append the each element in the "finallist".</li>
    <li>Inside the i loop, "listvalue" used to get the value for the list.</li>
  <li>"append" method will be used to append in the "finallist".</li>
  <li>outside the i loop, "finallist" will be "return and printed."</li>
  <li>Stop the program</li>
  </ol>
</details>


<details>
<summary>Fibonacci Series for the Nth Number</summary>
 <a href="https://en.wikipedia.org/wiki/Fibonacci_sequence">Concept</a>
 <ol>
  <li>Start the program</li>
    <li>Create a function as "fibonacciseries".</li>
  <li>Inside the function, create a list "fiblist" to hold the Fibonacci series.</li>
  <li>declare var as a = 0, b = 1, c = 0 and the append the a and b in "fiblist". </li>
  <li> create a var "lenvalue" to get the int value.</li>
  <li>Create a for "i loop" from "1 to lenvalue" to perform the fibonacci logic. </li>
  <li>inside the i loop, exchanging the values for iteration as follows "c = a+b", "a = b", "b = c" and the append the c in "fiblist"</li>
  <li>decalre the Return of fiblist outside of the loop.</li>
  <li>Stop the program</li>
  </ol>
</details>
