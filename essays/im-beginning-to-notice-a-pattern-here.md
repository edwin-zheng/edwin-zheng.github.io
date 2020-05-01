---
layout: essay
type: essay
title: I’m Beginning to Notice a Pattern Here
# All dates must be YYYY-MM-DD format!
date: 2020-04-30
labels:
  - Software Engineering
  - Design Patterns
---

<h3>Reduce, Reuse, Recycle</h3>

Design patterns, a concept that seems important for a software engineer to know, but also something that may confuse a newcomer into the software engineering scene. I prefer to view design patterns as a plan that lays out how something will be done, which is what a design pattern may be in essence. However, this in itself is broad, so I would draw an analogy towards drawing. An artist, both experienced and new, may begin any drawing with a simple framework that lays out the basics. For example, when drawing a person, they may map out the joints of the person with simple lines and circles to represent the person. This lays out a framework for approach, similar to what using a design pattern does. Design patterns open a door to a certain style of house, and it is up to the designer, the software engineer, to make the house a good place to live.

<h3>There’s a pattern here!</h3>

The model view controller pattern is almost inescapable when working on a webpage that has any form of database. React holds two of those components, putting both the view and the controller inside the same file, but the view and controller are still present. AngularJS is also a framework that acts as the controller in a model view controller design pattern. Using MongoDB as the database for a React project completes the design pattern, with MongoDB being the model and React holding the view and the controller. Combining AngularJS with Java, and SQL creates the model and controller, with AngularJS linking HTML to the javascript. Observers are also useful for notifying components that are separate from each other. React has its own watchers that look for state changes, and AngularJS does too. AngularJS also has methods such as $broadcast and $on, which allows someone to notify a different controller that something has happened. One would have to be careful, as those methods are still subject to Javascript’s asynchronous nature, but carefully using promises can avoid such pitfalls.
