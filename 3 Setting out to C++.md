1 outline
(1) creating a C++ program
(2) the general format for a c++ program
(3) the #include directive
(4) the main() function
(5) using the cout object for output
(6) comments
(7) endl
(8) declaring and using variables
(9) cin input
(10) functions

2 C++ initiation
facility
C++ is case sensitive; that is,it discriminates between uppercase characters and lowercase characters.
stripped of the trimmings
the function header describes the interface between a function and the function that calls it
parentheses, phase
Using void in the parentheses is an explicit way of saying that the function takes no arguments.
concession, encounter

3 C++ comments
double slash //
C++ also recognizes C comments, which are enclosed between /* and */ symbols.
try sticking to the C++ style

4 The c++ preprocessor and iostream file.  
C++, like C, uses a preprocessor.This is a program that processes a source file before the main compilation takes place. 
#include <iostream>
This directive causes the preprocessor to add the contents of the iostream file to your program.
In essence, replace
composite file
dropping the h extension and prefixing the filename with a c
iostream.h, math.h, iostream, cmath

use iostream instead of iostream.h, you should use the following namespace directive 
in h-free header files, 

5 cout
insertion operator << bitwise left-shift operator  operator overloading
>> extraction operator
*** endl is a special C++ notation that represents the importment concept of beginning a new line
cause the screen cursor to move to the beginning of the next line
\n, endl   One difference is that endl guarantees the output will be flushed
cout << carrots
first, cout replace carrots with its value. second, it translates the proper output character

6 variable
carrots is called a variable because you can change its value
The C++ style for declaring variables is to declare a variable as close to its first use as possible
remarkable, internally
25 stored as a binary value rather than store each digit separately
cout ostream class

7 function
C++ function come in two varieties: those with return values and those without them
The library files contain the compiled code for the function, whereas the header files contain the proyotypes.

英文标点符号
句点：英国英语（BrE）：Full Stop；美国英语（AmE）：Period，“ . ”
问号：Question Mark，“ ? ”
感叹号：Exclamation Mark，“ ! ”
逗号：Comma，“ , ”
冒号：Colon，“  : ”
省略号：Ellipsis (众数：Ellipses)，“ ... ”
分号：Semicolon，“ ; ”
连字符：Hyphen，“ - ”
连接号：En Dash，“ – ”
破折号：Em Dash，“ — ”
括号：Parentheses，
　　　小括号（圆括号）“ ( ) ”（parenthesis; round brackets）；
　　　中括号“ [ ] ”（square brackets）；
　　　大括号“ { } ”（brackets; braces）
引号：Quotation Marks，
　　　双引号“ " ”（quote）；
　　　单引号“ ' ”（single quotation marks）
缩写及所有格符号：Apostrophe，“ ' ”

explicit, implicit
5 to the eighth power
C++ does not allow you to embed one function definition inside another.
return 0 provide the return value and terminate the function.
main()'s return value to the operating system
main is not a keyword.
C++ programmers are blessed (or cursed) with myriad options when naming functions
convention, hallmark

#include <iostream> causes the contents of the iostream file to be substituted for this directive before final compilation.

Namespaces
If you use iostream instead of iostream.h, you should use the following namespace directive to make the definitions in iostream available to your program:
using namespace std;
This is called a using directive.   

 One potential problem is that you might use two prepackaged prod- ucts that both have, say, a function called wanda(). If you then use the wanda() function, the compiler won’t know which version you mean.   
 The namespace facility lets a vendor package its wares in a unit called a namespace so that you can use the name of a namespace to indicate which vendor’s product you want. So Microflop Industries could place its defi- nitions in a namespace called Microflop.

In this spirit, the classes, functions, and variables that are a standard component of C++ compilers are now placed in a namespace called std.

The preferred approaches are to use the std:: qualifier or to use something called a using declaration to make just particular names available:
using std::cout; 
using std::endl; 
using std::cin;
// make cout available // make endl available // make cin available



