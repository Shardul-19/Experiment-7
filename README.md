# Experiment-7
AIM:

To study and implement the while loop in Python for solving different problems like printing numbers, factorial, Fibonacci series, reversing a number, palindrome checking, counting digits, and searching an element in a list.
HEORY (1–2 lines each)



While Loop: while loop executes a block of code repeatedly until the given condition becomes false.

Factorial: Factorial of a number n is the product of all integers from 1 to n.

Fibonacci Series: A series where each number is the sum of the previous two numbers.

Reverse of Number: A number is reversed by extracting digits using %10 and rebuilding it.

Palindrome: A number or string is palindrome if it reads the same forward and backward.

Counting Digits: Digits are counted by repeatedly dividing the number by 10 until it becomes 0.

Searching in List: Linear search checks each element until the key is found or list ends



ALGORITHM 1 – Print numbers from 1 to 5

Start the program.

Initialize variable i = 1.

Check the condition i <= 5.

If condition is true, print the value of i.

Increment i by 1 using i = i + 1.

Repeat steps 3 to 5 until condition becomes false.

When condition becomes false, stop the program.

 ALGORITHM 2 – Print numbers from 1 to n

Start the program.

Take input from user and store it in variable n.

Initialize variable i = 1.

Check condition i <= n.

If condition is true, print i.

Increment i by 1.

Repeat steps 4 to 6 until i becomes greater than n.

Stop the program.

 ALGORITHM 3 – Factorial of a number using while loop

Start the program.

Take a number input from user and store it in num.

Initialize factorial = 1.

Check if num < 0, then print factorial not possible and stop.

If num == 0, print factorial is 1 and stop.

Otherwise initialize i = 1.

Repeat while i <= num:

Multiply factorial with i → factorial = factorial * i

Increment i by 1

After loop ends, print factorial value.

Stop the program.

 ALGORITHM 4 – Fibonacci series for n terms

Start the program.

Take input n_terms from user for number of terms.

Initialize first two Fibonacci numbers: a = 0 and b = 1.

Initialize counter i = 1.

Repeat while i <= n_terms:

Print value of a.

Calculate next term c = a + b.

Update a = b and b = c.

Increment i by 1.

Stop after printing all terms.

 ALGORITHM 5 – Fibonacci series up to a limit

Start the program.

Take input limit from user.

Initialize a = 0 and b = 1.

Repeat while a <= limit:

Print value of a.

Update values using a, b = b, a + b.

When a becomes greater than limit, stop the program.

 ALGORITHM 6 – Reverse a number

Start the program.

Take a number input from user and store it in num.

Initialize rev = 0.

Repeat while num > 0:

Extract last digit using digit = num % 10.

Update reverse as rev = rev * 10 + digit.

Remove last digit from number using num = num // 10.

After loop ends, print reversed number.

Stop the program.

ALGORITHM 7 – Check palindrome using slicing

Start the program.

Take a string input from user.

Reverse the string using slicing: rev = st[::-1].

Compare original string and reversed string.

If both are equal, print "Palindrome".

Otherwise print "Not Palindrome".

Stop the program.

 ALGORITHM 8 – Check palindrome using while loop

Start the program.

Store the string in variable s.

Initialize i = 0 and j = len(s) - 1.

Set flag variable is_palindrome = True.

Repeat while i < j:

Compare s[i] and s[j].

If they are not equal, set is_palindrome = False and break loop.

Increment i and decrement j.

After loop ends, check flag:

If true print palindrome.

Else print not palindrome.

Stop the program.

 ALGORITHM 9 – Count digits in a number

Start the program.

Take a number input from user and store it in num.

Initialize count = 0.

Repeat while num > 0:

Increment count by 1.

Divide number by 10 using integer division num = num // 10.

After loop ends, print total count.

Stop the program.

 ALGORITHM 10 – Search an element in a list (Linear Search)

(Extra de raha hu because ye bhi code me hai)

Start the program.

Create a list nums = [10,20,30,40,50].

Take input key from user.

Initialize i = 0.

Repeat while i < len(nums):

Check if nums[i] == key.

If true, print element found with index and break.

Otherwise increment i by 1.

If loop ends and element not found, print element not found.

Stop the program.


CONCLUSION (3–4 lines)

In this experiment, we studied the working of the while loop in Python. We implemented different programs such as factorial calculation, Fibonacci series, palindrome checking, reversing numbers, counting digits, and searching elements. The while loop is useful when the number of iterations is not fixed and depends on a condition. Thus, we understood the importance of looping in solving repetitive problems efficiently.
