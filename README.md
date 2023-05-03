Download Link: https://assignmentchef.com/product/solved-cs212-lab-23-recursive-programming
<br>
<span class="kksr-muted">Rate this product</span>

Recursive Programming.

Create a new Eclipse project for Lab23.

Write a recursive method that will determine if a given String is a palindrome (a string that reads the same forwards and backwards (except for spaces, etc.).

For example,

<pre>        isPalindrome("noon");</pre>

would return true.Remember, you need a base case (the empty String is a palindrome, the null String is

not.)Recursive case: A String is a palindrome if the first and last letters are the same, and the

String that remains after removing the first and last letters is a palindrome. For example, “noon” -&gt; “noon” -&gt; “oo” -&gt; “”Hint: To break up the String, substring(“noon”,1,4) is “oo”.What about the spaces? Ignore them by proceeding to the next recursive call.

<pre>                              "Madam, I'm Adam"                               "adam, I'm Ada"                                "dam, I'm Ad"                                 "am, I'm A"                                  "m, I'm "                                  "m, I'm"                                    ", I"                                    " I"                                     "I"                                     ""</pre>

You may also find these methods from the wrapper class Character helpful:

Character.isLetter(char ch) Character.toUpperCase(Char ch)

Character.toUpperCase(‘M’) is equal to Character.toUpperCase(‘m’)

Try your program on strings that are not palindromes, as well as the following: “noon”,”Madam I’m Adam”, “A man, a plan, a canal, Panama”, “A Toyota”