# 10*10-table
Algorithm: Print the multiplication table from 1 to 10
- Start
- Declare two integer variables: i and j
- Set i to 1
- Repeat the following steps until i is greater than 10
  - Set j to 1
  - Repeat the following steps until j is greater than 10
    - print the product of i and j, with a width of 4 spaces
    - Increase j by 1
  - print a new line
  - Increase i by 1
- End

---------------------

# a-circle
Algorithm: Calculate and print the perimeter and area of a circle
- Start
- Define a constant named pi with the value 3.14
- Declare integer variables: r, m, and a
- Read r from the user input (the radius of the circle)
- Set m to pi times r times r (the area of the circle)
- Set a to 2 times pi times r (the perimeter of the circle)
- print "perimeter=" followed by the value of m
- print "area=" followed by the value of a
- End

--------------------

# fibunachi

Algorithm: Print the Fibunachi
- Start
- Declare six integer variables: f1, f2, fib, i, n, and term
- Set f1 and f2 to 1 (the first two terms of the Fibonacci sequence)
- Read n from the user input (the number of terms to print)
- print "fib1: 1" and "fib2: 1"
- Set i to 3
- Repeat the following steps until i is greater than n
  - Set fib to the sum of f1 and f2 (the next term of the Fibonacci sequence)
  - Set f1 to f2
  - Set f2 to fib
  - print "fib" followed by the value of i, followed by ": ", followed by the value of fib
  - Increase i by 1
- End

--------------------


# kmm&bmm
Algorithm: kmm&bmm
- Start
- Declare six integer variables: m, n, p, f, and t
- Read m and n from the user input
- Set f to m and p to n
- Repeat the following steps until t is equal to 0
  - Set t to the remainder of m divided by n
  - Set m to n
  - Set n to t
- print "B.M.M=" followed by the value of m 
- print "K.M.M=" followed by the value of (p times f) divided by m 
- End

--------------------

# triangle by stars
- Start
- Declare two integer variables: i and j
- Set i to 1
- Repeat the following steps until i is greater than 5
  - Set j to 1
  - Repeat the following steps until j is greater than i
    - print "*"
    - Increase j by 1
  - print a new line
  - Increase i by 1
- End
