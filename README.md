# compiler_design

STEPS TO COMPILE:

->To compile the lex file: flex filename.l
->To compile the yacc file: yacc -d filename.y 
->To compile c++ programs: g++ lex.yy.c filename.tab.c -lfl
->To execute the file: ./a.out<inp.txt

CONCEPTS INCLUDED:

->convert unmatched if to matched if. 
->convert for loops and do while loops into while loops.
->construction of syntax tree.
->three address generation & backpatching.
->control flow graph.
->Directed Acyclic Graph(DAG) for basic blocks.
->copy propagation & constant folding.
