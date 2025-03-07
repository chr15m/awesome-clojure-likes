Mapping the constellation of [Clojure](https://en.wikipedia.org/wiki/Clojure)-like programming languages.

[Contribute](./contributing.md). [More](./more.md).

## Official variants

 * [Clojure](https://clojure.org/) on the [JVM](https://en.wikipedia.org/wiki/Java_virtual_machine).
 * [Clojure CLR](https://clojure.org/about/clojureclr) on the [Common Language Runtime](https://en.wikipedia.org/wiki/Common_Language_Runtime).
 * [ClojureScript](https://github.com/clojure/clojurescript) in the browser.

## Clojure-likes

### [Babashka](https://babashka.org/)

> Fast native Clojure scripting runtime. Avoid switching between Clojure and bash scripts. Enjoy your parens on the command line.

* Instant startup.
* Batteries included.
* Cross-platform.
* Multi-threaded.
* Task runner.
* Libraries & "pods".
* Actively developed.

### [nbb](https://github.com/babashka/nbb)

> Ad-hoc CLJS scripting on Node.js. Nbb's main goal is to make it easy to get started with ad hoc CLJS scripting on Node.js.

* Fast startup without relying on a custom version of Node.js.
* Small artifact (current size is around 1.2MB).
* First class macros.
* Support building small TUI apps using Reagent.
* Complement babashka with libraries from the Node.js ecosystem.

### [Squint/Cherry](https://github.com/squint-cljs/)

> Squint is a compiler for an experimental dialect of ClojureScript. A tool to target JS for anything you would not use ClojureScript for, for whatever reason: performance, bundle size, ease of interop, etc.

> Cherry is an experimental ClojureScript to ES6 module compiler. Reducing friction between ClojureScript and JS tooling.

* Compile cljs to js with various tradeoffs.
* Available on NPM and can be used from JS tooling.

### [Hy](http://hylang.org/)

> Hy is a wonderful dialect of Lisp that’s embedded in Python.

 * [Try it](https://hylang.org/try-hy).
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

### [jank](https://jank-lang.org/)

> jank is a native Clojure dialect hosted on LLVM with C++ interop.

* Strong Clojure compatibility; if it's valid Clojure and ClojureScript, it'll be valid jank.
* Built on an LLVM-based JIT. With AOT enabled, both statically and dynamically linked executables can be generated.
* Use your favorite nREPL editor plugin. jank uses an LLVM-based JIT to compile machine code on the fly.
* Utilize LLVM to link with your existing code or compile to WASM.
* [Work in progress](https://jank-lang.org/progress/)

### [Calcit](http://calcit-lang.org/)

> Heavily influenced by Clojure APIs, Macros, persistent data structure. Previously compiling to Clojure.

* Implemented in Rust. It was previously compiled to Clojure to run.
* Builtin persistent data structure. Shares many functions/macros API designs from Clojure.
* Designed like Lisp but prefers indentation based syntax or GUI code editor.

### [CLClojure](https://github.com/joinr/clclojure)

> An experimental port of Clojure to Common Lisp.

* Implements Clojure's persistent data structures (vectors, maps, sets) in Common Lisp.
* Provides Clojure-like protocols, lazy sequences, and loop/recur functionality.
* Bridges Lisp-1/Lisp-2 differences with a unified lexical environment.
* Custom reader macros for Clojure data literals.
* Experimental/Work-in-progress status.

### [Cloture](https://github.com/ruricolist/cloture)

> An implementation of Clojure in Common Lisp.

* Designed for seamless interoperation with Common Lisp.
* Clojure namespaces are implemented as Lisp packages.
* Uses FSet for implementing Clojure vectors, maps, and sets.
* Supports reader conditionals and Clojure's concurrency primitives.
* Pre-alpha status but can load clojure.test and run tests written in Clojure.

### [Carp](https://github.com/carp-lang/Carp)

> A language that borrows syntax from Clojure, designed for interactive and performance sensitive use cases like games, sound synthesis and visualizations.

* Clojure-like syntax with ML/Rust-inspired semantics and ownership-based memory management.
* Static type system with inference, annotations, and pattern matching for safe data extraction.
* Module system with interfaces and seamless C interoperability for system programming.
* Lisp macros and interactive REPL with developer-friendly features like "hole" debugging.

### [Clodiuno](https://nakkaya.com/clodiuno.html)

> A Clojure API for Arduino that allows Clojure developers to interface with the physical world using Arduino hardware.

* Control Arduino hardware using Clojure.
* Supports two interfaces: USB via Firmata or WiFi via WiShield.
* Libraries available via Clojars.
* Includes examples for servo control, motor control, sensors, and more.

### [Phel](https://phel-lang.org/)

> A functional programming language that compiles to PHP. It is a dialect of Lisp inspired by Clojure and Janet.

* Runs on PHP's ecosystem (requires PHP >=8.2).
* Implements persistent data structures (Lists, Vectors, Maps and Sets).
* First-class macros and recursive functions.
* Simple but powerful Lisp syntax with good error reporting.
* REPL available via Docker container.
* Created to enable functional programming on affordable/common PHP hosting.

### [Esprit](https://github.com/mfikes/esprit)

> ClojureScript for ESP32 microcontrollers using Espruino.

* Runs ClojureScript on ESP32 hardware.
* Leverages Espruino as the JavaScript runtime.
* Enables IoT and embedded development with ClojureScript.
* Provides a way to use Clojure's functional programming paradigm on microcontrollers.

### [Lokke](https://github.com/lokke-org/lokke)

> A full dialect of Clojure for Guile.

* Proper tail-recursion thanks to Guile.
* Clojure namespaces are implemented as Guile modules.
* Provides support for persistent data structures (vectors, hash-maps, hash-sets).
* Includes support for atoms, refs, futures, regex, and more.
* Experimental support for try/catch/finally with exception suppression.
* GMP-backed numeric tower with arbitrary precision integers.

### [JO Clojure](https://github.com/Zelex/jo_clojure)

> A fast, embeddable Clojure-like language implementation in C/C++.

* Native implementation of most of the Clojure core library.
* Extremely fast startup time compared to JVM Clojure.
* Implementations of persistent collections (lists, vectors, hash-maps, hash-sets).
* Software Transactional Memory (STM) that works seamlessly with atoms.
* Future plans include compilation to native executables and tensor/ML operations.

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
