def is_prime_or_not(a):
    if a <= 1:
        return "not a prime"
    for i in range(2, a):
        if a % i == 0:
            return "not a prime"
    return "prime"

print(is_prime_or_not(44))  # Output: not a prime
print(is_prime_or_not(7))   # Output: prime
