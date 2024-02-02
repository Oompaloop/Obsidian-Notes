- - -

#### The Shebang
---
Always include a "Shebang"
It acts as a path to the bash shell path
`#!/bin/bash` 
The above path is standard, because most instances of bash are stored in that directory, courtesy of the Linux Directory Hierarchy. However, bash is stored elsewhere in some cases.

Remember to account for this.
To find the shell path that bash is located in on most Unix-based systems, use the `which bash` command.

A more generalized Shebang might look like this `#!/[path to bash]`
- - - 


#### Comments, Variables, and Reading Input
- - - 
##### Comments
- - -
Comments can be written by preceding a line with the `#` symbol.
*All comments start with `#`*
An example comment would be `#This is an example comment in a Bash Script!`
As such, the Bash interpreter ignores anything following the `#`

##### Variables
- - -
Variables in Bash lack types and as such are relatively simple to implement.

__Here are some ways one can assign a value to a variable: 


1. `food=pizza`
Here, the value `pizza` was directly assigned to the variable `food`  

2. `foodVar2=$food`
Here, the variable `food` was assigned to the variable `foodVar2`


Notice how in order to access the value of `food`, the `$` indicator was placed in front of it.
This rule holds true for all variables. 
*In order to access the value of any variable, the `$` indicator must be placed in front of it.

 <u>It is also important to note the enforced variable-naming conventions in the Bash Scripting Language</u> 

Generally, variable names 
*Can:* - Start with a letter or an underscore
	- Contain letters, numbers, and underscores

*Cannot*
	- Start with a number
	- Include spaces or special characters
	- Be identical to reserved keywords such as `if`, `then`, `while`, etc.

*Note:* Variable names <u>ARE</u> case sensitive

##### User Input
- - -
User input, or input in general, can be read using the aptly named `read` command.

*Reading and Displaying User Input:* 

	read color
	echo $color

The 1st line reads user input and saves it to a variable named `color`, while the 2nd line accesses `$` the value of `color` and displays it to the terminal using the `echo` command.

If the user were to type in "red", then the script above (assuming the shebang is included) would display "red" on the terminal screen.

*Note:* A quick and easy way to have your script take command-line arguments is to type `$1`,`$2`, `$3`, and so on at the desired location(s). With each successive number denoting an additional argument.

An example would look something like this:
`echo "Hello! My name is $1 and my major is $2. I am a member of Hack@UCF and I am participating in Horse Plinko as a $3 member!`

Here, `$1` would be a name, `$2` would be a college major, and `$3` would be a color corresponding to the teams in the HPCC.
- - -


#### A
- - - 

- - - 

###### [[1.d. Interests]] Backlink

