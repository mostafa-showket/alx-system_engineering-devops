# 0x03. Shell, init files, variables and expansions

0-alias: creates an alias with name: `ls` and value: `rm *`

1-hello_you: prints `hello user` where user is the current Linux user

2-path: adds `/action` to the `PATH`, `/action` will be the last directory the shell looks into when looking for a program

3-paths: counts the number of directories in the `PATH`

4-global_variables: lists environment variables

5-local_variables: lists all local variavles and environment variables, and functions

6-create_loclal_variable: creates new local variable 
* name: `BEST`
* value: `School`

7-create_global_variable: creates a new global variable
* name: `BEST`
* value: `School`

8-true_knowledge: prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEGE`

9-divide_and_rule: prints the result of `POWER` divided by `DIVIDE`
* `POWER` and `DIVIDE` are environment variables

10-love_exponent_breath: displays the result of `BREATH` to the power of `LOVE`
* `BREATH` and `LOVE` are environment variables

11-binary_to_decimal: converts a number from base 2 to base 10
* The number in base 2 is stored in the environment variable BINARY

12-combinations: prints all possible combinations of two letters except `00`
* Letters are lower cases, from `a` to `z`
* One combination per line
* The output is alpha ordered, starting with `aa`

13-print_float: prints a number with two decimal places
* the number will be stored in `NUM` environment variable

100-decimal_to_hexadecimal: converts a number from base 10 to base 16
* the number in base 10 stored in environment variable `DECIMAL`

101-rot13: encodes and decodes text using the rot13 encryption

102-odd: prints every other line from the input starting from the first line

103-water_and_stir: adds the two numbers stored in the environment variables `WATER` and `STIR` and prints the result
* `WATER` is in base `water`
* `STIR` is in base `stir`
* the result will be in base `bestchol`

# Usage: 
write `./` before the file name in shell commands to excute example:
`./0-alias`

> this project developed for ALX School program
