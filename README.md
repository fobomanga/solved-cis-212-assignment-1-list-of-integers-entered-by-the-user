Download Link: https://assignmentchef.com/product/solved-cis-212-assignment-1-list-of-integers-entered-by-the-user
<br>
Write a Java program that calculates the sum of a list of integers entered by the user. You will repeatedly prompt the user to enter a letter or an integer, and then print the sum, clear the sum, add the integer to the sum, or quit the program.

<ol>

 <li> Display the text to ask the user for the input. You should indicate to the user that entering p will print the current sum, r will reset the current sum, q will quit the program, and i to add an integer to the sum. It looks like this:</li>

</ol>

Enter p to print, r to reset, q to quit, and i to add an integer:

<ol start="2">

 <li> The user entered a letter. Read the user’s input.</li>

 <li> If the user entered a letter other than p, r, q, and i, ignore it and then prompt the user for another input. (It is capitalization sensitive here, so R is not r, and vice versa, for example.)</li>

 <li> If the user entered p, print the current sum and then prompt the user for another input.</li>

 <li> If the user entered r, set the current sum to 0, print 0, and then prompt the user for another input.</li>

 <li> If the user entered q, print the current sum and then quit the program.</li>

 <li> If the user entered i, prompt the user for the integer. It looks like this:</li>

</ol>

Enter the integer:

<ol start="8">

 <li>Afterwards, the user entered an integer. Read it and add it to the current sum, and then prompt the user for another input.</li>

 <li> Write codes that are clear and efficient. Specifically, your codes should be indented with respect to code blocks, avoid unnecessarily repetitive codes, avoid codes that are commented out or otherwise unused, use descriptive and consistent class/method/variable names, etc.</li>

</ol>

Here’s the output from a sample run:




Enter p to print, r to reset, q to quit, and i to add an integer:

p

Sum: 0

Enter p to print, r to reset, q to quit, and i to add an integer:

i

Enter the integer:

1




Enter p to print, r to reset, q to quit, and i to add an integer: i

Enter the integer:

2

Enter p to print, r to reset, q to quit, and i to add an integer: i

Enter the integer:

-4

Enter p to print, r to reset, q to quit, and i to add an integer:

p

Sum: -1

Enter p to print, r to reset, q to quit, and i to add an integer: i

Enter the integer:

-2

Enter p to print, r to reset, q to quit, and i to add an integer:

p

Sum: -3

Enter p to print, r to reset, q to quit, and i to add an integer: i

Enter the integer:

4

Enter p to print, r to reset, q to quit, and i to add an integer:

s

Enter p to print, r to reset, q to quit, and i to add an integer: r

Sum: 0

Enter p to print, r to reset, q to quit, and i to add an integer: q Sum: 0


