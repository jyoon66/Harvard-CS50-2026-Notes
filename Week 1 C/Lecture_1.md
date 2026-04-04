### Welcome!

* In our previous session, we learned about Scratch, a visual programming language.
* Learning computer science concepts can be quite challenging. Indeed, it can feel like you are drinking from a fire hose. Remember: What is ultimately important is the gains you experience over these coming weeks and months through your hard work and study in this course.
* Indeed, all the essential programming concepts presented in Scratch will be utilized as you learn how to program any programming language. Functions, conditionals, loops, and variables found in Scratch are fundamental building blocks that you will find in any programming language.

### Source Code

* Recall that machines only understand binary. Where humans write *source code*, a list of instructions for the computer that is human readable, machines only understand what we can now call *machine code*. This machine code is a pattern of ones and zeros that produces a desired effect.
* It turns out that we can convert *source code* into machine code using a very special piece of software called a *compiler*. Today, we will be introducing you to a compiler that will allow you to convert source code in the programming language C into a machine code.

![alt text](image.png)

* Today, in addition to learning how to program, you will be learning how to write good code.

### Visual Studio Code for CS50

* The text editor that is utilized for this course is *Visual Studio Code*, aka *VS Code*, affectionately referred to as [cs50.dev](https://cs50.dev/), which can be accessed via that same URL.
* One of the most important reasons we utilize VS Code is that it has all the software required for the course already pre-loaded on it. This course and the instructions herein were designed with VS Code in mind.
* Manually installing the ncessary software for the course on your own computer is a cumbersome headache. Best always to utilize VS Code for assignments in this course.
* You can open VS code at [cs50.dev](https://cs50.dev/).
* The IDE can be divided into a number of regions:
![alt text](image-1.png)
   * Notice that there is a *file explorer* on the left side where you can find your files. Further, notice that there is a region in the middle called a *text editor* where you can edit your program. Finally, there is a `command line interface`, known as a *CLi*, *command line*, or *terminal window*, where we can send commands to the computer in the cloud.
* You will also notice in the graphical user interface (GUI) on the left-hand bar, various tools and a file explorer.
* Because this IDE is pre-configured with all the necessary software, you should use it to complete all assignments for this course.

### Hello World

* We will be using three commands to write, compile, and run our first program:

```sh
code hello.c

make hello

./hello
```
   * The first command, `code hello.c` creates a file and allows us to type instructions for this program. The second command, `make hello`, *compiles* the file from our instructions in C and creates an executable file called `hello`. The last command, `./hello`, runs the program called `hello`.
* We can build your first program in C by typing `code hello.c` into the terminal window. Notice that we deliberately lowercased the entire filename and included the `.c` extension. Then, in the text editor that appears, write code as follows: 

```c
// A program that says hello to the world

#include <stdio.h>

int main(void)
{
    printf("hello, world\n");
}
```
   * Note that every single character above serves a purpose. If you type it incorrectly, the program will not run. `printf` is a function that can output a line of text. Notice the placement of the quotes and the semicolon. Further, notice that the `\n` creates a new line after the words `hello, world`.
