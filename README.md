# exp1-19cs308

1. do...while Equivalent
Python doesn’t have a do...while loop, but you can simulate it using a while True loop with a break condition.

python
Copy
def do_while_example():
    number = 0
    while True:
        number += 1
        print(number)
        if number >= 5:  # Condition to stop
            break

# Test Case
do_while_example()
2. while...do Equivalent
This is simply a while loop in Python, where the loop's body executes as long as the condition is true.

python
Copy
def while_example():
    count = 0
    while count < 5:
        print(count)
        count += 1

# Test Case
while_example()
3. if ... else
This is straightforward in Python.

python
Copy
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
4. switch Equivalent
Python does not have a built-in switch statement, but you can use dictionaries to achieve similar functionality.

python
Copy
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
5. for Loop
The for loop in Python iterates over items in a sequence (like a list).

python
Copy
def for_example():
    fruits = ["apple", "banana", "cherry"]
    for fruit in fruits:
        print(fruit)

# Test Case
for_example()
