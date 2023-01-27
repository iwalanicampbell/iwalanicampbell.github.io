---
layout: essay
type: essay
title: "There Are No Dumb Questions But There Are Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2023-01-26
published: true
labels:
  - ICS314
  - Learning
---

<img width="200px" class="rounded float-start pe-4" src="../img/smart-questions/questions.png">
  
## Example Question Smart Way
```
Q: What is the "-->" operator in C++?
After reading Hidden Features and Dark Corners of C++/STL on comp.lang.c++.moderated, I was completely surprised that the following snippet compiled and worked in both Visual Studio 2008 and G++ 4.4.

Here's the code:
#include <stdio.h>
int main()
{
    int x = 10;
    while (x --> 0) // x goes to 0
    {
        printf("%d ", x);
    }
}

Output:

9 8 7 6 5 4 3 2 1 0
I'd assume this is C, since it works in GCC as well. Where is this defined in the standard, and where has it come from?
```
  All though this question might seem simple, this question is smart way to ask for help [Example 1](https://stackoverflow.com/questions/1642028/what-is-the-operator-in-c).  The inquirer asks the question using the type of coding language they want to code for.  They also give the full input code and output code.  The inqurier  received ten plus possible answers, and they were successful in inciting discussion from multiple users. The answers themselves were clear and were devoid of rudeness and hostility of forum members or hackers. 
  
  *There's no such thing as a stupid question*
## Example Question Not As Smart Way
  
  You might have heard that quote a lot, I agree with it there are no inherently dumb questions, but questions can be vague, or none descriptive like this one for example: [Example 2](https://stackoverflow.com/questions/26564442/code-not-working-on-machine) Looking at the rest of the description and example code provided its very hard to tell what is supposed to happen.  The code itself is only 4 lines and not in the full context of the rest of the code.  There has only been one response to the query and the response itself was not descriptive either.  The post also has some grammatical and punctuation errors.  By giving a vague question the people who can help you might not be able to solve the problem since they don't know what is fully going on. 
  
```
Q:code not working on machine

i am having an issue with code not working on my machine, the code its self is perfectly valid and compiles and runs on my girlfriends machine, however on my machine is giving me errors

imageView.animationImages = [UIImage(named: "Shake For Shot00000"),
        UIImage(named: "Shake For Shot00001"),
        UIImage(named: "Shake For Shot00002"),
at the very start of that code its telling me UIImage does not conform to protocol any object, then after i finish this array of uiimages i have

imageView.animationRepeatCount = 1.0
and that is giving me type int does not conform to protocol FloatLiteralConvertible.

i have run this same project folder on my girlfriends machine and it runs 100% fine, i have tried reinstalling Xcode and even reformatted my computer and a fresh install of mavericks and Xcode, nothing is working, i was hoping someone has had simmalir issues and can point me in the direction of fixing this short of buying a new machine
```
  
 
