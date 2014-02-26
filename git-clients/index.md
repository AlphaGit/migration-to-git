---
layout: default
title: Git clients
---

### Git clients

There are a lot of available clients for Git, some of these expose the internal Git design and 
architecture to the user, others hides the real Git power simplifying it for non-technical 
users. 

In general, at least for programmers, it is a good think to know how Git works, because in will
allow us to take advantage of it. For that reason, most of the Git clients including a short-cut 
to Git command line tool.

#### Git command line tool

The original Git user interface is the command line tool. Since many of us are accustomed to using 
Visual Studio, it may intimidate, but, come on! we are 
[hackers](http://tools.ietf.org/html/rfc1392#page-21), right? It is a shame if we do not assume 
the challenge. What is more, Microsoft itself is taking that way with _C# compiler (csc)_, _Windows 
Azure Cross-Platform Command-Line Interface_, _TypeScript Compiler (tsc)_ and _PowerShell_.

![Posh-Git over PowerShell and Git bash](git-commandline.png)

It is possible to use Git command line tool with `cmd.exe` (discouraged) and also with _bash_ in Linux, 
Mac and also in Windows or you can use it with _PowerShell_. It is a nice PowerShell extension named 
Posh-Git.

##### Pros

* Complete functionality
* Very quick when you know the commands
* No impedance with Git internal behaviour

##### Cons

* Need to remember the commands
* Difficult to see diffs and branches

#### GitHub for Windows

#### GitHub for Mac

#### Git Extensions

[Git Extensions](https://code.google.com/p/gitextensions/) is a graphical user 
interface for Git that allows a complete Git control without using the command 
line. Optionally, on the installation process, it could install Git command 
line tool and Git bash.

![Git Extensions](git-extensions.png)

##### Git Extensions Pros

* Complete Git functionality.
* Near to one to one relation with command line commands.
* Easy to remember commands because they have icons
* Nice view of diffs and branches.

##### Git Extensions Cons

* It is not so quick as command line.
* Difficult to understand if you do not want to understand Git internal behaviour.

#### Atlassian SourceTree

#### Visual Studio