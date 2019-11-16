# Basic C Programming Tutorial
## Chapter 3.Program Structure
### Parts of C:
* Preprocessor Commands
* Functions
* Variables
* Statements & Expressions
* Comments
### Example:

#include <stdio.h>

int main()

{

/* my first program in C */

printf("Hello, World! \n");

return 0;

}
### Description:
1. The first line of the program #include <stdio.h> is a preprocessor command, which tells a C compiler to include stdio.h file before going to actual compilation.
2. The next line int main() is the main function where the program execution begins.
3. The next line /*...*/ will be ignored by the compiler and it has been put to add additional comments in the program. So such lines are called comments in the program.
4. The next line printf(...) is another function available in C which causes the message "Hello, World!" to be displayed on the screen.
5. The next line return 0; terminates the main() function and returns the value 0.
