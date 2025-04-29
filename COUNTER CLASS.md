# Exp.No:30  
## COUNTER CLASS

---

### AIM  
To write a Python program to Create  Counter class which  has one attribute called current which defaults to zero. And it has three methods:

increment() increases the value of the current attribute by one.
value() returns the current value of the current attribute
reset() sets the value of the current attribute to zero
create a new instance of the Counter class and calls the increment() method three times before showing the current value of the counter to the screen.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Counter` class.**
   - Initialize the `current` variable with 0.
3. **Define the `increment()` method** to increment the value of `current` by 1.
4. **Define the `value()` method** to return the current value of `current`.
5. **Define the `reset()` method** to reset the `current` value back to 0.
6. **Create a `counter` object** of the `Counter` class.
7. **Call the `increment()` method** three times to increment the counter.
8. **Call the `value()` method** and print the result to show the current counter value.
9. **End the program.**

---

### PROGRAM
```
Reg no-212223020028
Name-Tharani devi.G
Write your code
class Counter:
    def __init__(self):
        self.current = 0

    def increment(self):
        self.current += 1

    def value(self):
        return self.current

    def reset(self):
        self.current = 0

counter = Counter()


#call the increment method three times
counter.increment()
counter.increment()
counter.increment()
print(counter.value())

```

### OUTPUT

![Module 6b](https://github.com/user-attachments/assets/19353c0f-25d9-41a3-9313-be6a2f705c40)


### RESULT
This program for Counter class which  has one attribute called current which defaults to zero is successfully executed.
