# Python Bootcamp: Day 1 Notes (3/15/2025)

## **Key Concepts & Codes Learned**
- **Printing Basics**:
  - `print("Hello World!")` - Prints text in quotes.
  - `print("Hello World!\nHello World!")` - `\n` adds a line break.
  - `print("Hello" + " Angela")` - String concatenation.
  - `print("Hello " + input("What is your name?") + "!")` - Combines user input with text.
- **Variables**:
  - `name = input("What is your name?")`  
    `print(name)` - Assign input to a variable and print it.
- **Functions**:
  - `print(len(input("What is your name?")))` - Calculates and prints the length of user input.
- **Tuple Unpacking**:
  - `a, b = b, a` - Swaps variable values.
  - `print(f"a: {a}\nb: {b}")` - Prints variables with a line break using an f-string.
- **Comments**: Use `#` to add comments and explain your code.

---

## **Day 1 Capstone: Band Name Generator**
A fun exercise combining all Day 1 concepts!

```python
# Welcome message
print("Welcome to the Epic Band Name Generator")

# Get inputs
cityname = input("What city did you grow up in?\n")
petname = input("What is your pet's name?\n")

# Generate and display the band name
print("Your most epic band name is: " + cityname + " " + petname)
```

---

## **Course Insights & Tools**
### **Instructor**: Dr. Angela Yu  
- Engaging teaching style with hands-on projects.
- Recommends committing 1 hour a day to complete the ~600 video lessons and exercises.
- Utilizes the **Pomodoro method** (25/5-minute intervals) for focused study sessions.

### **Tools Introduced**:
- **PyCharm**: IDE for coding. Community Edition suggested for Days 1–15 with a custom plugin.  
- **Thonny**: Beginner-friendly IDE for debugging and understanding code execution.

### **Key Takeaways**:
- It's okay to make mistakes—**GTS (Google That Stuff)** and learn from error messages.
- **Debugging**: Read outputs carefully and adjust code based on errors.
- **Commenting**: Use `#` to make code readable for yourself and others.
- **Search for solutions**: Googling is encouraged—you're not expected to memorize everything!
- **"Our brain is for thinking, not storing."** YASS! Own your errors and keep learning.

### **Memorable Resource**:
- [TypeError: str object is not callable – How to Fix in Python](https://www.freecodecamp.org/news/typeerror-str-object-is-not-callable-how-to-fix-in-python/)  
  Includes a fantastic graphic—**"Own Your Error"**.

---
