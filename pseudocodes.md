## Pseudo codes
<details>
<summary>DANZU Template</summary>
 <a href="https://dhanushgopi.github.io/">Concept</a>
 <p>Just code template the write the documentation of the pseudo codes!</p> 
 <ol>
    <li>Add as many as you want!</li>
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






