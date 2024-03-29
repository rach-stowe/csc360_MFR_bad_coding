# csc360_MFR_bad_coding

## This is a joke.
The following project is an exercise in what **NOT** to do when it comes to best practices in coding.

### Best practices violated:
1. Make your code readable.
2. Do not abbreviate names to the point where it would be unclear.
3. Use meaningful names that reflect the function or content.
4. Use proper whitespace to enforce and visualize structure.
5. Define constants where appropriate.
6. Do not overcomment.
7. Don't undercomment.
8. Write understandable loops.
9. Organize `if` statements so as to be readable, encapsulating conditions in boolean variables if necessary.
10. Maintain consistent naming practices.
11. Respect code proximity by putting related code as near to each other as possible.
12. Initialize variables wisely.
13. Follow established coding conventions.
14. Ensure your loop termination conditions are not surpassed by 1.

### How violated:
- Rules 1, 2, and 3 are all violated because all classes, variables, and methods have had their names obfuscated by random keysmashing.
   - By extension, rule 7 is also violated, because none of these obfuscated names are explained where it is required.
   - Rule 10 is also violated in the `Employee` class (now `ghjkluyghjfjyutgjhfncf`) where type indicators are prefixed to attributes of the class that are mismatched with their actual type (`boolean_num_hours` is a float, for example).
   - These rules are also violated because variables are unnecessarily typecast back and forth (e.g. `(int) (char) (int) (char)`).
- Rule 4 is violated because code for the `Hourly`, `Salary`, and `Contractor` classes (now `cfghfjk`, `gdhjfkdshfgds`, and `fghjklhkgfjkjyfgdfjhbknfsjdhfbsdnclkdghfdnsjkruweygfdshabjk` respectively) has been compressed onto one line, and whitespace removed.
   - It is also violated in the `Staff` (now `ghjkluyghjfjyutgjhfncf`) class, as unnecessary whitespace is included, making reading code a journey in scrolling.
   - Like, seriously. I cannot emphasize how terrible this one file is to look at. If there is one thing you have to experience with your eyeballs, it's this. Anywhere there can be whitespace there is whitespace. It looks like you tripped and spilled your code everywhere. It looks like cleanup in aisle 7. It looks like post-preschool toy time. It looks like an unfinished LEGO project. It looks like you sneezed really, really hard on it.
- Rule 5 is violated because constant values are hardcoded in as many different calculations (e.g. `40` has been replaced by `1+1+1...+1` 40 times.)
- Rule 6 is violated in the `Employee` class (now `ghjkluyghjfjyutgjhfncf`) as every single line is overexplained, even when it is self explanatory.
   - For example: Every line of a function definition block is commented, pointing out the function signature, each curly brace, any assignment operations, and whitespace for visual clarity.
   - Even more egregious: Functions with no parameters are singled out by comments _within the parentheses themselves_ indicating that these functions take no arguments.
   - It's even violated more in the `Salary` class (now `gdhjfkdshfgds`), where all whitespace is instead overwritten with a comment indicating that there should be whitespace there.
- Rule 8 is violated in the `Hourly` and `Employee` classes (now `cfghfjk` and `ghjkluyghjfjyutgjhfncf` respectively), where a random loop achieves nothing or recreates a string by iterating over it character by character.
- Rule 9 is violated in the `Salary` (`gdhjfkdshfgds`) class: not only is the `if` statement unnecessary, the conditions of the statement are not concisely defined, _and_ certain conditions are guaranteed to never run.
- Rule 11 is violated in the `Staff` (`ghjkluyghjfjyutgjhfncf`) class, as the whitespace effectively removes variables from their context.
- Rule 12 is violated in the `Hourly` (`cfghfjk`) and `Employee` (`ghjkluyghjfjyutgjhfncf`) classes by the inclusion of attributes and variables (e.g. `important` and `weight` that are not useful or discarded within the scope of their declaration.
- Rule 13 is violated. All new names for classes disrespect the PascalCase convention of class naming and are purely lowercase.
- Rule 14 is violated in the for loop in the `Salary` (`gdhjfkdshfgds`) class, as the terminal condition is off by one.
