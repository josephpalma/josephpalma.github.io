---
layout: essay
type: essay
title: Personal Design Patterns and Preferences
date: 2019-04-19
labels:
  - Factory Design
  - MVC Design
---

## **By Joe Palma**

### Personal Design Patterns and Preferences

## Design is Everywhere

Look around you and notice something that has a functional design. What is it? who made it? Before this object existed, what event took place that required its inception? 

As evolved cave people we use tools to do things, and engineers and creatives face issues of functionality all the time. We solve these issues by using existing tools in a new and different way, or designing our own to do such a task. However, the issue of optimal design is mutually exclusive.

Design patterns are repeatedable solutions to common software engineering problems. They are general templates that require optimization for your specific implementation. Using the patterns to their fullest takes expierence, but once fine tuned, they will work for you.

##My Expierence With Design Patterns

###Creational Design

I often find myself relying on the various forms of the creational design pattern when using languages like Java and C++. My code has relied on these designs:
    - Abstract factory in Java
    - Builder method in Java and C++
    - Factory method in C++
    - Prototyping in JavaScript

###Structural Design

The core of my systems re-usability comes from these various implementations of structural design to my code:
    - Adapter in Java
    - Bridge in Java and C++
    - Composite in Java and Javascript
    - Decorator in all languages
    - Flyweight in all languages
    - Private class data in Java
    - Proxy in Java and Javascript

###Behavorial Design

My creative side comes out when I use these patterns:
    -Chain of Responsibility in all languages
    -Interpreter in Javascript
    -Iterator in all languages
    -Mediator in JavaScript
    -Memento in all languages
    -Observer in Javascript
    -Null Object, State, and Strategy in all languages

##My Design Preferences

My expierence in the core languages, Java and C++, had me relying quite heavily on the factory designs. Utilizing the black boxes provided by the languages API is the most effective way to me achieve my goals in implementation. I often get creative with the builder design, using the constructor to do most of the work for me. Complex implementations require using the adapter technique, where simple ones can be done with a singleton instance, however I try to stray from using the singleton design pattern. The bridge design has proven successful for code reusability and is very effective when implementing algorithms.

When it comes to functional programming, my general go-to is Javascript. Besides the standard prototyping design pattern that comes with the language, I have discovered other best personal practices while using Javascript in Meteor. When implementing user-generated event handeling it is best to use the composite structure to seperate detatched but connected components. Within the composited structure I use the decorator, and flyweight patterns among others for my implementation.

The greatest in my opinon is the Model-View-Controller design pattern. Specifically, I have found the most success with the publish-subscribe system. Javascript is easily made reactive in Meteor with the application of this design. 