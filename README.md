# SER 502 Project
<p align="center">
<img width="200" height="200" src="https://user-images.githubusercontent.com/11274840/80438904-27212680-88ba-11ea-90c8-14ae5c9d3c15.png">
    
    
# LitePiler
This is a group project for SER502. In this project we have developed a programming language and the framework which runs programs written in laungage. Name of language is LitePiler.

## Basic idea about language:

This language was written in four layers : 

- First part was to design a grammar relevant to language and which compiler could understand.We used Context Free Grammar to write programming rules for this language. (**Grammar**)

- Second part was to mould rules according to Parser. This part is used to create parse tree for programs written in  language. (**Parser**)

- Third part was to create Lexer.In this part we created a list of keywords as programming blocks in programming launguage . This layer is responsible for taking out the tokens from programs and map them to parser(parse tree). (**Lexer**)

- Fourth part was to write Interpreter. For the rules written in parser, we have written eval function for them which will help us in evaluating the end result of the program. (**Interpreter**)

## Flow diagram
![alt text](https://user-images.githubusercontent.com/11274840/80473399-ef869e80-88fa-11ea-8e3b-cfd632d43df8.png)

## Tools used for language : 

This language was developed and built on MacOs but it can be compiled and run on any platform. It is also a system indepedent language.

- [SWI-Prolog (Web Version)][5]
- [SWI-Prolog (Desktop Version)][5]
- Any Text Editor - Example(Visual Studio,Atom,SublimeText)

## Build and run the language

1. Write program according to programming syntax. For reference, [See sample codes][7] present in data folder.

2. For running program in environment, clone the [repository][8] to your local system.

3. Open SWI-Prolog runtime environment.(Desktop Version)

4. In the terminal, consult path to your program ---> consult('PATH-TO-YOUR-FILE/SER502-Spring2020-Team20/src/runtime/litepiler.pl'). 

**For Example :-**

    consult('/Users/sarvanshprasher/Desktop/Study material/SER 502/SER502-Spring2020-Team20/src/runtime/litepiler.pl'). 

5. Now for running your program, type this in terminal --->  litepiler('<PATH-TO-YOUR-FILE/Program.lp>').

**For Example :-** 

    litepiler('/Users/sarvanshprasher/Desktop/Study material/SER 502/SER502-Spring2020-Team20/data/fibonacci.lp').

6. A new file wil be created which will contain the parse tree of program with extension .lpy . That parse tree will be automatically executed and loaded into interpreter for giving you the output value on terminal.

## Sample programs for language :


- **[Fibonacci Pattern:][9]**

    litepiler('/Users/sarvanshprasher/Desktop/Study material/SER 502/SER502-Spring2020-Team20/data/fibonacci.lp').

- **[Factorial of a number:][10]** 

    litepiler('/Users/sarvanshprasher/Desktop/Study material/SER 502/SER502-Spring2020-Team20/data/factorialNumber.lp').

- **[Power of a number:][11]** 

    litepiler('/Users/sarvanshprasher/Desktop/Study material/SER 502/SER502-Spring2020-Team20/data/powerOfNumber.lp').

- **[Ternary Operation:][12]** 


    litepiler('/Users/sarvanshprasher/Desktop/Study material/SER 502/SER502-Spring2020-Team20/data/ternary.lp').

- **[Printing Natural Numbers:][13]** 

    litepiler('/Users/sarvanshprasher/Desktop/Study material/SER 502/SER502-Spring2020-Team20/data/printNumber.lp').


- **[For Range Print Numbers:][14]** 

    litepiler('/Users/sarvanshprasher/Desktop/Study material/SER 502/SER502-Spring2020-Team20/data/rangeInForLoop.lp').

## Contributors :

- [Abhishek Haksar][1] 
- [Rohit Kumar Singh][2] 
- [Sarvansh Prasher][3] 
- [Surya Chatterjee][4]


  [1]: https://github.com/Abhi241296
  [2]: https://github.com/rohitksingh
  [3]: https://github.com/sarvanshprasher
  [4]: https://github.com/surya-de
  [5]: http://www.swi-prolog.org
  [6]: http://www.swi-prolog.org/download/stable
  [7]: https://github.com/sarvanshprasher/SER502-Spring2020-Team20/tree/master/data
  [8]: https://github.com/sarvanshprasher/SER502-Spring2020-Team20
  [9]: https://github.com/sarvanshprasher/SER502-Spring2020-Team20/blob/master/data/fibonacci.lp
  [10]: https://github.com/sarvanshprasher/SER502-Spring2020-Team20/blob/master/data/factorialNumber.lp
  [11]: https://github.com/sarvanshprasher/SER502-Spring2020-Team20/blob/master/data/powerOfNumber.lp
  [12]: https://github.com/sarvanshprasher/SER502-Spring2020-Team20/blob/master/data/ternary.lp
  [13]: https://github.com/sarvanshprasher/SER502-Spring2020-Team20/blob/master/data/printNumber.lp
  [14]: https://github.com/sarvanshprasher/SER502-Spring2020-Team20/blob/master/data/rangeInForLoop.lp
  


