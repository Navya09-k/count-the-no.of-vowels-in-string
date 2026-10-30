s = input("Enter a string: ")
count = sum(1 for c in s if c.lower() in "aeiou")
print("Number of vowels =", count)
