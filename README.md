# Mini-C-Compiler
A mini C++ compiler which detects errors like invalid variable name, invalid loops, invalid basic arithmetic expressions

Compilation Steps :
	
  $ lex c.l
	
  $ yacc c.y
	
  $ gcc y.tab.c -ll -ly 
	
  $ output [filename]
![CI](https://github.com/stepin104312/A-Mini-C-compiler/workflows/CI/badge.svg)
