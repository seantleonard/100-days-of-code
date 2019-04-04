# 100 Days Of Code - Log
### Day 2: April 3, 2019 

**Today's Progress**: Continue Coding
## SignalR Tutorial [Microsoft Docs](https://docs.microsoft.com/en-us/aspnet/core/tutorials/signalr?view=aspnetcore-2.2&tabs=visual-studio-mac)
Issue running libman. Which can be fixed by create a link in my path [GitHub Issue](https://github.com/aspnet/LibraryManager/issues/367)
TL;DR

```bash 
ln -s ~/.dotnet/tools/libman /usr/local/bin/libman
```
* make links between files: [SuperUser](https://superuser.com/questions/606308/how-do-i-create-a-terminal-shortcut-to-this-path) | 
[Die.net](https://linux.die.net/man/1/ln)
* create codeblocks in Markdown , language list: [CodebaseHQ](https://support.codebasehq.com/articles/tips-tricks/syntax-highlighting-in-markdown)

Crash course in Web App with SignalR. Done in Javascript. 
### Day 1: April 2, 2019 

**Today's Progress**: Started Coding

## Thoughts:

The hardest part is getting started. Built a Library in .NET CORE 2.2
Built a unit testing project for the libary using xUnit testing tool.
Additionly, fought with VSCode and GitHub to properly update the forked project from 100 days of code. 
Two Types of Tests: 
### [Theory]
Theory allows you to pass a data source into your unit testing function. Each line of the data source runs through the function, so the function runs for as many lines of data you pass. 

**Definition** Theories are test which are only true for a particular set of data. 

### [Fact]
Fact allows you to assert the return value of functions. Basic assertions are 
* Assert.True
* Assert.IsEqual
* Assert.IsNotEqual
  
**Definition:** Facts are tests which are always true. They test invariant conditions.

**Invariant:**  a condition that can be relied upon to be true during the execution of a program. "Never changing"

## Git
* Your repository has no remotes configured to push to
* There is no tracking information for the current branch
  
Just started over by deleting all the projects directory files and git clone <repolink>

## Markdown
Added Markdown preview plugin to VSCode.
**Name:** Markdown Preview Enhanced

**Version:** 0.3.13

**Publisher:** Yiyi Wang

**VS Marketplace:** [Link](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) 

## Resources: 
[Building a complete .NET Core solution on macOS using Visual Studio for Mac](https://docs.microsoft.com/en-us/dotnet/core/tutorials/using-on-mac-vs-full-solution)
* WordCounter Library
* WordCounter Library Unit Tests
* WordCounter Console App

## Link to work: TBD

