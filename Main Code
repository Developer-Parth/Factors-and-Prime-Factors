num = int(input("Enter a number: "))
factors = []
prime_factors = []
for i in range(1, num + 1):
    if num % i == 0:
        factors.append(i)
        is_prime = True
        if i > 1:
            for j in range(2, int(i**0.5) + 1):
                if i % j == 0:
                    is_prime = False
                    break
        if is_prime:
            prime_factors.append(i)
print(f"Factors of {num}: {factors}")
print(f"Prime factors of {num}: {prime_factors}")
