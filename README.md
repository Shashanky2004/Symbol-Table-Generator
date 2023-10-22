# Symbol-Table-Generator
This C program parses expressions and generates a simple symbol table for identifiers and operators. It allows you to input an expression (ending with '$') and extracts identifiers and operators while displaying their memory addresses.

Features:

Parses expressions and extracts identifiers and operators.
Generates a basic symbol table with symbol, address, and type information.
User-friendly input with a clear prompt.
Usage:

Clone the repository or download the code.
Compile the code using a C compiler.
Run the compiled executable.
Enter an expression (ending with '$') when prompted.
The program will display the symbol table with symbols, addresses, and types.
Sample Output:

less
Copy code
Enter the expression (ENDS WITH $)
abc+xyz$

Given expression: abc+xyz
--------SYMBOL TABLE--------
SYMBOL   Address   TYPE
a       0x7fbd179057d0   identifier
b       0x7fbd179057e0   identifier
c       0x7fbd179057f0   identifier
+       0x7fbd17905800   operator
x       0x7fbd17905810   identifier
y       0x7fbd17905820   identifier
z       0x7fbd17905830   identifier
Contributing:

We welcome contributions! Feel free to open issues, suggest improvements, or submit pull requests.
