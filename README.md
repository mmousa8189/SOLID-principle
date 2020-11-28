# SOLID-principle

The pourpuse for thate to learn SOLID-principle.

when you're writing code are you doing it right that's the question that worries a lot of people and should probably be at least something you think about design patterns are best-practice concepts that we can implement into our code to make it better in some way think of them as guardrails to keep our codes safe.

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

**A class should only have a single responsibility, that is, only changes to one part of the software's specification should be able to affect the specification of the class.**

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

practice practice practice the more you practice this the better off you'll get the more comfortable you will be starting off with OCP already in your code and it also SRP don't forget that one so these two things imp main your code will be cleaner leave it'll be more streamlined

-------------------------------------------------------------

## Liskov Substitution Principle

The Liskov Substitution Principle defines some guidelines for maintaining inheritor substitution. Passing an object’s inheritor in place of the base class shouldn’t break any existing functionality in the called method. You should be able to substitute all implementations of a given interface with each other.

**Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.**

>covariance and contravariance:
>C# doesn’t allow modifying return types or parameter types in overriding methods (even if the return type is an inheritor of the return type in the base class). Therefore, it won’t struggle with the most common substitution violations: contravariance of method arguments (overriders must have the same or base types of parent methods) and covariance of return types (return types in overriding methods must be the same or an inheritor of the return types in the base class).

-------------------------------------------------------------

## Interface segregation principle

The principle states that no client should be forced to depend on methods that it doesn't use. A
client should never be forced to implement an interface that it doesn't use or client shouldn't be
forced to depend on methods that they don't use.

**Many client-specific interfaces are better than one general-purpose interface.**

Each interface should have a specific purpose. You shouldn’t be forced to implement an interface when your object doesn’t share that purpose. By extrapolation, the larger the interface, the more likely it includes methods that not all implementers can achieve. That’s the essence of the Interface Segregation Principle.

-------------------------------------------------------------
