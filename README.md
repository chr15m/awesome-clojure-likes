Mapping the constellation of [Clojure](https://en.wikipedia.org/wiki/Clojure)-like programming languages.

[Contribute](./contributing.md). [More](./more.md).

## Official variants

- [Clojure](https://clojure.org/) on the [JVM](https://en.wikipedia.org/wiki/Java_virtual_machine).
- [Clojure CLR](https://clojure.org/about/clojureclr) on the [Common Language Runtime](https://en.wikipedia.org/wiki/Common_Language_Runtime).
- [ClojureScript](https://github.com/clojure/clojurescript) in the browser.

## Clojure-likes

### [Carp](https://github.com/carp-lang/Carp)

> A language that borrows syntax from Clojure, designed for interactive and performance sensitive use cases like games, sound synthesis and visualizations.

- Clojure-like syntax with ML/Rust-inspired semantics and ownership-based memory management.
- Static type system with inference, annotations, and pattern matching for safe data extraction.
- Module system with interfaces and seamless C interoperability for system programming.
- Lisp macros and interactive REPL with developer-friendly features like "hole" debugging.

### [Hy](https://hylang.org/)

> Hy is a wonderful dialect of Lisp that's embedded in Python.

- [Try it](https://hylang.org/try-hy).
- [Source code](https://github.com/hylang/hy).
- High level of interop with host language.
- All Python tooling available.

### [Babashka](https://babashka.org/)

> Fast native Clojure scripting runtime. Avoid switching between Clojure and bash scripts. Enjoy your parens on the command line.

- [Source code](https://github.com/babashka/babashka).
- [Documentation](https://book.babashka.org/).
- Instant startup.
- Batteries included.
- Cross-platform.
- Multi-threaded.
- Task runner.
- Libraries & "pods".

### [Janet](https://janet-lang.org/)

> A functional and imperative programming language for scripting, embedding, and system programming with Lisp-like syntax.

- [Source code](https://github.com/janet-lang/janet).
- [Documentation](https://janet-lang.org/docs/index.html).
- [Try it](https://janet-lang.org).
- Lightweight and embeddable (single C file).
- 600+ functions in core library.
- PEG grammar engine for robust text processing.
- First-class macros and closures.
- Garbage collection.
- Built-in networking, threading, and file system functions.
- C FFI for native extensions.
- Erlang-style supervision trees.

### [jank](https://jank-lang.org/)

> jank is a native Clojure dialect hosted on LLVM with C++ interop.

- [Source code](https://github.com/jank-lang/jank).
- [Documentation](https://jank-lang.org/docs/).
- Strong Clojure compatibility; if it's valid Clojure and ClojureScript, it'll be valid jank.
- Built on an LLVM-based JIT. With AOT enabled, both statically and dynamically linked executables can be generated.
- Use your favorite nREPL editor plugin. jank uses an LLVM-based JIT to compile machine code on the fly.
- Utilize LLVM to link with your existing code or compile to WASM.
- [Work in progress](https://jank-lang.org/progress/).

### [Fennel](https://fennel-lang.org)

> Lua Lisp Language.

- [Try it](https://fennel-lang.org/main).
- [Source code](https://github.com/bakpakin/Fennel).
- [Documentation](https://fennel-lang.org/reference).
- [Learning Fennel from Clojure](https://fennel-lang.org/from-clojure).
- Full Lua compatibility.
- Zero overhead.
- Compile-time macros.
- Embeddable.
- Quite popular in [game development](https://itch.io/games/tag-fennel).

### [Lux](https://github.com/LuxLang/lux)

> A functional, statically-typed Lisp that will run on several platforms, such as the Java Virtual Machine and JavaScript interpreters.

- Implemented in Clojure.
- Inspired by Haskell, Clojure, ML.

### [Joker](https://joker-lang.org/)

> Joker is a small interpreted dialect of Clojure written in Go. It is also a Clojure(Script) linter.

- [Source code](https://github.com/candid82/joker).
- [Documentation](https://joker-lang.org/docs/latest/).
- Fast startup time.
- Sane error messages and stacktraces.
- Batteries included: send HTTP requests, read and parse JSON, work with file system, start external processes, etc.

### [Clojerl](https://clojerl.org/)

> Clojure implemented on the Erlang VM.

- [Try it](http://try.clojerl.online/).
- [Source code](https://github.com/clojerl/clojerl).
- Interoperability as smooth as possible, just like Clojure proper and ClojureScript do.
- Provide most Clojure abstractions.
- Provide all Erlang abstractions and toolset.
- Include a default OTP library in Clojerl.

### [ClojureDart](https://github.com/Tensegritics/ClojureDart)

> ClojureDart is a Clojure dialect to make native mobile and desktop apps using Flutter and the Dart ecosystem.

 * Utilize Dart and Flutter ecosystem with full interopability.
 * Develop cross-platform user interfaces.
 * Short path from Clojure to native binaries (iOS, Android, MacOS, Linux, Windows).
 * Develop web applications by compiling to JavaScript.
 * Production-ready: applications are being built with it.

### [Small Clojure Interpreter (SCI)](https://github.com/babashka/sci)

> A complete implementation of Clojure in Clojure for secure, sandboxed code evaluation.

- A lightweight, portable Clojure/ClojureScript interpreter for evaluating untrusted code
- Runs on JVM, GraalVM native, Node.js, and browsers (even with advanced compilation)
- Provides a secure alternative to `eval` with fine-grained control over allowed operations
- Supports most Clojure features: persistent data structures, macros, namespaces, dynamic vars
- Powers many popular Clojure tools including Babashka, nbb, Clerk, and Portal
- Mature, well-maintained project with extensive documentation and community adoption

### [nbb](https://github.com/babashka/nbb)

> Ad-hoc CLJS scripting on Node.js. Nbb's main goal is to make it easy to get started with ad hoc CLJS scripting on Node.js.

- Fast startup without relying on a custom version of Node.js.
- Small artifact (on the order of ~2Mb).
- First class macros.
- Support building small TUI apps using Reagent.
- Complement babashka with libraries from the Node.js ecosystem.

### [Cloture](https://github.com/ruricolist/cloture)

> An implementation of Clojure in Common Lisp.

- [Documentation](https://github.com/ruricolist/cloture/blob/master/README.md).
- Designed for seamless interoperation with Common Lisp.
- Clojure namespaces are implemented as Lisp packages.
- Uses FSet for implementing Clojure vectors, maps, and sets.
- Supports reader conditionals and Clojure's concurrency primitives.
- Can load clojure.test and run tests written in Clojure.

### [Phel](https://phel-lang.org/)

> A functional programming language that compiles to PHP. It is a dialect of Lisp inspired by Clojure and Janet.

- [Source code](https://github.com/phel-lang/phel-lang).
- [Documentation](https://phel-lang.org/documentation/).
- Runs on PHP's ecosystem.
- Implements persistent data structures (Lists, Vectors, Maps and Sets).
- First-class macros and recursive functions.
- Simple but powerful Lisp syntax with good error reporting.
- REPL available via Docker container.
- Created to enable functional programming on affordable/common PHP hosting.

### [Basilisp](https://github.com/basilisp-lang/basilisp)

> A Lisp dialect with Clojure syntax for Python.

- [Documentation](https://basilisp.readthedocs.io/).
- Implementation of a Clojure-like language that targets Python 3.8+.
- Seamless interoperability with Python modules and objects.
- Provides familiar Clojure abstractions: persistent collections, protocols, namespaces, and macros.
- REPL with syntax highlighting, autocomplete, and inline documentation.

### [Scittle](https://github.com/babashka/scittle)

> The Small Clojure Interpreter (SCI) exposed for usage in script tags.

- [Try it on CodePen](https://codepen.io/Prestance/pen/PoOdZQw).
- [Documentation](https://babashka.org/scittle/).
- Run Clojure(Script) directly in the browser without compilation.
- Tiny footprint (on the order of ~15kb).
- Support for popular CLJS libraries like reagent, re-frame, and promesa.
- Ideal for adding scripting capabilities to web applications.
- Example full stack web application available via [babashka-scittle-guestbook](https://github.com/kloimhardt/babashka-scittle-guestbook).

### [Calcit](http://calcit-lang.org/)

> Heavily influenced by Clojure APIs, Macros, persistent data structure. Previously compiling to Clojure.

- [Source code](https://github.com/calcit-lang/calcit).
- Implemented in Rust. It was previously compiled to Clojure to run.
- Builtin persistent data structure. Shares many functions/macros API designs from Clojure.
- Designed like Lisp but prefers indentation based syntax or GUI code editor.

### [Toccata](https://github.com/Toccata-Lang/toccata)

> A Clojure dialect that compiles to native executable using the Clang compiler.

- Self hosted.

### [Lokke](https://github.com/lokke-org/lokke)

> A full dialect of Clojure for Guile.

- [Documentation](https://lokke.gitlab.io/lokke/).
- Proper tail-recursion thanks to Guile.
- Clojure namespaces are implemented as Guile modules.
- Provides support for persistent data structures (vectors, hash-maps, hash-sets).
- Includes support for atoms, refs, futures, regex, and more.
- Experimental support for try/catch/finally with exception suppression.
- GMP-backed numeric tower with arbitrary precision integers.

### [JO Clojure](https://github.com/Zelex/jo_clojure)

> A fast, embeddable Clojure-like language implementation in C/C++.

- Native implementation of most of the Clojure core library.
- Extremely fast startup time compared to JVM Clojure.
- Implementations of persistent collections (lists, vectors, hash-maps, hash-sets).
- Software Transactional Memory (STM) that works seamlessly with atoms.

### [Convex Lisp](https://docs.convex.world/docs/tutorial/convex-lisp/convex-lisp)

> A Clojure-inspired lisp for decentralised economic systems

- [Try it](https://docs.convex.world/docs/tools/convex-repl).
- [Source code](https://github.com/Convex-Dev/convex).
- [Community Discord](https://discord.com/invite/xfYGq4CT7v).
- Core language and syntax is (almost) identical to Clojure.
- Designed for development of smart contracts and digital assets.
- Runs on the decentralised Convex Virtual Machine.
- High perfomance, real-time economic transaction processing.
- Content-addressable immutable data structures with orthogonal persistence and cryptographic verification.
- Supported by the non-profit Convex Foundation

### [Pixie](https://github.com/pixie-lang/pixie)

> A small, fast, native lisp with "magical" powers.

- Implemented in RPython.
- Runs on own VM.
- Dormant project.

### [Ferret](https://nakkaya.com/2016/06/10/ferret-a-hard-real-time-clojure-for-lisp-machines/)

> A Hard Real-Time Clojure for Lisp Machines.

- [Source code](https://github.com/nakkaya/ferret).
- Implemented in Clojure.
- Compiles to ISO C++11.
- Restricted subset of Clojure.
- Embedded systems focus.

### [Wisp](https://github.com/wisp-lang/wisp)

> A little Clojure-like Lisp in JavaScript.

- [Try it](http://www.jeditoolkit.com/wisp/).
- Native JavaScript types and function calls.
- Dormant project.

### [timl](https://github.com/tpope/timl)

> TimL is a Lisp dialect implemented in and compiling down to VimL, the scripting language provided by the Vim text editor.

- Implemented in Vim's scripting language.
- Dormant project.

### [Rhine](https://github.com/artagnon/rhine-ml)

> An OCaml compiler for an untyped lisp.

- Implemented in OCaml.
- Runs on the LLVM JIT.
- Dormant project.

### [Gherkin](https://github.com/alandipert/gherkin)

> A functional programming language and interpreter written in GNU Bash 4.

- Implemented in Bash 4.
- Dormant project.

### [ki](http://ki-lang.org/)

> A functional programming language that expands into JavaScript through a very thin layer of sweet.js macros.

- [Source code](https://github.com/lantiga/ki).
- Implemented in JavaScript.
- Intermix Lisp code with JavaScript.
- Dormant project.

### [CLClojure](https://github.com/joinr/clclojure)

> An experimental port of Clojure to Common Lisp.

- Implements Clojure's persistent data structures (vectors, maps, sets) in Common Lisp.
- Provides Clojure-like protocols, lazy sequences, and loop/recur functionality.
- Bridges Lisp-1/Lisp-2 differences with a unified lexical environment.
- Custom reader macros for Clojure data literals.
- Dormant project.

### [Clodiuno](https://nakkaya.com/clodiuno.html)

> A Clojure API for Arduino that allows Clojure developers to interface with the physical world using Arduino hardware.

- [Source code](https://github.com/nakkaya/clodiuno).
- Control Arduino hardware using Clojure.
- Supports two interfaces: USB via Firmata or WiFi via WiShield.
- Libraries available via Clojars.
- Includes examples for servo control, motor control, sensors, and more.
- Dormant project.

### [Esprit](https://github.com/mfikes/esprit)

> ClojureScript for ESP32 microcontrollers using Espruino.

- Runs ClojureScript on ESP32 hardware.
- Leverages Espruino as the JavaScript runtime.
- Enables IoT and embedded development with ClojureScript.
- Provides a way to use Clojure's functional programming paradigm on microcontrollers.
- Dormant project.

### [Carbonate](https://github.com/7even/carbonate)

> Clojure-inspired Lisp that transpiles to Ruby.

- Implemented in Ruby.
- Tries to cover Ruby's functionality with more concise code forms.
- Dormant project.

### [slisp](https://github.com/bailesofhey/slisp)

> Modern Lisp variant inspired by Python, Clojure & Arc.

- Implemented in C++.
- Modern, OO, both statically & dynamically typed.
- Dormant project.

### [Apricot](https://github.com/apricot-lang/apricot)

> Apricot is a programming language inspired by Clojure and Lisp that runs on the [Rubinius](http://rubini.us/) VM.

- Implemented in Ruby.
- Dormant project.

# Mal [make-a-lisp](https://github.com/kanaka/mal)

> Mal is a Clojure inspired Lisp interpreter. Mal is **implemented in >60 languages**.

- [Try it](https://kanaka.github.io/mal/).

Notable/usable implementations follow.

### [malc](https://github.com/dubek/malc)

> Mal (Make A Lisp) compiler

- Compiler for Mal, written in Mal itself.
- Compiles a Mal program to LLVM assembly language (IR), and then uses the LLVM optimizer, assembler and gcc linker to produce a binary executable.

### [miniMAL](https://github.com/kanaka/miniMAL)

> A Delightfully Diminutive Lisp. Implemented in < 1 KB of JavaScript with JSON source.

- [Try it](https://kanaka.github.io/miniMAL/).
- Uses JSON syntax.

### [mal/php](https://github.com/kanaka/mal/tree/master/php)

- Implemented in PHP.
- Interop with & runs where PHP does.

### [mal/ruby](https://github.com/kanaka/mal/tree/master/ruby)

- Implements the #mal IRC bot.
