# What is A Month of Solid?

A Month of SOLID is a coding exercise to sharpen your software design skills while working on a "real-world" example.

Starting up from a "working" application, its design will be improved little by little, be it from new requirements
or from suggested refactorings, each one of them suggesting the application of a design principle.

## Software Requirements

The real application is written in C# targeting .NET Core 1.1.

So any development environment that allows writting code and compile it to netcore11 will do: Visual Studio 17, VSCode, Atom,...<br/>
All is welcome. It is all text, after all.

Code and assignments are delivered via GitHub, so certain familiarity with Git is expected.

# "Real-World" example

## Error Log Emailer

Given the high frequence of exceptions thrown by the variety of applications, a way to notify the CTO about exceptions thrown.

The network operations team needs a quick way to send a log file containing exceptions to the email inbox of the CTO.

### A Brilliant Solution

GUIs are overrated so you put your genious to work on a console application that takes the path of the log file,
sends an email to the worry-free CTO and logs the operations to the console.

The application works and you are the new hero of the minute.

However...
