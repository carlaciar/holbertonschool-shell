# WEEK 2: Shell, init files, variables and expansions
**Requirements**
- Allowed editors: `vi`, `vim`, `emacs`
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/bin/bash`
- A `README.md` file, at the root of the folder of the project, describing what each script is doing
- You are not allowed to use `&&`, `||` or `;`
- You are not allowed to use `bc`, `sed` or `awk`
- All your files must be executable

## FILE: 0-alias
**0. <o>**\
Create a script that creates an alias.
- Name: `ls`
- Value: `rm -f *`

## FILE: 1-hello_you
**1. Hello you**\
Create a script that prints `hello user`, where user is the current Linux user.

## FILE: 2-path
**2. The path to success is to take massive, determined action**\
Add `/action` to the `PATH`. `/action` should be the last directory the shell looks into when looking for a program.

## FILE: 3-paths
**3. If the path be beautiful, let us not ask where it leads**\
Create a script that counts the number of directories in the `PATH`.

## FILE: 4-global_variables
**4. Global variables**\
Create a script that lists environment variables.

## FILE: 5-local_variables
**5. Local variables**\
Create a script that lists all local variables and environment variables, and functions.

## FILE: 6-create_local_variable
**6. Local variable**\
Create a script that creates a new local variable.
- Name: `BEST`
- Value: `School`

## FILE: 7-create_global_variable
**7. Global variable**\
Create a script that creates a new global variable.
- Name: `BEST`
- Value: `School`

## FILE: 8-true_knowledge
**8. Every addition to true knowledge is an addition to human power**\
Write a script that prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line.

## FILE: 9-divide_and_rule
**9. Divide and rule**\
Write a script that prints the result of `POWER` divided by `DIVIDE`, followed by a new line.
- `POWER` and `DIVIDE` are environment variables

## FILE: 10-love_exponent_breath
**10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath**\
Write a script that displays the result of `BREATH` to the power `LOVE`
- `BREATH` and `LOVE` are environment variables
- The script should display the result, followed by a new line

## FILE: 11-binary_to_decimal
**11. There are 10 types of people in the world -- Those who understand binary, and those who don't**\
Write a script that converts a number from base 2 to base 10.
- The number in base 2 is stored in the environment variable `BINARY`
- The script should display the number in base 10, followed by a new line

## FILE: 12-combinations
**12. Combination**\
Create a script that prints all possible combinations of two letters, except `oo`.
- Letters are lower cases, from `a` to `z`
- One combination per line
- The output should be alpha ordered, starting with `aa`
- Do not print `oo`
- Your script file should contain maximum 64 characters

## FILE: 13-print_float
**13. Floats**\
Write a script that prints a number with two decimal places, followed by a new line.\
The number will be stored in the environment variable `NUM`.

## FILE: 14-decimal_to_hexadecimal
**14. Decimal to Hexadecimal**\
Write a script that converts a number from base 10 to base 16.
- The number in base 10 is stored in the environment variable `DECIMAL`
- The script should display the number in base 16, followed by a new line

