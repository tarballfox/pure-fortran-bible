# pure-fortran-bible
## Salus populi suprema lex esto
This repository and document exists for the good of the people. **ALL** code examples are written from scratch. They are not based on ANY work, hence the CC0 license. I just ask that you use it for good.  Most of the code assumes a compiler with good standards compliance like gfortran (GCC 16.2 more specifically). In the readme there are links to various projects with diffrent licenses that may help you in your Fortran endeavours. 
## Learning resources
### Basic
#### Tutorial
The [fortran-lang](https://fortran-lang.org/learn/quickstart/) website covers almost anything. Check it out. 
### Advanced
#### GCC
The [GCC docs](https://gcc.gnu.org/onlinedocs/gcc-16.2.0/gfortran/) are a great resource - they show you basically every feature supported under the compiler.
#### MRedies
MRedies got a guide on [interfacing C in Fortran](https://github.com/MRedies/Interfacing-Fortran/tree/master).
This guide covers dealing with strings and structs. It has only 2 examples though which don't cover everything.
## Awesome-Fortran
In this sections I only list stuff that I have used and I think are great. 
### FPM
FPM is the Fortran Package Manager. You use it to install your dependencies, build project and manage it. 
#### JSON-Fortran
[JSON-Fortran](https://github.com/jacobwilliams/json-fortran) is basically what you use for JSON. jacobwilliams made a few other very cool Fortran projects that you might want to check out. This one is personally what I use for Fortran. (3-Clause BSD)
#### Self insert slop
Yes, I know self-insert bad. I am developing easy wrapper/bindings (GPLv2) for [cesanta/mongoose](https://github.com/cesanta/mongoose/tree/master) and a proper discord bot/bot library in Fortran. It is just my learning project and it is just slop so ignore it. **Initial comit pending.**
#### http-client
[http-client](https://github.com/fortran-lang/http-client) is the simplest way to send HTTP requests and receive response in Fortran. I reccomend pairing it with JSON-Fortran. (MIT)
