# data_analytics_with_python
# Data Types
# Integers
## 1. What is an Integer?
In the simplest terms, an integer is a whole number. It can be positive, negative, or zero, but it can never have a decimal point or a fractional part.

Valid integers: 5, -42, 0, 1000

Not integers: 5.5, 3.14, 1/2

## 2. Python Code Examples
The blue boxes show how a computer handles these numbers:

Assignment: x = 10 and y = -3 tells the computer to store those specific whole numbers into variables named x and y.

Output: When the code simply says x, the computer returns its value: 10.

Type Checking: The command print(type(x)) asks the computer, "What kind of data is stored in x?"

The result <class 'int'> is the computer’s way of saying, "This is an integer."

## 3. Common Use Cases
Since integers are "clean" numbers with no decimals, they are used for things that can be counted precisely:

Counts: The number of people in a room or items in a shopping cart (you can't have 2.5 people).

IDs: Unique identification numbers, like a student ID or a database record number.

Discrete Quantities: Anything that exists in distinct, separate units (e.g., the number of days in a month).

# Floating-Point Number
## 1. What is a Float?
A floating-point number represents "real" numbers that require precision. 

Even if a number is technically a whole number, like $10$, adding a decimal point ($10.0$) turns it into a float in the eyes of a computer.

Examples from the image: 1.34, 4.567, 10.4, -2.5

# 2. Python Code Examples
The Decimal Difference: Notice b = 10.0. In math, $10$ and $10.0$ are the same, but in programming, the .0 tells the computer to use the "float" data type instead of the "int" data type.

Type Checking: When the code runs print(type(a)), the output is <class 'float'>. This confirms that any number with a decimal is categorized this way.

# 3. When do we use Floats?
Floats are used for data that isn't "all or nothing." They are essential for:

  Continuous Measurements: Things like temperature ($72.5$ degrees), weight ($150.2$ lbs), or height.

  Financial Values: Prices like $\$19.99$.Statistical Calculations: Averages (e.g., the average of $1$ and $2$ is $1.5$).

## String
# 1. What is a String?
A string represents any textual data—letters, words, sentences, or even symbols. The defining feature of a string in programming is that it must be wrapped in quotes.

The Rule: You can use single quotes ('Alice') or double quotes ("Alice"). They work the same way, but they tell the computer: "Don't treat this as a number or a command; treat it exactly as text."

# 2. Python Code Examples
Assignment: name = "Alice" saves the word Alice into a variable.

Type Checking: When you run print(type(name)), the computer responds with <class 'str'>. In Python, "str" is the short code for string.

The "Number" Trap: Even a number can be a string if you put quotes around it. "10" is a string (text), while 10 is an integer (math). 

You can't add "10" + 5, because the computer sees the first one as a word.

# 3. Common Use Cases
Strings are the most flexible data type because they can hold almost anything:

  Names: Usernames, employee names, or city names (like "Yerevan").

  Categories/Labels: Identifying types of data, like "High", "Medium", or "Low".

  Descriptions: Long paragraphs of text or product reviews.
