1 outline  
(1) naming variables   
(2) integers types.   
(3) climits file.  
(4) numeric literals (constants).  
(5) const qualifier.  
(6) built-in floating-point types.  
(7) cfloat file.  
(8) numeric literals of various floating-point types.  
(9) C++'s arithmetic operators.  
(10) automatic type conversions.  
(11) forced type conversions.  

The essence of object-oriented programming (OOP) is designing and extending your own data types. Designing your own data types represents an effort to make a type match the data. If you do this properly, you’ll find it much simpler to work with the data later.
fundamental types (integers and floating-point numbers) and compound types (arrays,strings, pointers and structures)

2 simple variables
three fundamental properties: where, value, type. 

Typically, int is 16 bits (the same as short) for older IBM PC implemen- tations and 32 bits (the same aslong) forWindows XP,WindowsVista,Windows 7,Macin- tosh OS X,VAX, and many other minicomputer implementations.   

First, the sizeof operator returns the size, in bytes, of a type or a variable. (An operator is a built-in language element that operates on one or more items to produce a value. For example, the addition operator, represented by +, adds two values.)   
Second, the climits header file (or, for older implementations, the limits.h header file) contains information about integer type limits. In particular, it defines symbolic names to represent different limits. For example, it defines INT_MAX as the largest possible int value and CHAR_BIT as the number of bits in a byte. 

When you use the sizeof operator with a type name, such as int, you enclose the name in paren- theses. But when you use the operator with the name of the variable, such as n_short, parentheses are optional:
cout << "int is " << sizeof (int) << " bytes.\n"; cout << "short is " << sizeof n_short << " bytes.\n";

The climits file contains lines similar to the following:
#define INT_MAX 32767
Recall that the C++ compilation process first passes the source code through a preproces- sor. Here #define, like #include, is a preprocessor directive. What this particular directive tells the preprocessor is this: Look through the program for instances of INT_MAX and replace each occurrence with 32767. So the #define directive works like a global search- and-replace command in a text editor or word processor.


underscore _ , __fools reserved, strident
nMyWeight a prefix that describes the variable's type
presage, positive and negative value
The funfamental unit of computer memory is the bit.
Think of a bit as an electronic switch that you can set to either off or on.
kilobyte, megabyte
short is short for short int


Integer Literals
An integer literal, or constant, is one you write out explicitly, such as 212 or 1776.    
C++, like C, lets you write integers in three different number bases: base 10 (the public favorite), base 8 (the old Unix favorite), and base 16 (the hardware hacker’s favorite).   
C++ uses the first digit or two to identify the base of a number constant. If the first digit is in the range 1–9, the number is base 10 (decimal); thus 93 is base 10. If the first digit is 0 and the second digit is in the range 1–7, the number is base 8 (octal); thus 042 is octal and equal to 34 decimal. If the first two characters are 0x or 0X, the number is base 16 (hexadecimal); thus 0x42 is hex and equal to 66 decimal.


cout << "Monsieur cuts a striking figure!" << endl;
cout << "chest = " << chest << " (decimal for 42)" << endl;   
cout << hex; // manipulator for changing number base
cout << "waist = " << waist << " (hexadecimal for 42)" << endl;    
cout << oct; // manipulator for changing number base
cout << "inseam = " << inseam << " (octal for 42)" << endl;   
cout << dec;
cout << "chest = " << chest << " (decimal for 42)" << endl;



cout << "Year = " << 1492 << "\n";
Does the program store 1492 as an int, a long, or some other integer type? The answer is that C++ stores integer constants as type int unless there is a reason to do oth- erwise.Two such reasons are if you use a special suffix to indicate a particular type or if a value is too large to be an int.  
22022UL are unsigned long


initialization combines assignment with declaration

cin and cout are guided by the type of variable.
*** C++ uses single quotation marks for a character and double quotation marks for a string.
cout << 'q'; cout.put('q');
escape sequence 转义字符 '\n'
*** C++ interprets nonzero values as true and zeros values as false.
bool is_ready = true;

Now let’s return to the topic of symbolic names for constants.A symbolic name can sug- gest what the constant represents.Also if the program uses the constant in several places and you need to change the value, you can just change the single symbol definition.
The keyword const is termed a qualifier because it __qualifies the meaning of a declaration__.  

But const is better.   
For one thing, it lets you specify the type explicitly.   
Second, you can use C++’s scoping rules to limit the defi- nition to particular functions or files. (Scoping rules describe how widely known a name is to different modules; you’ll learn about this in more detail in Chapter 9,“Memory Models and Namespaces.”)    
Third, you can use const with more elaborate types, such as arrays and structures, as discussed in Chapter 4.

3 floating-point type
conspiracy
moving decimal point is the origin of the term "floating-point."
By default, floating-point type constants are type double.
scaling factor, operands, modulus 19 % 5 = 4

module modulus model
*** order of operation: operator precedence and associativity

4 type conversions
profusion
(1) conversion on initialization and assignment
the value is converted to the type of the receiving variable.
loss of precision, out of range
C++ uses truncation (discarding the fractional part) and not rounding (finding the closest integer value) when converting floating-point value to integer types.
*** short fowl = chickens + ducks;










