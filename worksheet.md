
# Computer Science I 
## Lab 2.0 Worksheet

Name(s) and Login(s):
saifullah
saifapsff@gmail.com


1. Dennis Ritchie, the creator of the C programming language,
was born on September 9th, 1941.  If he were still alive,
how old would he be today?  Find out by running the `birthday`
program on the appropriate inputs and enter your solution here.

Answer:   First Name (no spaces) : DennisRitchie
 the year in which you were born: 2002
the month in which you were born (1-12): 9
 the day of the month in which you were born (1-31): Today is 2023/10/11
Hello, Dennis.  You are 23 years, 4 weeks, and 3 days old today

2. Bjarne Stroustrup, the creator of the C++ programming
language, the object-oriented extension of C, was born on
December 30th, 1950.  How old is he today?

Answer: First Name (no spaces) followed by ENTER: Bjarne
 the year in which you were born: 2002
 the month in which you were born (1-12): 12
the day of the month in which you were born (1-31): 30
Today is 2023/10/11
Your birthday was 2002/12/30
Hello, Bjarne.  You are 20 years, 40 weeks, and 5 days old today



3. Software testing often involves testing code with known
"bad" input in an attempt to break it (sometimes this is
referred to as *fuzzing*).  Try breaking the `birthday_cli`
program by giving it "bad" input and observe the consequences.
Give at least two examples of potentially bad input and the
results you observe.
 
Answer : Today is 2023/10/21 Your birthday was Hello, saif. You are 0 years, 0 weeks, and 0 days old today




4. Complete all the size and range entries below.

* `char`
  size: 1 byte
  range: -128 to 127
* `short int`
  size: 2 bytes.
  range: -32768 to 32767.
* `int`
  size:4 bytes
  range: -2147483648 to 2147483647
* `long int`
  size: 4 bytes
  range: -2147483648 to 2147483647
* `float`
  size:  4 bytes
  range: 7 digits of accuracy
* `double`
  size: 8 bytes
  range: 15 digits of accuracy


5. Use your working currency conversion to determine
the exchange amounts for the following inputs:

  a) $250.25
Exchange tax = 25.02    
In british pound = 88.96
In Japanese yen = 14375 
  b) $1,000.52
Exchange tax = 100.05    
In british pound = 355.68
In Japanese yen = 57472 
  c) $968,410.12
Exchange tax = 96.80     
In british pound = 344.12
In Japanese yen = 55604


6. Suppose that you had used only `int` types
in your conversion program.  Would you be able
to use it to convert the US national debt
(which as of 2020 was \$26,009,754,625,487)?
Why or why not?
No it a big value and it cannot be inserted in int we will need long int to put this value



7. Mixed types

a) Run the `area` program with 3 and 4 as inputs.  
What value do you get?  Is this result correct?

Answer: The area is 0.000000 square units. No this result is not correct.


b) Execute the program again with inputs 3 and 5.
Does the program give correct results?  Why not?

Answer: The area is 0.000000 square units. No answer is not correct because the formula of area is 1\2 * length * width and compiler considers 1\2 as zero so it gives every value zero


c) Fix the program by editing the `area.c` source
code so that the program produces correct results.

Answer: Done
