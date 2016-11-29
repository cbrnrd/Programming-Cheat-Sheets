### What is Python?
***
In short,
>Python is a high-level, interpreted general purpose programming language. It's lack of massive verbosity (like Java)
> gives it increased productivity.


### Why use Python?
***
- It's object oriented
- For making prototypes of future projects
- For networking projects (3L1TE HAXX0R tools)
- It's incredibly popular
- It's very beginner friendly
- For various [Raspberry Pi](https://www.raspberrypi.org/) projects
- No need to compile (it's interpreted)



### When not to use Python
***
- For performance-critical projects
- Low level programming (eg: Kernel code)
- Safety critical apps
- Graphically intensive programs (Video Games)
- Embedded programming
- Compilers

### Data types
***
- _boolean_:    

>the type of the built-in values True and False. Useful in conditional expressions, and anywhere else you want to represent the truth or falsity of some condition. Mostly interchangeable with the integers 1 and 0. In fact, conditional expressions will accept values of any type, treating special ones like boolean False, integer 0 and the empty string "" as equivalent to False, and all other values as equivalent to True. But for safety’s sake, it is best to only use boolean values in these places.


- _Numeric types_:

>int: Integers; equivalent to C longs in Python 2.x, non-limited length in Python 3.x

>long: Long integers of non-limited length; exists only in Python 2.x

>float: Floating-Point numbers, equivalent to C doubles

>complex: Complex Numbers

- _Sequences_:

>str: String; represented as a sequence of 8-bit characters in Python 2.x, but as a sequence of Unicode characters (in the range of U+0000 - U+10FFFF) in Python 3.x
bytes: a sequence of integers in the range of 0-255; only available in Python 3.x
byte array: like bytes, but mutable (see below); only available in Python 3.x

>list

>tuple

- _Sets_:

>set: an unordered collection of unique objects; available as a standard type since Python 2.6
frozen set: like set, but immutable (see below); available as a standard type since Python 2.6
Mappings:

> dict: Python dictionaries, also called hashmaps or associative arrays, which means that an element of the list is associated with a definition, rather like a Map in Java

### Basic Operators
***
##### _Arithmatic Operators_

_assume `a` is 10 and `b` is 20_

| Operator      | Description   | Example  |
| :-------------:|:-------------:|:---------:|
| `+` Addition      | Adds values on either side of the operator | `a + b = 30` |
| `-` Subtraction      | Subtracts the right hand operand from left hand operand| `a - b = -10` |
| `*` Multiplication | Multiplies the value on either side of the operator      | `a * b = 200` |
|`/` Division | Divides the left hand operand by the right hand operand | `a / b = 2` |
|`%` Modulus | Divides the left hand operand by the right hand operand and return the remainder | `b % a = 0` |
| `**` Exponent |Performs exponential (power) calculation on operators | `a ** b` = `a to the power of b`
|`//` Floor Division | [Explanation from Stack Overflow](http://stackoverflow.com/questions/183853/in-python-what-is-the-difference-between-and-when-used-for-division) | `9//2 = 4` and `9.0//2.0 = 4.0`|

##### _Assignment Operators_

| Operator    | Description   | Example  |
| :----------:| :------------:| :-------:|
| `=`         |	Assigns values from right side operands to left side operand | `c = a + b` assigns the value of `a + b` to `c`|
| `+=` Add AND | It adds right operand to the left operand and assign the result to left operand | `c += a` is equivalent to `c = c + a`
| `-=` Subtract AND | It subtracts right operand from the left operand and assign the result to left operand | `c -= a` is equivalent to `c = c - a`|
|`*=` Multiply AND | It multiplies right operand with the left operand and assign the result to left operand | `c *= a` is equivalent to `c = c * a`|
| `/=` Divide AND | It divides left operand with the right operand and assign the result to left operand | `c /= a` is equivalent to `c = c / a`
| `%=` Modulus AND | It takes modulus using two operands and assign the result to left operand | `c %= a` is equivalent to `c = c % a`
| `**=` Exponent AND | Performs exponential (power) calculation on operators and assign value to the left operand | `c **= a` is equivalent to `c = c ** a`|


### Advanced Operators
***
Each of these operators could have their own Wikipedia article, but for time/space purposes, [Here is a great chart from Tutorialspoint](https://www.tutorialspoint.com/python/python_basic_operators.htm)

***
***
### Hello, Python!
***
Here is the most basic program you can write in Python:

```python          
          print("Hello, Python!")
```
This prints `Hello, Python!` to the console.

# Syntax
***
- `if, else, elif` loops

```python
if x == y:
  #do stuff
elif x == z:
  #do something else
else:
  #do this

```
- Functions

```python
def func_name(args):
  #do stuff

#run func_name
func_name(args)

```
