# Factor and Prime Factor Finder

This Python script finds the factors and prime factors of a given number. It prompts the user to input a number, then calculates and displays both the factors and the prime factors of that number.

## Features

- **Factor Calculation**: It calculates all factors of the input number.
- **Prime Factor Calculation**: It identifies which of the factors are prime numbers.

## How it Works

1. **Input**: The user is prompted to enter a number.
2. **Factor Calculation**: The script iterates from 1 to the number itself to find all the factors (divisors) of the number.
3. **Prime Factor Calculation**: For each factor, the script checks if it is a prime number by dividing it by all numbers from 2 to the square root of the factor. If no divisor is found, the number is considered prime.
4. **Output**: The script prints both the factors and the prime factors of the input number.

## Code Explanation

- `num = int(input("Enter a number: "))`: Prompts the user to enter a number.
- `factors = []`: Initializes an empty list to store all factors of the number.
- `prime_factors = []`: Initializes an empty list to store prime factors.
- The script iterates through numbers from 1 to `num` using a `for` loop.
- For each number `i`, it checks if `i` divides `num` evenly (i.e., `num % i == 0`). If it does, `i` is added to the list of factors.
- The script then checks if `i` is a prime number. If `i` is greater than 1 and not divisible by any number between 2 and the square root of `i`, it is considered a prime factor and added to the list of prime factors.
- Finally, it prints the lists of factors and prime factors.

## Example

Enter a number: 12 Factors of 12: [1, 2, 3, 4, 6, 12] Prime factors of 12: [2, 3]

## How to Run

1. Copy the Python code into a file (e.g., `factor_prime_factors.py`).
2. Run the script using Python:
   ```bash
   python factor_prime_factors.py

3. Enter a number when prompted.


4. The script will display the factors and prime factors of the number.



# Requirements

`Python 3.x`


##License

This project is licensed under the <span style="color:"blue"">MIT License - see the LICENSE file for details.



