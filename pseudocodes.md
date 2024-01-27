## Pseudo codes
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
