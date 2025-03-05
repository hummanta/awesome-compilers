# awesome-compilers
An opinionated list of awesome compiler frameworks, libraries, software and resources.

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



## Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/hummanta/awesome-compilers/blob/main/CONTRIBUTING.md) for details. Thanks to all [contributors](https://github.com/hummanta/awesome-compilers/graphs/contributors); you rock!

***If you see a project or link here that is no longer maintained or is not a good fit, please submit a pull request to improve this document. Thank you!***
