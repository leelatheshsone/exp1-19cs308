# exp1-19cs308
def do_while_example():
    number = 0
    while True:
        number += 1
        print(number)
        if number >= 5:  # Condition to stop
            break

# Test Case
do_while_example()

def while_example():
    count = 0
    while count < 5:
        print(count)
        count += 1

# Test Case
while_example()
def if_else_example(x):
    if x > 0:
        return "Positive"
    elif x < 0:
        return "Negative"
    else:
        return "Zero"

# Test Cases
print(if_else_example(10))  # Positive
print(if_else_example(-5))  # Negative
print(if_else_example(0))   # Zero

def switch_example(value):
    switcher = {
        1: "One",
        2: "Two",
        3: "Three"
    }
    return switcher.get(value, "Invalid")

# Test Cases
print(switch_example(1))  # One
print(switch_example(2))  # Two
print(switch_example(4))  # Invalid

def for_example():
    fruits = ["apple", "banana", "cherry"]
    for fruit in fruits:
        print(fruit)

# Test Case
for_example()
