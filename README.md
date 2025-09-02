# Python-calculator-project
Thanks for the amazing reactions on the last post. Let's start with our first Python Project today:

✅ *Python Project 1: Calculator (CLI)* 🔢💻

📌 *Problem Statement:*  
Build a simple command-line calculator that performs basic arithmetic: addition, subtraction, multiplication, and division.

🧠 *What You'll Learn:*  
- Taking user input  
- Writing functions  
- Using if/else statements  
- Handling edge cases (like division by zero)

✅ *Python Code:*
``` 
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Error: Division by zero"
    return x / y

print("=== Simple Calculator ===")
print("Choose operation:")
print("1. Add (+)")
print("2. Subtract (-)")
print("3. Multiply (*)")
print("4. Divide (/)")

op = input("Enter your choice (+, -, *, /): ")
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

if op == '+':
    result = add(a, b)
elif op == '-':
    result = subtract(a, b)
elif op == '*':
    result = multiply(a, b)
elif op == '/':
    result = divide(a, b)
else:
    result = "Invalid operator"

print("Result:", result)
```

📥 *Sample Input:*  
```
Enter your choice (+, -, *, /): +
Enter first number: 10  
Enter second number: 5  
```

📤 *Output:*  
```
Result: 15.0
```

*React ❤️ if you're ready for the next project*

Python Projects Series: https://whatsapp.com/channel/0029VaiM08SDuMRaGKd9Wv0L/1987
