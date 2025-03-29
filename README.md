# awesome-compilers
An opinionated list of awesome compiler frameworks, libraries, software and resources.

## Contents

[C/C++](#cc) · [Golang](#golang) · [Javascript](#javascript) · [Lisp](#lisp) · [Python](#python) · [Rust](#rust) · [Solidity](#solidity) · [Typescript](#typescript)

##  C/C++

> Inspired by [Awesome C++](https://github.com/fffaraz/awesome-cpp), organised and assembled from the [Compiler section](https://github.com/fffaraz/awesome-cpp?tab=readme-ov-file#compiler), for more details visit their project homepage. [MIT license](https://github.com/fffaraz/awesome-cpp#MIT-1-ov-file)

*List of C or C++ compilers*

- [8cc](https://github.com/rui314/8cc) - A Small C Compiler, It's intended to support all C11 language features while keeping the code as small and simple as possible.
- [c](https://github.com/ryanmjacobs/c) - Compile and execute C "scripts" in one go!
- [chibicc](https://github.com/rui314/chibicc) - chibicc is yet another small C compiler that implements most C11 features.
- [Clang](http://clang.llvm.org/) - A C compiler for LLVM. Supports C++11/14/1z C11. Developed by LLVM Team.
- [GCC](https://gcc.gnu.org/) - GNU Compiler Collection. Supports C++11/14/1z C11 and OpenMP.
- [PCC](https://github.com/IanHarvey/pcc) - A very old C compiler. Supports C99.
- [AMD C++ Compiler](https://www.amd.com/en/developer/aocc.html) - Developed by AMD.
- [Intel C++ Compiler](https://software.intel.com/en-us/c-compilers) - Developed by Intel.
- [Intel SPMD](http://ispc.github.io/) - Compiler for a variant of the C language, for single program, multiple data programming.
- [lcc](https://github.com/drh/lcc) - The lcc retargetable ANSI C compiler.
- [LLVM](http://llvm.org/) - Collection of modular and reusable compiler and toolchain technologies.
- [Microsoft Visual C++](https://docs.microsoft.com/en-us/cpp/dotnet/dotnet-programming-with-cpp-cli-visual-cpp?view=msvc-160) - MSVC, developed by Microsoft.
- [Open WatCom](https://github.com/open-watcom) - Watcom C, C++, and Fortran cross compilers and tools.
- [Oracle Solaris Studio](http://www.oracle.com/technetwork/server-storage/solarisstudio/overview/index.html) - C, C++ and Fortran compiler for SPARC and x86. Supports C++11. Available on Linux and Solaris.
- [TCC](http://bellard.org/tcc/) - A small C compiler written by Fabrice Bellard.

*List of online C or C++ compilers*

- [CodeChef](https://www.codechef.com/ide) - Online compiler supports multiple programming languages like Python, C++, C, JavaScript, Rust, Go, Kotlin, and many more.
- [Coliru](http://coliru.stacked-crooked.com/) - Online compiler/shell with support for various C++ compilers.
- [Compiler Explorer](http://gcc.godbolt.org/) - An interactive compiler with assembly output available.
- [CompileOnline](http://www.tutorialspoint.com/codingground.htm) - Compile and Execute C++ online on Linux.
- [Ideone](http://ideone.com/) - An online compiler and debugging tool which allows you to compile source code and execute it online in more than 60 programming languages.
- [OneCompiler](https://onecompiler.com/) - An online compiler supporting over 70 programming languages and database systems.
- [Programiz](https://www.programiz.com/cpp-programming/online-compiler) - An online compiler for learners and developers.
- [repl.it](https://repl.it/) - A powerful yet simple tools and platforms for educators, learners, and developers.
- [Rextester](http://rextester.com/runcode) - Online compiler which provides several compilers(Clang, GCC, MSVC) and several editors.
- [Try It Online](https://tio.run/) - TIO is a family of online interpreters for an evergrowing list of practical and recreational programming languages.
- [Wandbox](https://wandbox.org/) - An online Clang/GCC compiler with Boost available.
- [paiza.io](https://paiza.io/en) - An online C/C++ compiler with multiple files supporting feature, GitHub(gist) integration and collaborative editing.
- [InterviewBit](https://www.interviewbit.com/online-cpp-compiler/) - A simple and easy to use online C++ compiler.

*List of C or C++ debuggers*

- [Comparison of debuggers](https://en.wikipedia.org/wiki/Comparison_of_debuggers) - A list of Debuggers from Wikipedia.
- [GDB](https://www.gnu.org/software/gdb/) - GNU Debugger.
- [LLDB](http://lldb.llvm.org/) - The LLDB Debugger.
- [Metashell](https://metashell.readthedocs.org/) - An interactive template metaprogramming shell which includes the MDB metadebugger.
- [Valgrind](http://valgrind.org/) - A tool for memory debugging, memory leak detection, and profiling.
- [x64dbg](http://x64dbg.com/) - An open-source x64/x32 debugger for windows.

## Golang

*List of Golang compilers*

- [Go Compiler](https://github.com/golang/go) - The official Go compiler, supports AOT compilation, based on Plan 9 assembly and partially on LLVM.
- [llgo](https://github.com/go-llvm/llgo) - An older LLVM-based compiler for Go, now discontinued, but of historical value.
- [TinyGo](https://github.com/tinygo-org/tinygo) - A lightweight Go compiler based on LLVM, suitable for embedded systems and WebAssembly.

*Tools for parsing Go code and generating the abstract syntax tree (AST)*

- [antlr4-go](https://github.com/antlr/antlr4/tree/master/runtime/Go) - The Go runtime for ANTLR, can be used to parse various languages, including Go.
- [go/ast](https://pkg.go.dev/go/ast) - Go's standard library for AST parsing, often used in conjunction with `go/parser`.
- [go/parser](https://pkg.go.dev/go/parser) - The official Go parsing library, parses Go code and generates an AST.
- [golangci-lint](https://github.com/golangci/golangci-lint) - A linter that uses multiple Go parsers to perform static analysis and code formatting checks.
- [gocc](https://github.com/goccmack/gocc) - A Go-written LALR(1) parser generator, similar to YACC/Bison.
- [goyacc](https://godoc.org/golang.org/x/tools/cmd/goyacc) - YACC Implementation in Go. Standard LALR(1) parser generator.
- [Peg](https://github.com/pointlander/peg) - A PEG parser generator for Go, supports grammar rule definitions.
- [tuqqu/go-parser](https://github.com/tuqqu/go-parser) - Golang parser written in PHP.

*Tools for converting Go code to other languages*

- [c4go](https://github.com/Konstantin8105/c4go) - Transpile C code to Go code.
- [esp32](https://github.com/andygeiss/esp32-transpiler) - Transpile Go into Arduino code.
- [f4go](https://github.com/Konstantin8105/f4go) - Transpile FORTRAN 77 code to Go code.
- [Gno](https://github.com/gnolang/gno) - A smart contract language developed in the Cosmos ecosystem, based on Go syntax, supporting persistent computation.
- [go2hx](https://github.com/go2hx/go2hx) - Compiler from Go to Haxe to Javascript/C++/Java/C#.
- [GopherJS](https://github.com/gopherjs/gopherjs) - Transpiles Go code to JavaScript, allowing Go code to run in the browser.
- [Yaegi](https://github.com/traefik/yaegi) - A Go interpreter that allows Go code to be transpiled into executable Go syntax trees.

*Tools for debugging Go code*

- [Delve](https://github.com/go-delve/delve) - The official Go debugger, supports breakpoints, variable inspection, and Goroutine debugging.
- [gdb-go](https://sourceware.org/gdb/) - GNU Debugger (GDB) support for Go, but with limited functionality; Delve is recommended.
- [GoTrace](https://pkg.go.dev/runtime/trace) - Go runtime's built-in tracing tool, useful for concurrency analysis and performance tuning.
- [pprof](https://github.com/google/pprof) - A Go-built performance profiling tool, useful for CPU and memory analysis.

*List of Golang Variants*

- [cell-script](https://github.com/cell-labs/cell-script) - A new designed language for smart-contract programming on UTXO chain.
- [Gno](https://github.com/gnolang/gno) - A smart contract language in the Cosmos ecosystem, based on Go syntax, supporting persistent computation.
- [Gop (Goplus)](https://github.com/goplus/gop) - A Go variant focused on engineering computation, with Python-like dynamic features and meta programming.
- [Odin](https://github.com/odin-lang/Odin) - A systems programming language influenced by Go, similar to Go + Rust.
- [Vlang](https://github.com/vlang/v) - A language with Go-like syntax but more concise, faster compilation speed, and memory safety mechanisms.
- [Wa](https://github.com/wa-lang/wa/) - A general-purpose programming language designed for for WebAssembly.

## JavaScript

*List of JavaScript compilers*

- [GraalJS](https://github.com/oracle/graaljs) - JavaScript engine in GraalVM, allowing interoperability with JVM.
- [Hermes](https://hermesengine.dev/) - AOT JavaScript compiler by Meta, optimized for React Native.
- [JavaScriptCore (JSC)](https://webkit.org/) - JavaScript engine for WebKit, used in Safari.
- [QuickJS](https://github.com/bellard/quickjs) - Lightweight JavaScript engine supporting ES2020, suitable for embedded use.
- [SpiderMonkey](https://spidermonkey.dev/) - Mozilla’s JS engine, featuring Baseline and IonMonkey JIT.
- [swc](https://swc.rs/) - A super fast JavaScript compiler written in Rust, significantly faster than Babel.
- [V8](https://v8.dev/) - Google Chrome and Node.js JavaScript engine with JIT compilation.

*List of JavaScript transpilers*

- [Babel](https://babel.dev/) - Transpiles modern JavaScript into ES5 for compatibility.
- [esbuild](https://github.com/evanw/esbuild) - A high-speed JavaScript bundler and compiler with tree-shaking and minification.
- [sucrase](https://github.com/alangpierce/sucrase) - A fast JavaScript transpiler optimized for development.
- [traceur-compiler](https://github.com/google/traceur-compiler) - Traceur is a JavaScript.next-to-JavaScript-of-today compiler.

*List of Javascript interpreters*

- [Deno](https://deno.land/) - A modern JavaScript runtime, built on V8, with enhanced security.
- [Duktape](https://duktape.org/) - Lightweight JavaScript interpreter for embedded systems.
- [Espruino](https://www.espruino.com/) - JavaScript interpreter designed for microcontrollers like ESP8266/ESP32.
- [Jerryscript](https://github.com/jerryscript-project/jerryscript) - Ultra-lightweight JavaScript engine for IoT devices.
- [MuJS](https://github.com/ccxvii/mujs) - Minimal JavaScript interpreter with no dependencies.

*List of Javascript parsers*

- [Acorn](https://github.com/acornjs/acorn) - A lightweight ECMAScript parser that supports the latest ES standard.
- [Cherow](https://github.com/cherow/cherow) - A fast and spec-compliant ECMAScript parser.
- [Esprima](https://esprima.org/) - A widely used ECMAScript parser that generates ASTs.
- [Seafox](https://github.com/bathos/seafox) - A minimal JavaScript parser with ES2020 support.
- [Tree-sitter JavaScript](https://github.com/tree-sitter/tree-sitter-javascript) - Incremental JavaScript parser, used in LSP and syntax analysis.

*List of Javascript syntax libraries*

- [AST Explorer](https://astexplorer.net/) - An online tool to visualize JavaScript ASTs.
- [Escodegen](https://github.com/estools/escodegen) - Converts JavaScript AST back to source code.
- [Prettier](https://prettier.io/) - Code formatter that enforces a consistent style.
- [Recast](https://github.com/benjamn/recast) - JavaScript AST manipulation library for code transformation.
- [Terser](https://terser.org/) - Successor to UglifyJS, optimized for ES6+.
- [UglifyJS](https://github.com/mishoo/UglifyJS) - JavaScript minifier, optimizer, and obfuscator.

*List of Javascript debuggers*

- [Chrome DevTools](https://developer.chrome.com/docs/devtools) - Built-in Chrome debugging tools with breakpoints and performance analysis.
- [Firefox DevTools](https://firefox-source-docs.mozilla.org/devtools/) - Firefox’s debugging tools, similar to Chrome DevTools.
- [ndb](https://github.com/GoogleChromeLabs/ndb) - Enhanced Node.js debugger based on Chrome DevTools.
- [Node.js Inspector](https://github.com/node-inspector/node-inspector) - `node --inspect` for debugging Node.js with Chrome DevTools.

*List of JavaScript Variants*

- [CoffeeScript](https://coffeescript.org/) - A syntactic sugar layer over JavaScript, compiles to JS.
- [Flow](https://flow.org/) - A static type checker by Meta, similar to TypeScript but with optional typing.
- [JScript](https://en.wikipedia.org/wiki/JScript) - A deprecated JavaScript variant from Microsoft for older Internet Explorer versions.
- [LiveScript](http://livescript.net/) - A functional programming variant of CoffeeScript with pattern matching.
- [Nasal-Interpreter](https://github.com/ValKmjolnir/Nasal-Interpreter) - Nasal is an ECMAscript-like language.

## Lisp

### Clojure

- [Clojure](https://github.com/clojure/clojure) - The official Clojure compiler, compiles to JVM bytecode.
- [ClojureScript](https://github.com/clojure/clojurescript) - Compiles to JavaScript, targeting browsers and Node.js.
- [Babashka](https://github.com/babashka/babashka) - A GraalVM-based Clojure interpreter, optimized for scripting.
- [Joker](https://github.com/candid82/joker) - A lightweight Clojure interpreter written in Go.
- [Arcadia](https://github.com/arcadia-unity/Arcadia) - A Clojure implementation for Unity game development.

### Common Lisp

- [ABCL (Armed Bear Common Lisp)](https://abcl.org/) - A Common Lisp implementation for the JVM.
- [Clasp](https://github.com/clasp-developers/clasp/) - A Common Lisp implementation based on LLVM, interoperable with C++.
- [CMUCL](https://cmucl.org/) - An early high-performance Common Lisp implementation.
- [ECL (Embeddable Common Lisp)](https://gitlab.com/embeddable-common-lisp/ecl) - A lightweight implementation that compiles to C code.
- [LispWorks](https://www.lispworks.com/) - A commercial Common Lisp implementation supporting multiple platforms.
- [SBCL (Steel Bank Common Lisp)](https://github.com/sbcl/sbcl) - A high-performance JIT compiler based on CMUCL.

### Emacs Lisp

- [Emacs Bytecode Compiler](https://www.gnu.org/software/emacs/manual/elisp.html) - The built-in bytecode compiler for Emacs Lisp.
- [Native-Comp (gccemacs)](https://github.com/emacs-mirror/emacs/blob/master/etc/NEWS) - A native Emacs Lisp compiler using GCC, improving performance.

### Scheme

- [Bigloo](https://github.com/manuel-serrano/bigloo) - A Scheme compiler that generates C, JVM, and .NET code.
- [Chicken Scheme](https://www.call-cc.org/) - AOT compiler to C, suitable for embedded development.
- [Chez Scheme](https://github.com/cisco/ChezScheme) - A high-performance Scheme implementation supporting AOT and JIT.
- [Gambit](https://gambitscheme.org/) - Compiles Scheme to efficient C code.
- [Guile](https://www.gnu.org/software/guile/) - The GNU Scheme interpreter and compiler, embeddable in C applications.
- [Kawa](https://www.gnu.org/software/kawa/) - A Scheme implementation targeting the JVM.
- [Larceny](https://github.com/larcenists/larceny) - A Scheme compiler with multiple backend targets.
- [MIT/GNU Scheme](MIT/GNU Scheme) - A classic Scheme compiler.
- [Racket](https://racket-lang.org/) - A powerful Lisp variant, supporting JIT compilation and DSL creation.

### Other dialects and variants

- [Arc](http://arclanguage.org/) - A Lisp dialect developed by Paul Graham, focused on simplicity and flexibility.
- [AutoLISP](https://www.autodesk.com/developer-network/platform-technologies/autolisp) - A Lisp dialect integrated into AutoCAD for automating drawing tasks.
- [Calcit](https://github.com/calcit-lang/calcit) - Indentation-based ClojureScript dialect in Rust and compiling to JavaScript ES Modules.
- [Carp](https://github.com/carp-lang/Carp) - A statically typed Lisp for system programming, compiles to native code via AOT.
- [Clarity](https://github.com/clarity-lang) - A Lisp-like smart contract language for Stacks blockchain.
- [EuLisp](http://eulisp.org/) - A European Lisp dialect aimed at unifying features of Common Lisp and Scheme.
- [Fennel](https://github.com/bakpakin/Fennel) - A Lisp variant based on Lua, compiling to Lua code, ideal for LuaJIT.
- [Ferret](https://github.com/racket/ferret) - A Racket-style Scheme variant that supports WebAssembly.
- [Franz Lisp](https://en.wikipedia.org/wiki/Franz_Lisp) - An early Lisp implementation, historically significant but no longer maintained.
- [GOAL](https://github.com/open-goal/jak-project) - A Lisp dialect developed by Naughty Dog for PlayStation 2 game development.
- [Hy](https://github.com/hylang/hy) - A Lisp that compiles directly to Python’s AST for seamless integration with Python.
- [Interlisp](https://github.com/Interlisp) - An early Lisp dialect with an integrated programming environment, mainly used in Xerox systems.
- [ISLISP](http://islisp.info/) - A standardized Lisp dialect focused on providing a small yet powerful core language.
- [Janet](https://github.com/janet-lang/janet) - A lightweight Lisp supporting AOT and JIT compilation, suitable for embedded and scripting.
- [LeLisp](https://github.com/c-jullien/lelisp) - A Lisp dialect developed in France, mainly used for AI research.
- [LFE](https://github.com/rvirding/lfe) - A Lisp dialect running on the Erlang VM, combining Lisp macros with Erlang's concurrency model.
- [Maclisp](https://en.wikipedia.org/wiki/Maclisp) - A Lisp dialect developed at MIT in the 1960s, influential in later Lisp dialects.
- [MDL](https://en.wikipedia.org/wiki/MDL_(programming_language)) - A Lisp dialect developed at MIT for AI and computer science research.
- [newLISP](https://www.newlisp.org/) - A lightweight Lisp dialect suited for scripting and general programming tasks.
- [NIL](https://en.wikipedia.org/wiki/NIL_(programming_language)) - A Lisp implementation developed at MIT for VAX computers, no longer maintained.
- [PicoLisp](https://picolisp.com/) - A minimal and efficient Lisp dialect suitable for embedded systems and application development.
- [PSL](https://user.ceng.metu.edu.tr/~ucoluk/research/lisp/generalinfo.html) - A Lisp implementation designed to be portable across multiple hardware and OS platforms.
- [RPL](https://en.wikipedia.org/wiki/RPL_(programming_language)) - A Lisp dialect developed by Hewlett-Packard for its calculators, using Reverse Polish Notation.
- [SKILL](https://github.com/jonpry/Pill) - A Lisp dialect developed by Cadence Design Systems for electronic design automation (EDA).
- [Spice Lisp](https://en.wikipedia.org/wiki/Spice_Lisp) - A Lisp dialect historically used in the development of CMUCL.
- [T](https://mumble.net/~jar/tproject/) - A Scheme-derived Lisp dialect developed at Yale, designed for high-performance systems programming.
- [Zetalisp](https://en.wikipedia.org/wiki/Lisp_Machine_Lisp) - A Lisp dialect developed for Lisp Machines, influencing the development of Common Lisp.
- [Wasp Lisp](https://github.com/wasplang/wasp) - A Scheme-inspired language designed for WebAssembly and frontend development.

## Python

> Organising and assembling parts content from [Awesome Python](https://github.com/vinta/awesome-python), for more details visit their project homepage. [CC BY 4.0 license](https://github.com/vinta/awesome-python?tab=License-1-ov-file#readme)

*Implementations of Python*

- [cpython](https://github.com/python/cpython) - Default, most widely used implementation of the Python programming language written in C.
- [cython](https://github.com/cython/cython) - Optimizing Static Compiler for Python.
- [clpython](https://github.com/metawilm/cl-python) - Implementation of the Python programming language written in Common Lisp.
- [ironpython](https://github.com/IronLanguages/ironpython3) - Implementation of the Python programming language written in C#.
- [micropython](https://github.com/micropython/micropython) - A lean and efficient Python programming language implementation.
- [numba](https://github.com/numba/numba) - Python JIT compiler to LLVM aimed at scientific Python.
- [peachpy](https://github.com/Maratyszcza/PeachPy) - x86-64 assembler embedded in Python.
- [pypy](https://foss.heptapod.net/pypy/pypy) - A very fast and compliant implementation of the Python language.
- [pyston](https://github.com/pyston/pyston/) - A Python implementation using JIT techniques.
- [RustPython](https://github.com/RustPython/RustPython) - A Python Interpreter written in Rust.
- [Vyper](https://docs.vyperlang.org/) - Vyper is a contract-oriented, pythonic programming language that targets the Ethereum Virtual Machine (EVM).

*Interactive Python interpreters (REPL)*

- [bpython](https://github.com/bpython/bpython) - A fancy interface to the Python interpreter.
- [Jupyter Notebook (IPython)](https://jupyter.org/) - A rich toolkit to help you make the most out of using Python interactively.
- [ptpython](https://github.com/jonathanslenders/ptpython) - Advanced Python REPL built on top of the [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).

*List of Python debugging tools*

- [ipdb](https://github.com/gotcha/ipdb) - IPython-enabled [pdb](https://docs.python.org/3/library/pdb.html).
- [pudb](https://github.com/inducer/pudb) - A full-screen, console-based Python debugger.
- [manhole](https://github.com/ionelmc/python-manhole) - Debugging UNIX socket connections and present the stacktraces for all threads and an interactive prompt.
- [python-hunter](https://github.com/ionelmc/python-hunter) - A flexible code tracing toolkit.
- [py-spy](https://github.com/benfred/py-spy) - A sampling profiler for Python programs. Written in Rust.
- [vprof](https://github.com/nvdv/vprof) - Visual Python profiler.
- [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar) - Display various debug information for Django.
- [flask-debugtoolbar](https://github.com/pallets-eco/flask-debugtoolbar) - A port of the django-debug-toolbar to flask.
- [icecream](https://github.com/gruns/icecream) - Inspect variables, expressions, and program execution with a single, simple function call.
- [pyelftools](https://github.com/eliben/pyelftools) - Parsing and analyzing ELF files and DWARF debugging information.

## Rust

> Organising and assembling parts content from [Awesome Rust](https://github.com/rust-unofficial/awesome-rust), for more details visit their project homepage. [CC0-1.0 license](https://github.com/rust-unofficial/awesome-rust?tab=readme-ov-file#CC0-1.0-1-ov-file)

*List of Rust compilers*

- [rustc](https://github.com/rust-lang/rust/tree/master/compiler) - Rust compiler.
- [rust-analyzer](https://github.com/rust-lang/rust-analyzer) - A Rust compiler front-end for IDEs.
- [rustc_codegen_c](https://github.com/rust-lang/rustc_codegen_c) - This a C codegen backend for rustc, which lowers Rust MIR to C code and compiles it with a C compiler.
- [rustc_codegen_cranelift](https://github.com/rust-lang/rustc_codegen_cranelift) - create an alternative codegen backend for the rust compiler based on [Cranelift](https://github.com/bytecodealliance/wasmtime/blob/main/cranelift).
- [rustc_codegen_gcc](https://github.com/rust-lang/rustc_codegen_gcc) - libgccjit AOT codegen for rustc, loaded by the existing rustc frontend, but benefits from GCC.
- [rust-lang/llvm-project](https://github.com/rust-lang/llvm-project) - Rust-specific fork of LLVM.
- [rust-playground](https://github.com/rust-lang/rust-playground) - Allows you to experiment with Rust before you install it locally.

*List of Rust debuggers*

- [CodeLLDB](https://github.com/vadimcn/codelldb) - A native debugger extension for VSCode based on LLDB.
- [gdbgui](https://github.com/cs01/gdbgui) - Browser based frontend for gdb to debug C, C++, Rust, and go.
- [Tracexec](https://github.com/kxxt/tracexec)  - Tracer for execve{,at} and pre-exec behavior, launcher for debuggers.

*List of parsers*

- [Chomp](https://github.com/m4rw3r/chomp) - A fast monadic-style parser combinator.
- [Combine](https://github.com/Marwes/combine) - parser combinator library.
- [grmtools](https://github.com/softdevteam/grmtools/) - A LR parser with better error correction.
- [lady-deirdre](https://github.com/Eliah-Lakhin/lady-deirdre) - A framework for new programming languages and LSP servers.
- [LALRPOP](https://github.com/lalrpop/lalrpop) - LR(1) parser generator.
- [Nom](https://github.com/rust-bakery/nom) - parser combinator library.
- [Oak](https://github.com/ptal/oak) - A typed PEG parser generator (compiler plugin).
- [Pest](https://github.com/pest-parser/pest) - The Elegant Parser.
- [rust-peg](https://github.com/kevinmehall/rust-peg) - Parsing Expression Grammar (PEG) parser generator.
- [Tree-Sitter](https://github.com/tree-sitter/tree-sitter) - A parser generator tool and an incremental parsing library geared towards programming tools.

*Static analysis*

- [MIRAI](https://github.com/endorlabs/mirai) - an abstract interpreter operating on Rust's mid-level intermediate representation (MIR)
- [static_assertions](https://crates.io/crates/static_assertions) - Compile-time assertions to ensure that invariants are met
- [verus](https://github.com/verus-lang/verus) - Verified Rust for low-level systems code

*List of transpilers*

- [m2cgen](https://github.com/BayesWitnesses/m2cgen) - A CLI tool to transpile trained classic machine learning models into a native Rust code with zero dependencies.
- [c2rust](https://github.com/immunant/c2rust) - C to Rust translator and cross checker built atop Clang/LLVM.
- [Corrode](https://github.com/jameysharp/corrode) - A C to Rust translator written in Haskell.

*Other dialects and variants*

- [MoonBit](https://www.moonbitlang.com/) - An end-to-end programming language toolchain for cloud and edge computing using WebAssembly.

## Solidity

- [aderyn](https://github.com/Cyfrin/aderyn) - Rust-based solidity smart contract static analyzer designed to help find vulnerabilities in Solidity code bases.
- [charcoal](https://github.com/ourovoros-io/charcoal) - Charcoal is a Solidity-to-Sway translator written in Rust.
- [era-compiler-solidity](https://github.com/matter-labs/era-compiler-solidity) - ZKsync Compiler Toolchain for Solidity and Yul.
- [ethdebug](https://github.com/ethdebug/format) - A standard debugging data format for smart contracts on Ethereum-compatible networks.
- [evmdis](https://github.com/Arachnid/evmdis) - EVM Disassembler that performs static analysis on the bytecode to provide a higher level of abstraction than raw EVM operations.
- [ocaml-solidity](https://github.com/OCamlPro/ocaml-solidity) - Ocaml-solidity provides a Solidity parser and typechecker.
- [pyrometer](https://github.com/nascentxyz/pyrometer) - A tool for analyzing the security and parameters of a solidity smart contract.
- [Remix](https://remix.ethereum.org) - Online realtime compiler and runtime.
- [revive](https://github.com/paritytech/revive) - Solidity compiler and YUL recompiler to LLVM, targetting RISC-V on PolkaVM.
- [SIF](https://github.com/chao-peng/SIF) - Solidity code instrumentation and analysis framework.
- [slang](https://github.com/NomicFoundation/slang) - A modular set of compiler APIs empowering the next generation of Solidity code analysis and developer tooling.
- [Slither](https://github.com/crytic/slither) - Solidity static analysis framework, a suite of vulnerability detectors, prints visual information about contract details etc.
- [sol-repl](https://github.com/eagr/sol-repl) - a REPL to provide instant feedback for Solidity snippets.
- [sol-to-o1js](https://github.com/hummanta/sol-to-o1js) - Solidity Compiler & Transpiler for Mina.
- [sol2uml](https://www.npmjs.com/package/sol2uml) - Unified Modeling Language (UML) class diagram generator for Solidity contracts.
- [solana-solidity.js](https://github.com/solana-labs/solana-solidity.js) - Compile, deploy, and use Solidity contracts on Solana.
- [solang](https://github.com/hyperledger-solang/solang) - Solidity Compiler for Solana, Polkadot and Stellar.
- [solar](https://github.com/paradigmxyz/solar) - Blazingly fast, modular and contributor friendly Solidity compiler, written in Rust.
- [solc-js](https://github.com/ethereum/solc-js) - Javascript bindings for the Solidity compiler.
- [solc](https://github.com/deno-web3/solc) - Solidity compiler bindings for Deno.
- [solgraph](https://github.com/raineorshine/solgraph) - Visualize control flows for smart contract security analysis.
- [solhint](https://github.com/protofire/solhint) - Solhint is an open-source project to provide a linting utility for Solidity code.
- [Solidity Parser for JavaScript](https://github.com/solidity-parser/parser) - A Solidity parser for JS built on top of a robust ANTLR4 grammar.
- [solidity-parser-antlr](https://github.com/federicobond/solidity-parser-antlr) - A Solidity parser for JS built on top of a robust ANTLR4 grammar.
- [solidity-repl](https://github.com/raineorshine/solidity-repl) - Ethereum Solidity REPL.
- [solidity-rs](https://github.com/camden-smallwood/solidity-rs) - Solidity 0.8.X AST parsing and analysis in Rust.
- [solidity](https://github.com/ethereum/solidity) - Official Compiler for the Solidity Smart Contracts Programming Language.
- [SOLL](https://github.com/second-state/SOLL) - SOLL is a new compiler for generate Ewasm from solidity and yul.
- [Soltsice](https://github.com/Soltsice/Soltsice) - Solidity & TypeScript Integration, Configuration and Examples.
- [sulk](https://github.com/lukehedger/sulk) - Solidity compilation without the tears.
- [surya](https://github.com/Consensys/surya) - Utility tool for smart contract systems, offering a number of visual outputs and information about the contracts’ structure.
- [warp](https://github.com/NethermindEth/warp) - Warp is a Solidity to Cairo Compiler, write/migrate Solidity to Cairo for easy onboarding into the StarkNet ecosystem.

## TypeScript

*List of Typescript compilers*

- [TypeScript Compiler (tsc)](https://www.typescriptlang.org/) - The official TypeScript compiler that transpiles TS to JS with type checking.
- [TypeScript Go](https://github.com/microsoft/typescript-go) - A Go implementation of the TypeScript compiler.

*List of Typescript parsers*

- [TypeScript Compiler API](https://github.com/microsoft/TypeScript/wiki/Using-the-Compiler-API) - Official TypeScript AST and parsing tools.
- [swc parser](https://swc.rs/) - A superfast TypeScript parser written in Rust.

*List of Typescript syntax libraries*

- [Prettier](https://prettier.io/) - Code formatter for TypeScript.
- [ts-morph](https://github.com/dsherret/ts-morph) - TypeScript AST manipulation library based on the TypeScript Compiler API.

*List of Typescript debuggers*

- [VS Code Debugger](https://code.visualstudio.com/docs/nodejs/debugging) - Built-in TypeScript debugging support in VS Code.
- [WebStorm Debugger](https://www.jetbrains.com/webstorm/) - Advanced TypeScript debugging tools in WebStorm.

*List of TypeScript variants*

- [AssemblyScript](https://www.assemblyscript.org/) - A TypeScript-like language for WebAssembly.
- [ReScript](https://github.com/rescript-lang/rescript) - ReScript is a robustly typed language that compiles to efficient and human-readable JavaScript.

## Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/hummanta/awesome-compilers/blob/main/CONTRIBUTING.md) for details. Thanks to all [contributors](https://github.com/hummanta/awesome-compilers/graphs/contributors); you rock!

***If you see a project or link here that is no longer maintained or is not a good fit, please submit a pull request to improve this document. Thank you!***
