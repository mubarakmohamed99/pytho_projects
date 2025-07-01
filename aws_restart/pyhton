def prime_numbers_upto_250():
    with open("results.txt", "w") as file:
        for num in range(2, 251):
            is_prime = True
            for i in range(2, int(num ** 0.5) + 1):
                if num % i == 0:
                    is_prime = False
                    break
            if is_prime:

                file.write(f"{num}\n")  # Write directly to file

prime_numbers_upto_250()

print("\nResults saved to results.txt successfully!")
