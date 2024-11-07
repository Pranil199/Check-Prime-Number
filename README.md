# Check-Prime-Number
Purpose of the Code
The code is designed to check whether a given number is a prime number or not. A prime number is a number greater than 1 that has no divisors other than 1 and itself.

### How the Code Works

1. Getting User Input:
   — The program begins by asking the user to enter a number. This number is stored in the variable `num`.

2. Initial Setup:
   — A variable `p` is initialized to 0. This variable acts as a flag to indicate whether the number is prime or not.

3. Checking for Prime:
   — The program uses a `for` loop to iterate through numbers starting from 2 up to (but not including) the given number (`num`).
   — For each number `i` in this range, the program checks if `num` is divisible by `i` (i.e., `num % i == 0`). If it is, this means `num` has a divisor other than 1 and itself, so it's not a prime number.
   — If a divisor is found, `p` is set to 1, indicating that the number is not prime.

4. Outputting the Result:
   — After the loop completes, the program checks the value of `p`.
   — If `p` is 1, it prints that the number is not a prime number.
   — If `p` is still 0, it indicates that no divisors were found, and the number is prime. The program then prints that the number is a prime number.

### Key Points for Beginners
— Prime Numbers: These are numbers greater than 1 that are divisible only by 1 and themselves. Common examples include 2, 3, 5, and 7.
— Divisibility Check: The code checks if a number is divisible by another using the modulus operator (`%`). If `num % i == 0`, then `i` is a divisor of `num`.
— Flag Variable: The variable `p` is used as a simple way to track whether a divisor was found during the loop. If `p` remains 0, the number is prime; otherwise, it is not.

This code provides a basic way to understand how loops, conditionals, and user input work in Python. It's a fundamental example of how to determine prime numbers, a common task in programming exercises.
