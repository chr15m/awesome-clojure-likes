Mapping the constellation of [Clojure](https://en.wikipedia.org/wiki/Clojure)-like programming languages.

[Contribute](./contributing.md). [More](./more.md).

## Official variants

 * [Clojure](https://clojure.org/) on the [JVM](https://en.wikipedia.org/wiki/Java_virtual_machine).
 * [Clojure CLR](https://clojure.org/about/clojureclr) on the [Common Language Runtime](https://en.wikipedia.org/wiki/Common_Language_Runtime).
 * [ClojureScript](https://github.com/clojure/clojurescript) in the browser.

## Clojure-likes

### [Hy](http://hylang.org/)

> Hy is a wonderful dialect of Lisp that’s embedded in Python.

 * [Try it](https://try-hy.appspot.com/).
 * [Source code](https://github.com/hylang/hy).
 * High level of interop with host language.
 * All of available Python tooling available.
 * Actively developed.

### [Pixie](https://github.com/pixie-lang/pixie)

> A small, fast, native lisp with "magical" powers.

 * Implemented in RPython.
 * Runs on own VM.
 * Dormant project.

### [Clojerl](https://clojerl.org/)

> Clojure implemented on the Erlang VM.

 * [Try it](http://try.clojerl.online/).
 * [Source code](https://github.com/clojerl/clojerl).
 * Interoperability as smooth as possible, just like Clojure proper and ClojureScript do.
 * Provide most Clojure abstractions.
 * Provide all Erlang abstractions and toolset.
 * Include a default OTP library in Clojerl.

### [Fennel](https://fennel-lang.org)

> Lua Lisp Language.

 * [Try it](https://fennel-lang.org/main)
 * [Source code](http://github.com/source/page)
 * Full Lua compatibility.
 * Zero overhead.
 * Compile-time macros.
 * Embeddable.
 * [Learning Fennel from Clojure](https://fennel-lang.org/from-clojure)
 * Quite popular in [game development](https://itch.io/games/tag-fennel)

### [Lux](https://github.com/LuxLang/lux)

> A functional, statically-typed Lisp that will run on several platforms, such as the Java Virtual Machine and JavaScript interpreters.

 * Implemented in Clojure.
 * Inspied by Haskell, Clojure, ML.
 * Actively developed.

### [Wisp](https://github.com/Gozala/wisp)

> A little Clojure-like LISP in JavaScript.

 * [Try it](http://www.jeditoolkit.com/wisp/)
 * Native JavaScript types and function calls.
 * Maintenance mode.

### [Joker](https://joker-lang.org/)

> Joker is a small interpreted dialect of Clojure written in Go. It is also a Clojure(Script) linter.

 * [Source code](https://github.com/candid82/joker)
 * Fast startup time.
 * Sane error messages and stacktraces.
 * Batteries included: send HTTP requests, read and parse JSON, work with file system, start external processes, etc.

### [Ferret](https://nakkaya.com/2016/06/10/ferret-a-hard-real-time-clojure-for-lisp-machines/)

> A Hard Real-Time Clojure for Lisp Machines.

 * Implemented in Clojure.
 * Compiles to ISO C++11.
 * Restricted subset of Clojure.
 * Embedded systems focus.

### [ki](http://ki-lang.org/)

> A functional programming language that expands into JavaScript through a very thin layer of sweet.js macros.

 * [Source code](https://github.com/lantiga/ki)
 * Implemented in Javascript
 * Intermix LISP code with JavaScript.
 * Dormant project.

### [Toccata](https://github.com/Toccata-Lang/toccata)

> A Clojure dialect that compiles to native executable using the Clang compiler.

 * Self hosted.

### [Carbonate](https://github.com/7even/carbonate)

> Clojure-inspired Lisp that transpiles to Ruby.

 * Implemented in Ruby.
 * Tries to cover Ruby's functionality with more concise code forms.
 * Dormant project.

### [slisp](https://github.com/bailesofhey/slisp)

> Modern Lisp variant inspired by Python, Clojure & Arc.

 * Implemented in C++.
 * Modern, OO, both statically & dynamically typed.
 * Dormant project.

### [timl](https://github.com/tpope/timl)

> TimL is a Lisp dialect implemented in and compiling down to VimL, the scripting language provided by the Vim text editor.

 * Implemented in Vim's scripting language.
 * Dormant project.

### [Apricot](https://github.com/apricot-lang/apricot)

> Apricot is a programming language inspired by Clojure and Lisp that runs on the [Rubinius](http://rubini.us/) VM.

 * Implemented in Ruby.
 * Dormant project.

### [Gherkin](https://github.com/alandipert/gherkin)

> A functional programming language and interpreter written in GNU Bash 4.

 * Implemented in Bash 4.
 * Dormant project.

### [Rhine](https://github.com/artagnon/rhine-ml)

> An OCaml compiler for an untyped lisp.

 * Implemented in OCaml.
 * Runs on the LLVM JIT.
 * Dormant project.

### [Small Clojure Interpreter](https://github.com/borkdude/sci)

> A tiny implementation of Clojure in Clojure.

* Made to evaluate code from user input where `eval` is unsafe or unavailable.
* Early development.

### [Jank](https://jank-lang.org/)

> jank is strongly compatible with Clojure; its host is C++ on top of an LLVM-based JIT, with a built-in gradual type system.

* Any Clojure library without interop will compile into your jank projects.
* Built on an LLVM-based JIT. With AOT enabled, both statically and dynamically linked executables can be generated.
* Use your favorite nREPL editor plugin. jank uses an LLVM-based JIT to compile machine code on the fly.
* Built-in gradual type system which allows for malli-style type annotations which result in static type analysis.
* [Work in progress](https://jank-lang.org/progress/)

# Mal [make-a-lisp](https://github.com/kanaka/mal)

> Mal is a Clojure inspired Lisp interpreter. Mal is **implemented in 63 languages**.

 * [Try it](https://kanaka.github.io/mal/)

Notable/usable implementations follow.

### [malc](https://github.com/dubek/malc)

 > Mal (Make A Lisp) compiler

 * Compiler for Mal, written in Mal itself.
 * Compiles a Mal program to LLVM assembly language (IR), and then uses the LLVM optimizer, assembler and gcc linker to produce a binary executable.

### [miniMAL](https://github.com/kanaka/miniMAL)

> A Delightfully Diminutive Lisp. Implemented in < 1 KB of JavaScript with JSON source.

 * [Try it](https://kanaka.github.io/miniMAL/).
 * Uses JSON syntax.

### [mal/php](https://github.com/kanaka/mal/tree/master/php)

 * Implemented in PHP.
 * Interop with & runs where PHP does.

### [mal/ruby](https://github.com/kanaka/mal/tree/master/ruby)

 * Implements the #mal IRC bot.

