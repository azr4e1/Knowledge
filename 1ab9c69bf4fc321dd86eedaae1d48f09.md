---
title: Closures in Go
author: Lorenzo Drumond
date: 2024-01-29T10:27:12
last: 2024-01-29T10:34:36
zk_id: 1ab9c69bf4fc321dd86eedaae1d48f09
tags: #variadic #closure #values #expression #list #literals #type #golang #first_class_citizens #bubble #body #parameters #programming #signature #tuple #functions #declare
---


# Closures in Go
In Go, anonymous functions have something called _closure_.

Anonymous functions defined inside the calling function can see all variables that are in scope in the function. This is referred to as a closure.

Any function has access to the variables available in the scope where it's defined, and when this is a function literal, we call it a closure over those variables.

We can think of a closure as a sort of bubble, which traps all the variables in scope at the point where it's defined. If you pass that bubble as an argument to some other function, those variables will still be trapped inside the bubble and available for use when it gets there.

So a function literal is a closure over certain variables, which means that when the function is called, it will be able to access the value of that variable.

N.B.: The value the closure can access is however _not_ the value of when the function is defined, but the value of the variable when the function is _called_.

Any time you're updating a variable that's referenced by a closure, you need to be careful to not inadvertently get the wrong result when the closure is called.

# References
- John Arundel, For the Love of Go
