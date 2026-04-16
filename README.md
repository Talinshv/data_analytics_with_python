# data_analytics_with_python
# Data Types
## Integers
### 1. What is an Integer?
In the simplest terms, an integer is a whole number. It can be positive, negative, or zero, but it can never have a decimal point or a fractional part.

  - Valid integers: 5, -42, 0, 1000
  - Not integers: 5.5, 3.14, 1/2

### 2. Python Code Examples
The blue boxes show how a computer handles these numbers:

  - Assignment: x = 10 and y = -3 tells the computer to store those specific whole numbers into variables named x and y.
  - Output: When the code simply says x, the computer returns its value: 10.
  - Type Checking: The command print(type(x)) asks the computer, "What kind of data is stored in x?"

The result <class 'int'> is the computer’s way of saying, "This is an integer."

### 3. Common Use Cases
Since integers are "clean" numbers with no decimals, they are used for things that can be counted precisely:

  - Counts: The number of people in a room or items in a shopping cart (you can't have 2.5 people).
  - IDs: Unique identification numbers, like a student ID or a database record number.
  - Discrete Quantities: Anything that exists in distinct, separate units (e.g., the number of days in a month).

## Floating-Point Number
### 1. What is a Float?
A floating-point number represents "real" numbers that require precision. 

Even if a number is technically a whole number, like $10$, adding a decimal point ($10.0$) turns it into a float in the eyes of a computer.

Examples from the image: 1.34, 4.567, 10.4, -2.5

### 2. Python Code Examples
The Decimal Difference: Notice b = 10.0. In math, $10$ and $10.0$ are the same, but in programming, the .0 tells the computer to use the "float" data type instead of the "int" data type.

Type Checking: When the code runs print(type(a)), the output is <class 'float'>. This confirms that any number with a decimal is categorized this way.

### 3. When do we use Floats?
Floats are used for data that isn't "all or nothing." They are essential for:

  - Continuous Measurements: Things like temperature ($72.5$ degrees), weight ($150.2$ lbs), or height.
  - Financial Values: Prices like $\$19.99$.Statistical Calculations: Averages (e.g., the average of $1$ and $2$ is $1.5$).

## String
### 1. What is a String?
A string represents any textual data—letters, words, sentences, or even symbols. The defining feature of a string in programming is that it must be wrapped in quotes.

The Rule: You can use single quotes ('Alice') or double quotes ("Alice"). They work the same way, but they tell the computer: "Don't treat this as a number or a command; treat it exactly as text."

### 2. Python Code Examples
Assignment: name = "Alice" saves the word Alice into a variable.

Type Checking: When you run print(type(name)), the computer responds with <class 'str'>. In Python, "str" is the short code for string.

The "Number" Trap: Even a number can be a string if you put quotes around it. "10" is a string (text), while 10 is an integer (math). 

You can't add "10" + 5, because the computer sees the first one as a word.

### 3. Common Use Cases
Strings are the most flexible data type because they can hold almost anything:

  - Names: Usernames, employee names, or city names (like "Yerevan").
  - Categories/Labels: Identifying types of data, like "High", "Medium", or "Low".
  - Descriptions: Long paragraphs of text or product reviews.

## Boolean
This image introduces the Boolean, which is the simplest but perhaps most powerful data type in programming. 
While integers and strings can have infinite variations, a Boolean can only ever be one of two things: True or False.

Think of it like a light switch—it is either on or off.
### 1. The Basics
  - Values: In Python, these are written as True and False (note the capital letters).
  - Type Label: If you run print(type(is_active)), Python identifies it as <class 'bool'>.

### 2. Booleans from Comparisons
The most common way Booleans are created is through "questions" (comparisons) you ask the computer.
  - In the image example: x = 10 followed by x > 5.
  - The computer evaluates this and returns True because 10 is indeed greater than 5.

### 3. Why are they important?
Booleans are the "brain" of any program. They allow the computer to make decisions:
  - Logical conditions: "If the user is logged in (True), show the dashboard."
  - Filtering data: "Show only the products that are in stock (is_in_stock = True)."
  - Decision making: "If the battery is less than 15%, turn on power saving mode."
## Variables
This image explains the concept of Variables. 
If the data types you just learned (integers, strings, booleans) are the "objects," then variables are the boxes you put them in so you can find them later.

### 1. What is a Variable?
The image defines it as a named reference. Instead of just having a piece of data floating around, you give it a name so the computer knows how to find it in its memory.

### 2. Why do we need them?
The image makes a great point: "Without variables, automation is impossible."

  - Avoid Repetition: If you use a number like $3.14159$ fifty times in your code, it's easier to just name it pi.
  - Readability: Seeing total_price in code makes much more sense than just seeing a random number like 142.5.
  - Updating Values: If the price changes, you only have to change it once where the variable is defined, rather than searching through every line of code.

### 3. Creating a Variable
The image shows the "Assignment" process using the = sign. This is a bit different from math:
  In Math: = means "these two things are equal."
  In Programming: = means "take the value on the right and stuff it into the name on the left."
  - x = 10
  - The computer creates a spot in its memory.
  - It labels that spot x.
  - It puts the integer 10 inside.

## Variables Can Store Any Data Type
A variable is a universal container—it doesn't care what you put inside it, as long as it's a valid data type.

### 1. The "Big Four" in Action
The image shows one variable for each of the data types we discussed:
  - Integer: count = 100 (Whole number)
  - Float: price = 19.99 (Decimal number)
  - String: customer_name = "Alice" (Text in quotes)
  - Boolean: is_active = True (Logical truth)

### 2. Dynamic Typing (The "Important" Note)
Variables do not have a fixed type.
In some older programming languages, you have to tell the computer, "This variable will only ever hold integers." If you try to put a string in it later, the program crashes.
### Python is different:
  - A variable's "identity" comes from whatever is inside it at that exact moment.
  - If you have x = 10 (an integer) and then later write x = "Hello", Python just swaps the old integer for the new string. It's flexible!

## Reassigning Variables
It is the "variable" part of a variable. It shows that you aren't just stuck with the first value you choose; you can update that "box" at any time.

### 1. How Reassignment Works
The code shows a two-step process:
  - Initial Assignment: x = 5. The computer creates a space called x and puts a $5$ in it.
  - The Update: x = 20. The computer doesn't create a new variable. Instead, it goes back to the box labeled x, tosses out the $5$, and drops in a $20$.

When you ask the computer for x afterward, it only remembers the most recent value. The old value is gone.

### 2. Why is this useful?
In the real world, data is rarely static. We use reassignment for:
  - Keeping Score: score = score + 1 (Updating your current points).
  - Changing States: is_playing = False (When a user hits the stop button).
  - Tracking Progress: current_page = 2 (When you click "Next" in an e-reader).



