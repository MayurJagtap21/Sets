# Sets

# Convert list into set

l = ["mayur", "jagtap", "pop", "jordan", "mayur"]
s = print(set(l))

# Set operations
# Add
s1 = {"john", "mike", "kevin"}
print(s1)
s1.add('smith')
print(s1)

# Remove item from set
s1 = {"john", "mike", "kevin"}
print(s1)
s1.remove("john")
print(s1)

# Mathematical set operations
# Union
s1 = {"john", "mike", "kevin"}
print(s1)
s2 = {"mayur", "jagtap", "pop", "jordan"}
print(s2)
s3 = s1.union(s2)
print(s3)

# Subset
s1 = {"john", "mike", "kevin"}
print(s1)
s2 = {"john", "mike"}
print(s2)
s4 = s2.issubset(s1)
print(s4)

