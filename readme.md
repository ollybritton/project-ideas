# Project Ideas
This is just a github repo which is designed to be a list of all my projects ideas and therefore a general source of inspiration for those in need of something to develop/code. This format and a couple of the ideas are based on [Joe Reynold's project list](https://github.com/joereynolds/what-to-code#command-line]).

Table of Contents
=================

   * [Project Ideas](#project-ideas)
      * [Programming Languages](#programming-languages)
      * [Command Line Tools](#command-line-tools)
      * [Local Tools](#local-tools)
      * [Websites](#websites)
      * [Services](#services)
      * [Desktop/Mobile Apps](#desktopmobile-apps)
      * [Games](#games)
      * [Improvements/Libraries](#improvementslibraries)
      * [Remakes/Reimplementations](#remakesreimplementations)

## Programming Languages
This may seem like a stupid suggestion, but if you are *really* stuck for ideas, try learning a new programming language. Try lean something completely unlike what you already know. For example, [Haskell](https://www.haskell.org/)is a great language because it's so different.

+ *[Haskell](https://www.haskell.org/)*: An advanced, purely functional programming language where functions have no side effects. It's not used very often (as with any functional language), but could be fun to learn and write some basic programs in. Some example code:
 
        primes = filterPrime [2..] 
        where filterPrime (p:xs) = 
                p : filterPrime [x | x <- xs, x `mod` p /= 0]

+ *[Go](https://golang.org/)*: A very fast programming language which compiles into machine code. Created by some of the best minds at Google & Bell Labs. Here's some sample code:

        package main
        import "fmt"

        func main() {
            fmt.Println("hello world")
        }

+ *[BrainFuck](https://www.wikiwand.com/en/Brainfuck)*: Not a very serious language, but one with a very fun limitation that can provide a lot of fun. BrainFuck only has 8 characters in the entire language (`+`, `-`, `[`, `]`, `.`, `,`, `>`, `>`), yet it is still technically Turing-complete. A (simple) hello world program:

        ++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>.

+ **Some More Inspiration:**
Some more esoteric programming languages like BrainFuck can be found on [Esolangs.org](https://esolangs.org/), and there's a good list of programming languages for jobs by [freecodecamp](https://medium.freecodecamp.org/best-programming-languages-to-learn-in-2018-ultimate-guide-bfc93e615b35).

There are many more examples of languages you can learn. What's more, if you don't want to learn a new language, why not challenge your skills using your existing knowledge and *[build your own programming language](https://medium.freecodecamp.org/the-programming-language-pipeline-91d3f449c919)*?

## Command Line Tools
__*Nothing Here Yet*__

## Local Tools
__*Nothing Here Yet*__

## Websites
__*Nothing Here Yet*__

## Services
__*Nothing Here Yet*__

## Desktop/Mobile Apps
__*Nothing Here Yet*__

## Games
__*Nothing Here Yet*__

## Improvements/Libraries
__*Nothing Here Yet*__

## Remakes/Reimplementations
__*Nothing Here Yet*__
