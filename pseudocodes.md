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
