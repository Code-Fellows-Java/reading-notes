# Operators and Loops

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.


# Comparison Operators

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. The following table describes the comparison operators in terms of this sample code:

- Equal (==)	Returns true if the operands are equal. /	3 == var1 "3" == var 13 == '3'
- Not equal (!=)	Returns true if the operands are not equal. /	var1 != 4 var2 != "3"
- Strict equal (===)	Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS. /	3 === var1
- Strict not equal (!==)	Returns true if the operands are of the same type but not equal, or are of different type. /	var1 !== "3" 3 !== '3'
- Greater than (>)	Returns true if the left operand is greater than the right operand. /	var2 > var1 "12" > 2
- Greater than or equal (>=)	Returns true if the left operand is greater than or equal to the right operand. /	var2 >= var1 var1 >= 3
- Less than (<)	Returns true if the left operand is less than the right operand. /	var1 < var2 "2" < 12
- Less than or equal (<=)	Returns true if the left operand is less than or equal to the right operand. /	var1 <= var2 var2 <= 5


# Loops and Iteration

Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.

You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

- There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

- The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others
