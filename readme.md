# Project Ideas
This is just a github repo which is designed to be a list of all my projects ideas and therefore a general source of inspiration for those in need of something to develop/code. This format and a couple of the ideas are based on [Joe Reynold's project list](https://github.com/joereynolds/what-to-code#command-line]).

A ✅ symbol means that I have completed the project for myself. If it is avaliable, it should also be a link to the completed code.

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
+ *Youtube Alarm Clock*: A script that waits until a specified hour and then plays a given youtube video to wake a person up.

## Local Tools
__*Nothing Here Yet*__

## Websites
These are websites or online tools that are easily accesible and don't require much/any special setup.

+ *Meetup Today*: A very simple website which uses [Meetup](https://www.meetup.com/) and its API to find events that are happening today or tommorow and that are free to everyone.

+ *Recipie Shopping & Meal Planner*: A user inputs a meal plan for the upcoming week from a large list of breakfasts, lunches & dinners. The website would then generate a shopping list for the week which contained all the ingredients required.

+ *Youtube Clickbait Generator*: A website where somebody can play with some values and sliders and it will generate a clickbaity title of a youtube value accordingly. For example, I could select how cringey and depressing and it would be and a name of a video would be presented. Like this:

        I walked to the shop and... [SHOTS FIRED] [911 CALLED] [NOT CLICKBAIT]!!!!!!!
        MY CREEPY SUITCASE STORY [REAL GHOST] :{ [REAL STORY]
        ...ad infinitum

+ *Break this website*: A website is hosted on a virtual machine every week or so with a set of built in vunrabilities (like SQL injection, X-Site scripting...), and people have to race to see who can stop the website from being hosted the fastest.

## Services
__*Nothing Here Yet*__

## Desktop/Mobile Apps
+ *Baby App*: A app for mobile which contains a very easy bold and understandable interface, even for an infant. The app responds to inputs like shakes or random presses with stuff like sounds and vibrations. It's designed to keep a baby occupied for a short while.

## Bots
__*Nothing Here Yet*__

## Games
+ *Text RPG*: A command-line RPG with a story line, combat and levelling up systems. It could also be developped to have the look and feel of a terminal but actually be a standalone game, in order to get over technical difficulties that arise from the terminal, such as live inputs and key combinations.

## Improvements/Libraries
__*Nothing Here Yet*__

## Remakes/Reimplementations
__*Nothing Here Yet*__

## Hardware
+ *Raspberry Pi Security Camera*: A raspberry pi project that uses an ordinary webcam and turns it into a security camera. At the simpliest level it could just take pictures and save them, but with more complexity, it could do stuff like:

    * Live video streaming on device network
    * Detecting movement and sending a text alert

+ *Raspberry Pi WiFi Hotspot* ✅: A raspberry pi project where you plug in a USB Sim Dongle and it then broadcasts an internet signal using the data from that sim. Useful for travelling.