# Assignment-7
#1
# Create a tuple
t = (1, 2, 3, 4)

# Length of tuple
print("Length:", len(t))

# Concatenation
t2 = (5, 6)
print("Concatenation:", t + t2)

# Repetition
print("Repetition:", t * 2)

# Membership
print("Is 3 present?", 3 in t)
print("Is 10 not present?", 10 not in t)

#2
t = (10, 20, 30, 40, 50)

# Indexing
print("First element:", t[0])

# Negative Indexing
print("Last element:", t[-1])

# Slicing
print("Elements from index 1 to 3:", t[1:4])

# Iteration
print("Elements of tuple:")
for i in t:
    print(i)

#3
t = (1, 2, 3)

# Attempt to modify tuple
try:
    t[0] = 10
except TypeError:
    print("Tuples are immutable (cannot be changed)")

# Delete tuple
del t

# Check deletion
try:
    print(t)
except NameError:
    print("Tuple has been deleted")

#4
# Given sequence
seq = [4, 7, 1, 9, 2]

# Convert to tuple
t = tuple(seq)

# Built-in functions
print("Tuple:", t)
print("Length:", len(t))
print("Maximum:", max(t))
print("Minimum:", min(t))

OUTPUT 
Length: 4
Concatenation: (1, 2, 3, 4, 5, 6)
Repetition: (1, 2, 3, 4, 1, 2, 3, 4)
Is 3 present? True
Is 10 not present? True
First element: 10
Last element: 50
Elements from index 1 to 3: (20, 30, 40)
Elements of tuple:
10
20
30
40
50
Tuples are immutable (cannot be changed)
Tuple has been deleted
Tuple: (4, 7, 1, 9, 2)
Length: 5
Maximum: 9
Minimum: 1
