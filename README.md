# SOLID-principle

The pourpuse for thate to learn SOLID-principle.

## Getting started with SOLID-principle using "C#"

This is an overview of what solid-principles are, and why a developer might want to use it.

## Installation or Setup

You can use any IDE (Visual studio or VSCode) and OOP language to implement S.O.L.I.D Principles. In the sample code I
have used C# as it is the most widely used language in .NET word and is closely.

Reference related to the source code and explanation of the lesson please follow the below link:
[IAmTimCorey](https://www.youtube.com/user/IAmTimCorey/videos "The best easy videos for developers").

### Table of Contents

- [S.O.L.I.D Overview](https://github.com/mmousa8189/SOLID-principle/blob/master/README.md#solid-overview)
- [Single Responsibility Principle](https://github.com/mmousa8189/SOLID-principle/blob/master/README.md#single-responsibility-principle)
- [The Open Closed Principle](https://github.com/mmousa8189/SOLID-principle/blob/master/README.md#the-open-closed-principle)
- The Liskov Substitution Principle
- The Interface Segregation Principle
- The Dependency Inversion Principle

-------------------------------------------------------------

## S.O.L.I.D Overview

As the process of writing software has evolved from the theoretical realm into a true engineering discipline, a number of principles have emerged. And when I say principle, I’m referring to a feature of the computer code that helps maintain the value of that code. Pattern refers to a common code scenario, whether good or bad.

For example, you might value computer code that works safely in a multi-threaded environment. You may value computer code that doesn’t crash when you modify code in another location. Indeed, you might value many helpful qualities in your computer code, but encounter the opposite on a daily basis.

There have been some fantastic software development principles captured under the SOLID acronym:
 **Single responsibility**, **Open for extension and closed for modification**, **Liskov substitution**, **Interface segregation**, and **Dependency injection**. You should have some familiarity with these principles.

-------------------------------------------------------------

## Single Responsibility Principle

There should never be more than one reason for change anything in software entities (class,function, file etc). A class, function, file etc should have only one reason to change.
> "Just because you can, doesn't mean you should"  

-------------------------------------------------------------

## The Open Closed Principle

Software entities (class, modules, functions etc).
**should be open for extension but closed for modification**.
that is, such an entity can allow its behaviour to be extended without modifying its.
The name open–closed principle has been used in two ways. Both ways use generalizations (for instance, inheritance or delegate functions) to resolve the apparent dilemma, but the goals, techniques, and results are different.

- A module will be said to be open if it is still available for extension. For example, it should be possible to add fields to the data structures it contains, or new elements to the set of functions it performs.

- A module will be said to be closed if [it] is available for use by other modules. This assumes that the module has been given a well-defined, stable description (the interface in the sense of information hiding).

The open closed principle
it talks about the idea of being open to extension but closed modification,
So our and we really focus on the accounts part of this the account dot create,
So our accounts class initially when we started making those changes we changed everything okay we we modify as we had if statements and switch statements and we're changing things left and right or making or introducing bugs and all the rest but when we went back and kind of redesign up a piece of this application,
So we actually didn't modify some things but once we did now our accounts class doesn't have to change ever unless there's a bug and instead now it's closed for modification but it's open for extension.

-------------------------------------------------------------
