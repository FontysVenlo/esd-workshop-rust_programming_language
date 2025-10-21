## Slide 1

Rust is a programming language. It was created in 2006. Its one of the fastest growing programming languages currently on the market.

## Slide 2

It has an emphasis on safety, performance and productivity.

It bought it and cargo (a package manager for rust) are the most admired tools used by programers in the stack overflow survey of 2025.

Used in windows components, discord backend and linux kernel.

Discord switched from go to rust because of the problems that a garbage collector caused in their connection.

## Slide 3

Rust achieves good safety, performance and productivity due to the following features and others. These are some of the most important.

- Memory safety without garbage collector: it makes rust extremely fast since the programer manages memory directly similarly to C without memory leaks or similar problems.
- Cargo package manager: helps manage libraries and packages without the fear of versions causing problems
- Pattern marching: helps manage errors or problems without the risk of the program having unintended behavior
- Comprehensive error messages: rust has extremely good and detailed error messages due to all types being known at compile time
- Safe concurrency: rust inherently preventing problems such as race conditions
- Zero cost abstractions: Using abstraction (structs, functions etc) does not cause loss of performance
- Modern syntax: Rust has learned from older languages what to avoid and as such it tends to have cleaner shorter syntax.

## Slide 4

To give you a better idea of Rust we have compared it to two other languages c++ and java
- Memory safety: rust does not suffer memory leaks, c++ does and java avoid it trough a garbage collector
- Concurrency: unlike c++ and java rust has features specifically build in to avoid problems such as race conditions
- Performance: high in rust and c++ due to the lack of features like the java garbage collector that impact performance
- Ease of learning: rust tends to be harder to use due to the difficulties its safeguards can cause
- Ecosystem: rust is much less used compared to the most popular languages. It is however one of the more popular and currently rising
- Use in legacy systems: due to its relative recency rust is less used in already established system making it less likely that you will use it for a job

## Slide 5

Cargo is a rust package manager it helps you create new projects and manage libraries. New project can be created running and run using cargo commands and libraries can be added by just typing the name and version in the cargo toml file. When you update the cargo.lock file makes sure that your libraries don't update in a way that makes them work differently without your express permission.

## Slide 6

The most basic features of rust is creating a variable. In the first example we have all variables of different types: signed, unsigned, float, bool, etc. In the second we have an example of a variable being changed. If you run this you will get an error.

## Slide 7

To have a variable be changeable you nit to use mut. This shows all other programers whether a variable is meant to be changed.

Shadowing is also an option for when you want to "change" a variable type or reuse a variable name.

## Slide 8

Here are examples if, while and for the structures that you already know. Of note is the fact that if can be used to initialize/change variables and for iterates trough a list rather that incrementing a variable i.

## Slide 9

Here are two examples of functions both with and without variables

## Slide 10

Here we have an example of a struct. It is important to mention that rust does not have classes but you can use structs and implement functions on a struct to get the same effect.

## Slide 17

The goal of this exercise is to create your own small command line program. First we will spilt you into 4 groups. Then we will give each group 2 cheat sheets with rust syntax. You will then make a small command line program. An example of what you could do is a guessing game. The program has a number between 1 and 100 that you have to guess. Each time it tels you whether the number you guessed is lower or higher than the correct guess until you guess correctly at witch point the program ends. This is just an example of what we expect feel free to experiment with rust during the alloted time and try to include as many rust features as possible.

## Slide 18

Before we end this workshop does anybody have questions about rust before the end?

