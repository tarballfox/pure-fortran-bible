# pure-fortran-bible
I recently discovered my love for Fortran. I got frustrated by lack of learning resources, especially related to more complicated stuff in terms of FFI. I chose a Discord bot as my first project (which wasn't wise) and immediate got into trouble with C FFI. This guide was inspired by the Pure Bash Bible, altough I do not copy ANYTHING from there (besides the idea). This guide mostly assumes GCC as your compiler though from what I checked, some stuff applies to others. This guide will cover mostly resources for beginners + examples with solutions to various problems broken down. This document might not be as "pure" as the PBB, however it focuses 100% on Fortran. 
## Learning resources
### Basic
#### Tutorial
The [fortran-lang](https://fortran-lang.org/learn/quickstart/) website covers everything from begineer to advanced topics. You will find almost everything here, but I find that it is kinda hard to look there for easily soluble details of advanced features. You need to start here.
### Advanced
This section is for you if you outgrown the begineer stuff (which is probably very quickly).
#### GCC
The [GCC docs](https://gcc.gnu.org/onlinedocs/gcc-16.2.0/gfortran/) are a great resource - they show you basically every feature supported under the compiler. Unfortunately, they do not show you how to deal with a particular problem. You look here if you wanna make a solution, not discover an already made one. 
#### MRedies
MRedies got a guide on [interfacing C in Fortran](https://github.com/MRedies/Interfacing-Fortran/tree/master).
This guide covers dealing with strings and structs. It has only 2 examples though which don't cover everything.
## Awesome-Fortran
In this sections I only list stuff that I have used and I think are great. 
### FPM
FPM is the Fortran Package Manager. You use it to install your dependencies, build project and manage it. 
#### JSON-Fortran
[JSON-Fortran](https://github.com/jacobwilliams/json-fortran) is basically what you use for JSON. jacobwilliams made a few other very cool Fortran projects that you might want to check out. This one is personally what I use for Fortran. (ISC)
#### Self insert slop
Yes, I know self-insert bad. I am developing easy wrapper/bindings (GPLv2) for [cesanta/mongoose](https://github.com/cesanta/mongoose/tree/master) and a proper discord bot/bot library in Fortran. It is just my learning project and it is just slop so ignore it. **Initial comit pending.**
#### http-client
[http-client](https://github.com/fortran-lang/http-client) is the simplest way to send HTTP requests and receive response in Fortran. I reccomend pairing it with JSON-Fortran. (MIT)
