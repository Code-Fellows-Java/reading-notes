# JavaScript Cont.
### functions

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).
- function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

- function name(parameter1, parameter2, parameter3) {
  // code to be executed
}

### Operators

- let x = 5;         // assign the value 5 to x
- let y = 2;         // assign the value 2 to y
- let z = x + y;     // assign the value 7 to z (5 + 2)

### Expressions

This chapter describes JavaScript's expressions and operators, including assignment, comparison, arithmetic, bitwise, logical, string, ternary and more.

At a high level, an expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to 7.

The expression 3 + 4 is an example of the second type. This expression uses the + operator to add 3 and 4 together and produces a value, 7. However, if it's not eventually part of a bigger construct (for example, a variable declaration like const z = 3 + 4), its result will be immediately discarded — this is usually a programmer mistake because the evaluation doesn't produce any effects.

As the examples above also illustrate, all complex expressions are joined by operators, such as = and +. In this section, we will introduce the following operators:

- Assignment	x = f()	x = f()
- Addition assignment	x += f()	x = x + f()
- Subtraction assignment	x -= f()	x = x - f()
- Multiplication assignment	x *= f()	x = x * f()
- Division assignment	x /= f()	x = x / f()
- Remainder assignment	x %= f()	x = x % f()
- Exponentiation assignment	x **= f()	x = x ** f()
- Left shift assignment	x <<= f()	x = x << f()
- Right shift assignment	x >>= f()	x = x >> f()
- Unsigned right shift assignment	x >>>= f()	x = x >>> f()
- Bitwise AND assignment	x &= f()	x = x & f()
- Bitwise XOR assignment	x ^= f()	x = x ^ f()
- Bitwise OR assignment	x |= f()	x = x | f()
- Logical AND assignment	x &&= f()	x && (x = f())
- Logical OR assignment	x ||= f()	x || (x = f())
- Logical nullish assignment	x ??= f()	x ?? (x = f())
