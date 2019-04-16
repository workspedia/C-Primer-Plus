1 outline 
(1) history & philosophy
(2) procedural versus object-oriented programming
(3) add object-oriented concepts to C
(4) add generic programming(泛型编程) concepts to C
(5) standards
(6) creating a program

2 introduction
C ancestry brings to C++  efficient, compact, fast, portable
Object-oriented heritage   a fresh programming methodology(方法), designed to cope with the escalating（esclate 增加） complexity
template features bring yet   genetric programming
triple heritage is both a blessing（福气） and a bane（祸根）

be poised（镇定，泰然自若的） to learn C++, mind-stretching（思维拓展，stretch，舒展） efforts, resilient（有弹性的）, nook（角落）, cranny（缝隙）

3 origins
 evolve, involve, revolve
 mainframe computer, spawn, discipline, address hardware matters
 These gifts helped make C the dominant programming language in the 1980s.
 Meanwhile, the 1980s witnessed the growth of a new programming paradigm（榜样，范例）: OOP
 
 4 The C Language
 assembly language（汇编语言）
 graft
 computer languages deal with two concepts, data and algorithms
 C is a procedual language, which means it emphasizes the algorithm side of programmming.
 A program prescribes a set of procedures for the computer to follow
 structured programming, C include features to facilitate this approach
 Top-down design
 
 5 The C++ shift: OOP
 OOP emphasizes the data
 property rotate（旋转）
 The process of going from a lower level of organization, such as classes, to a higher level, such as program designs, is called bottom-up 
 programming.
 
 6 C++ and Generic Programming
 
 7 Portability and Standards
 If you can recompile the program without making changes and it runs without a hitch, we say the program is portable.
 
 8 the mechanics（力学；操作方法） of creating a program
 WRITE -> source code -> COMPILER -> object code -> LINKER(startup code & library code) -> executable code
 
 Appendix 
 Portability and Standards
 Can you run your program on the new platform?    
 Of course you’ll have to recompile the program using a C++ compiler designed for the new platform.     
 But will you have to make any changes to the code you wrote?    
 If you can recompile the program without making changes and it runs without a hitch, we say the program is portable.   
 
 There are a couple obstacles to portability,the first of which is hardware.   
 The second obstacle to portability is language divergence. 
 
 Therefore, the American National Standards Institute (ANSI) created a committee in 1990 (ANSI X3J16) to develop a stan- dard for C++. 
 The International Organization for Standardization (ISO) soon joined the process with its own committee (ISO-WG-21), creating a joint ANSI/ISO effort to develop the standard for C++.  
 
adopted in 1998 by the ISO, the International Electrotechnical Commission (IEC), and ANSI.This standard, often called C++98
C++ continues to evolve, and the ISO committee approved a new standard August 2011 titled ISO/IEC 14882:2011 and informally dubbed C++11.  




Prior to the emergence of ANSI C, the C community followed a de facto standard based on the book The C Programming Language, by Kernighan and Ritchie.   
This standard was often termed K&R C; with the emergence of ANSI C, the simpler K&R C is now sometimes called classic C.
The C Standard was last revised as C99, which was adopted by the ISO in 1999 and ANSI in 2000. 

Some C++ implementations, such as Microsoft Visual C++, Embarcadero C++ Builder, Apple Xcode, Open Watcom C++, Digital Mars C++, and Freescale CodeWarrior, provide integrated development environments (IDEs) that let you manage all steps of program development, including editing, from one master program.   

Other implementations, such as GNU C++ on Unix and Linux, IBM XL C/C++ on AIX, and the free versions of the Borland 5.5 (distributed by Embarcadero) and Digital Mars com- pilers, just handle the compilation and linking stages and expect you to type commands on the system command line. 

Originally, Stroustrup implemented C++ with a C++-to-C compiler program instead of developing a direct C++-to-object code compiler.This program, called cfront (for C front end), translated C++ source code to C source code, which could then be compiled by a standard C compiler.

**Unix Compiling and Linking. 
**Linux Compiling and Linking. 
Linux systems most commonly use g++, the GNU C++ compiler from the Free Software Foundation.
The Free Software Foundation (FSF) is a 501(c)(3) non-profit organization founded by Richard Stallman on 4 October 1985 to support the free software movement, which promotes the universal freedom to study, distribute, create, and modify computer software,  
The GNU Project (/ɡnuː/ (About this soundlisten))[3] is a free-software, mass-collaboration project.  
g++ spiffy.cxx   

Command-Line Compilers for Windows Command Prompt Mode   
Free Windows downloads that include the GNU C++ compiler are Cygwin and MinGW; they use g++ as the compiler name.   
To compile a source code file named great.cpp, you type the following command at the prompt:
g++ great.cpp
If the program compiles successfully, the resultant executable file is named a.exe.   

Windows Compilers
The Wikipedia link (http://en.wikipedia.org/wiki/List_of_compilers) provides a comprehensive(综合的; 广泛的;) list of compilers for many platforms, including Windows.
Compile, Build, Make, Build All, Link, Execute, Run, and Debug.  
n Compile typically means compile the code in the file that is currently open.
n Build or Make typically means compile the code for all the source code files in the project.This is often an incremental process.That is, if the project has three files, and you change just one, and then just that one is recompiled.
n Build All typically means compile all the source code files from scratch.
n As described earlier, Link means combine the compiled source code with the neces-
sary library code.
n Run or Execute means run the program.Typically, if you have not yet done the earlier steps, Run does them before trying to run a program.
n Debug means run the program with the option of going through step-by-step.


the C++ ISO standards (C++98/03 and C++11) provide a basis for keeping these many implementations mutually compatible.


 
 
 ASCII | BrE ˈaski, AmE ˈæski | American Standard Code for Information Interchange 美国信息互换标准代码
