#CDX Coding Language

#Introduction

What is CDX?
	CDX is a high-level, class-based open-source programming language made with Python and C.
	It is developed by Cloudnix with the intention of making a programming language that makes developing games and applications easier.

	It is used for:
		Desktop applications
		Web applications
		Web servers and application servers
		Video Games
		And more!

#Installing CDX

#Get Started

In CDX, every application starts and begins with a class. Unlike Java and other programming languages, CDX's class is a way to seperate code instead to start an application

Let's create your first CDX file, called Main.cdx, which can be done on any text editor
The file should contain a "Hello World" message, which is written with the following code:

```
class Hello World:
	nc "Hello World"{
		console.print('Hello World')
		}
	end class
```
Don't worry if you don't understand the code above - we will discuss it in detail in later chapters. For now, focus on how to run the code above.

Save the code in any text editor application as "Main.cdx". Open Command Prompt (cmd.exe) or Terminal, navigate to the directory where you saved your file, and type "cdx Main.cdx":
The output should read:
```
Hello World
```
(Optional) Compile to .exe
You could compile your .cdx file to .exe for your application to run on any Windows PC
How to do it?
	Open Command Prompt (cmd.exe) or Terminal, navigate to the directory where you saved your file and type the following:
	
	cdx Main.cdx
	cdx compile Main.cdx
	cdx convertexe Main
	
	Then without any errors, your .exe application should be in the same folder/directory as your .cdx uncompiled file
Congratulations! You have written and executed your first CDX program.




