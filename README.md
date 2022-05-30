When evaluating a formula, Excel follows a standard math protocol called "order of operations". In general, Excel's order of operation follows the acronym PEMDAS (Parentheses, Exponents, Multiplication, Division, Addition, Subtraction) but with some customization to handle the formula syntax in a spreadsheet.Next, Excel will perform exponentiation, negation, and percent conversions (in that order), followed by multiplication and division, addition and subtraction, and concatenation. Finally, Excel will evaluate logical operators, if present.In summary, Excel solves formulas in the following order:

Parentheses
Reference operators
Exponents
Negation
Percent
Multiplication and Division
Addition and Subtraction
Concatenation
Logical operators
Note: If a formula contains multiple operators with the same priority (e.g. multiplication and division, or addition and subtraction), Excel will evaluate the operators from left to right.
