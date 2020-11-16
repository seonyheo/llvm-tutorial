# LLVM Tutorial

## General Information

This LLVM tutorial is to help you get familiar with LLVM. :)  
It consists of 8 practices and 1 toy project in total.

* List of Practices
  * Basic
      - (1) First Compilation
      - (2) Control Flow Graph
  * Optimization 
      * Analysis
        - (3) Function Name Printer
        - (4) Instruction Counter
        - (5) Call Instruction Counter
        - (6) Loop Info 
      * Transformation
        - (7) Insert inc Function
        - (8) Dynamic Call Counter

* List of Toy Projects
  * Optimization
    * MemoryProfiler

## Prerequisite
### LLVM Installation

For your convenience, I wrote a Makefile that automatically downloads and builds LLVM 10.0.0.  
It can take more than 3 hours to build LLVM, please start early! 

## Instructions

### Testing

#### Compile your pass

In each practice folder, type
~~~bash
$ make
~~~
You will get the library file that contains your pass.

#### Apply your pass to a test program

In each practice folder, type
~~~bash
$ make test
~~~
You will get the optimized IR code (test.opt.ll) for the test program.

#### Run the optimized program

In each practice folder, type
~~~bash
$ make run
~~~
You will get the output of the optimized program.

## Contact

If you need a solution for the practices, please contact me.  
Seonyeong Heo, heosy@postech.ac.kr
