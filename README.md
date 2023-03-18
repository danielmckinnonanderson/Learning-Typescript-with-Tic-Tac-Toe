# Learning Typescript with Tic-Tac-Toe

A do-it-yourself project aimed at beginner developers, meant to take a person who has done a couple Javascript tutorials online and introduce them to developing fully-fledged programs given written requirements.
Please read this entire document before getting started!

#### Prerequisites
- Familiarity with the basic syntax of Javascript / Typescript -- Primitive types & objects, for loops, if statements, functions, etc.
  If you've written Javascript but never Typescript, it's ok! All Javascript is valid Typescript and can be written in a Typescript file (`.ts`), you will still get the benefits of [type safety](https://en.wikipedia.org/wiki/Type_safety)!
- [`git` installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
- [`Node.js` installed](https://nodejs.org/en/download).
- A code editor program. There's a lot out of them out there, pick one that makes you feel warm and fuzzy inside.
- Willing to use a terminal: Command Prompt on Windows, Terminal on Mac.
  The terminal can be intimidating at first, but I promise it's not scary.
  The terminal is your friend.
- __Create your own fork of this repository for you to work out of.__ If you don't know how to do this, you can read GitHub's docs [here](https://docs.github.com/en/github-ae@latest/get-started/quickstart/fork-a-repo).


#### This repository contains:
- A starter project, meant to be the foundation for what you the student will build.
- A markdown document containing descriptions of the features that must be built for the application.
  Each of these features will be described using detail that may be unfamiliar to you--The terminology used is intentionally chosen to introduce you to important concepts that it is good for new developers to learn.
  When you see words and concepts that are unfamiliar to you, treat that as a cue to go and do some exploring on those subjects. You'll learn a lot that way :)


#### What should I do if I'm brand new to this stuff?
Let's say you literally just downloaded the software in the prerequisites for the very first time, you managed to create a fork of this repository for yourself, and now you're unsure where to begin.


Open your system's terminal--That's Command Prompt for Windows or Terminal for Mac.
Inside the terminal, you can type `dir` in Windows Command Prompt or `ls` on the Mac Terminal and press enter. The output is the contents of the folder you are currently in.
Your terminal likely opened to your home directory. You can change the directory you are in using the command `cd` on both Windows and Mac. `cd` expects you to type the directory you'd you like to change into, like `cd Documents`.
Use the `cd` command to navigate to the folder where you have your local copy of the project.
From our project directory, you can now use `npm` (Node Package Manager) commands to manage and run our program.


Now look at the file `package.json`.
This file describes your project's dependencies--The libraries and external code that it needs in order to run.
It describes them to you, the developer, but it also describes it to your project's _build system_.
This is the program that handles retrieving these external libraries for us off of the internet, putting them in the right place in our project, and updating or removing dependencies that we change later.
The build tool we use for this project is [Node Package Manager (called on our system using `npm` in our terminal)](https://docs.npmjs.com/cli/v9/commands/npm/).
The `package.json` file describes `"devDependencies"`. These are the names and versions of libraries that we need to have installed on our system in order to run the program.


Install the dependencies that are specified in the `package.json` file using the terminal command `npm install`.
When it finishes, you will see a new folder in your project called `node_modules`. This is the folder where the dependencies we needed got installed to.
We shouldn't edit anything in this folder, but now we can use code from our two `devDependencies` (`ts-node`, and `typescript`) in our own code.


Then, take a look at `main.ts`. This is the place where your program starts executing. This file contains some commentary explaining how it works and how to add new code.


Finally, take a look at [`stories.md`](./stories.md). This file details the tasks--or individual units of work--that you will need to develop for this project.
Each task in `stories.md` is written as a description of what the program should be able to do in order for the task to be considered complete.


