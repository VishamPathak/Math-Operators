## Math Operators
Used to perform mathematical operations, _(AKA. Arithmetic Operations)_

1. Addition `+`
2. Subtraction `-`
3. Multiplication `*`
4. Division `/` (Exact Answer, float)
   Division `//` (Quotient, integer)
5. Modulo `%` (Remainder)
6. Exponent `**`

*Ex.*
`print (2+1)`
 >3
`print (5%3)`
 >2
print( 2 ** 3)
 >8

## Assignment Operators
Used to assign values to variables

0. Simple Assignment `=`
1. Addition Assignment `+=`
2. Subtract Assignment `-=` 
3. Multiply Assignment `*=`
4. Divide Assignment `/=`
   Divide Assignment `//=`
5. Modulo Assignment `%=`
6. Exponent Assignment `**=`

### Rule for using Assignment Operators 
A variable must be declared before using an assignment operator with variables

*Ex.*
```
a = 5
a += 2 # equivalent to a = a + 2
print(a)
```
 >7

## Comparison Operators

Used to compare values for conditions. Returns a boolean after evaluations

1. equal to, `a == b`
> ` 5 == 6 ` --> False
2. not equal to, ` a != b`
> ` 5 != 6 ` --> True

3. less than, `a < b`
4. greater than, `a > b`
5. less than or equal to, `a <= b`
6. greater than or equal to, `a >= b`

### Rules for using Comparison Operators

Two objects are required such as a variable or a raw data/value
Variables must be defined before we can compare

Ex. 
`a = 5`
`print(a > 4)
> True

`print (a > b)`
> Error, b has no value
