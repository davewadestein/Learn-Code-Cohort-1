# Learn-Code-Cohort-1
## Homework
#### user input practice
* get a price, number of items, and tax rate in %age from the user (e.g. 19.95, 35, 9.5)
  * then print out the total cost (price * number_of_items + (number_of_items * tax_rate / 100.0))
* get birth year from user and future year
  * print out current age, and age in that future year
#### loops practice
* ask user how many student are in the class?
  * get a name for each student, put it in a list
  * print out the student list, in alphabetical order

  * do the above, and once you get it working, make some modifications to it...
    * now make it so that each iteration, we get name from the user like we did before, but
      * if the name begins with a '-', e.g., '-Tanner', that means remove it from the list, rather than add
      * (if the name doesn't begin with a '-', we'll add it)
      * ...which implies we may have more interactions with the user than there are students, e.g.,
          * if 3 students, we might enter "Tanner", "Cristy", "-Cristy", "Christy", "Dave"
          * therefore a for loop which we may have used initially is probably not going to work
    * stop when the name is empty (or 'quit')
    * print out the student list, in alphabetical order
* go through all the numbers from 1..100
  * for each number, print it out, followed by:
    * is it even or odd, is it divisible by 3, divisible by 5
    * for numbers greate than 9 (two digits or more), write out the digit separately
    * e.g.,
    <pre>
    1 is odd
    2 is even
    3 is odd and divisible by 3
    ...
    5 is odd and divisible by 5
    ...
    15 is odd and divisible by 3 and divisible by 5 (digits are 1, 5)
    </pre>


    


