# python5
my_dict = {
    "name": "John",
    "age": 25,
    "city": "New York"
}

# Accessing elements in the dictionary
print("Name:", my_dict["name"])
print("Age:", my_dict["age"])
print("City:", my_dict["city"])

# Modifying elements in the dictionary
my_dict["age"] = 26
my_dict["city"] = "San Francisco"

# Adding a new key-value pair
my_dict["occupation"] = "Engineer"

# Removing a key-value pair
del my_dict["city"]

# Iterating through the dictionary
print("\nIterating through the dictionary:")
for key, value in my_dict.items():
    print(key + ":", value)
