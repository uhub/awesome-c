# awesome-c

A curated list of awesome C frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Debugging and Profiling](#debugging-and-profiling)
* Web
	* [Web Frameworks](#web-frameworks)
	* [Web Servers and Proxies](#web-servers-and-proxies)
* Data and Storage
	* [Databases](#databases)
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
* Machine Learning and AI
	* [LLM and Inference](#llm-and-inference)
	* [Machine Learning Frameworks](#machine-learning-frameworks)
* Networking and Distributed
	* [Networking](#networking)
	* [RPC and Messaging](#rpc-and-messaging)
	* [Distributed Systems](#distributed-systems)
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
	* [Monitoring and Observability](#monitoring-and-observability)
* User Interface
	* [GUI Toolkits](#gui-toolkits)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Graphics and Rendering](#graphics-and-rendering)
	* [Game Development](#game-development)
	* [Audio](#audio)
	* [Image and Video](#image-and-video)
* Security
	* [Cryptography](#cryptography)
	* [Security Tools](#security-tools)
	* [Reverse Engineering](#reverse-engineering)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
	* [Performance and Optimization](#performance-and-optimization)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Logging and Configuration](#logging-and-configuration)
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [General Purpose Libraries](#general-purpose-libraries)
* Systems and Hardware
	* [Operating Systems and Kernels](#operating-systems-and-kernels)
	* [Embedded and Firmware](#embedded-and-firmware)
* Science and Math
	* [Mathematics](#mathematics)
	* [Scientific Computing](#scientific-computing)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [SamyPesse/How-to-Make-a-Computer-Operating-System](https://github.com/SamyPesse/How-to-Make-a-Computer-Operating-System) - How to Make a Computer Operating System in C++
* [mytechnotalent/Reverse-Engineering](https://github.com/mytechnotalent/Reverse-Engineering) - A FREE comprehensive reverse engineering tutorial covering x86, x64, 32-bit/64-bit ARM, 8-bit AVR and 32-bit RISC-V architectures.
* [s-matyukevich/raspberry-pi-os](https://github.com/s-matyukevich/raspberry-pi-os) - Learning operating system development using Linux kernel and Raspberry Pi
* [DoctorWkt/acwj](https://github.com/DoctorWkt/acwj) - A Compiler Writing Journey
* [cstack/db_tutorial](https://github.com/cstack/db_tutorial) - Writing a sqlite clone from scratch in C
* [yanfeizhang/coder-kung-fu](https://github.com/yanfeizhang/coder-kung-fu) - 开发内功修炼
* [yourtion/30dayMakeOS](https://github.com/yourtion/30dayMakeOS) - 《30天自制操作系统》源码中文版。自己制作一个操作系统（OSASK）的过程
* [zpoint/CPython-Internals](https://github.com/zpoint/CPython-Internals) - Dive into CPython internals, trying to illustrate every detail of CPython implementation
* [firmianay/CTF-All-In-One](https://github.com/firmianay/CTF-All-In-One) - CTF竞赛权威指南
* [lotabout/write-a-C-interpreter](https://github.com/lotabout/write-a-C-interpreter) - Write a simple interpreter of C. Inspired by c4 and largely based on it.
* [y123456yz/reading-code-of-nginx-1.9.2](https://github.com/y123456yz/reading-code-of-nginx-1.9.2) - nginx-1.9.2源码通读分析注释，带详尽函数中文分析注释以及相关函数流程调用注释，最全面的nginx源码阅读分析中文注释，更新完毕
* [hackerschoice/thc-tips-tricks-hacks-cheat-sheet](https://github.com/hackerschoice/thc-tips-tricks-hacks-cheat-sheet) - Various tips & tricks
* [Ewenwan/ShiYanLou](https://github.com/Ewenwan/ShiYanLou) - 学习C & C++ & python&汇编语言 LLVM编译器 数据结构 算法 操作系统 单片机 linux 面试
* [cksystemsteaching/selfie](https://github.com/cksystemsteaching/selfie) - An educational software system of a tiny self-compiling C compiler, a tiny self-executing RISC-V emulator, and a tiny self-hosting RISC-V hypervisor.
* [mpitutorial/mpitutorial](https://github.com/mpitutorial/mpitutorial) - MPI programming lessons in C and executable code examples
* [mkirchner/linked-list-good-taste](https://github.com/mkirchner/linked-list-good-taste) - Linus Torvalds' linked list argument for good taste, explained
* [Hansimov/csapp](https://github.com/Hansimov/csapp) - 个人整理的《深入理解计算机系统》中文电子版（原书第 3 版）与实验材料：https://hansimov.gitbook.io/csapp/
* [0voice/ffmpeg_develop_doc](https://github.com/0voice/ffmpeg_develop_doc) - 2023年，最新音视频学习资料整理，项目（调试可用），ffmpeg命令手册，文章，编解码论文，视频讲解，面试题全套资料
* [agavrel/42_CheatSheet](https://github.com/agavrel/42_CheatSheet) - A comprehensive guide to 50 years of evolution of strict C programming, a tribute to Dennis Ritchie's language
* [HITSZ-OpenCS/HITSZ-OpenCS](https://github.com/HITSZ-OpenCS/HITSZ-OpenCS) - 哈尔滨工业大学（深圳）计算机专业课程攻略 | Guidance for courses in Department of Computer Science, Harbin Institute of Technology (Shenzhen)
* [wuxiaolie/Knowledge-Notes](https://github.com/wuxiaolie/Knowledge-Notes) - 开放个人技术学习过程中整理记录的所有笔记。包含C/C++，算法，Linux基础，Linux驱动，STM32+RTOS；嵌入式，总线协议，操作系统，计算机网络，人工智能；工程实践，项目开发，软件使用，校招面试等等。
* [brenns10/lsh](https://github.com/brenns10/lsh) - Simple shell implementation. Tutorial here ->
* [stas00/the-art-of-debugging](https://github.com/stas00/the-art-of-debugging) - The Art of Debugging Open Book
* [mytechnotalent/Hacking-Windows](https://github.com/mytechnotalent/Hacking-Windows) - A FREE Windows C development course where we will learn the Win32API and reverse engineer each step utilizing IDA Free in both an x86 and x64 environment.
* [luohaha/Chinese-uvbook](https://github.com/luohaha/Chinese-uvbook) - 翻译的libuv的中文教程
* [QuantumLeaps/modern-embedded-programming-course](https://github.com/QuantumLeaps/modern-embedded-programming-course) - Companion repository to the "Modern Embedded Systems Programming" video course.
* [trailofbits/ctf](https://github.com/trailofbits/ctf) - CTF Field Guide
* [zedshaw/learn-c-the-hard-way-lectures](https://github.com/zedshaw/learn-c-the-hard-way-lectures) - All of the code from Learn C The Hard Way, each project, plus the presentation slides used in the videos.
* [AlexFanw/HUSTER-CS](https://github.com/AlexFanw/HUSTER-CS) - 华中科技大学 计算机科学与技术学院 课程与实验资料💾
* [chenyahui/AnnotatedCode](https://github.com/chenyahui/AnnotatedCode) - 知名开源代码库的注释版：C++、Golang等 *(archived)*
* [MaJerle/c-code-style](https://github.com/MaJerle/c-code-style) - Recommended C code style and coding rules for standard C99 or later. Comes with AI agent skill to write, edit and format the code.
* [CodeWithHarry/The-Ultimate-C-Programming-Course](https://github.com/CodeWithHarry/The-Ultimate-C-Programming-Course) - This is the C language code and supplement material for the Ultimate C language Course on CodeWithHarry
* [hairrrrr/C-CrashCourse](https://github.com/hairrrrr/C-CrashCourse) - C语言教程+博客+代码演示+课程设计。 帮助初学者更好的理解 C 难点，提升代码量！ For beginners:C tuition/self-learning
* [vonzhou/CSAPP](https://github.com/vonzhou/CSAPP) - CSAPP,《深入理解计算机系统结构》2nd ，阅读与实践！
* [ustcwpz/USTC-CS-Courses-Resource](https://github.com/ustcwpz/USTC-CS-Courses-Resource) - USTC计算机学院课程资源
* [y123456yz/Reading-and-comprehense-linux-Kernel-network-protocol-stack](https://github.com/y123456yz/Reading-and-comprehense-linux-Kernel-network-protocol-stack) - linux内核网络协议栈源码阅读分析注释--带详尽中文分析注释以及相关流程分析调用注释，对理解分析内核协议栈源码很有帮助
* [ayoubfaouzi/cpu-internals](https://github.com/ayoubfaouzi/cpu-internals) - Intel / AMD CPU Internals
* [codr7/hacktical-c](https://github.com/codr7/hacktical-c) - A practical hacker's guide to the C programming language.
* [dddrrreee/cs140e-20win](https://github.com/dddrrreee/cs140e-20win) - cs140e course materials.
* [CN-annotation-team/redis7.0-chinese-annotated](https://github.com/CN-annotation-team/redis7.0-chinese-annotated) - Redis 7.0.5 版本——中文注释，持续更新！欢迎参与本项目！🍭🍭🍭
* [XWHQSJ/ebooks](https://github.com/XWHQSJ/ebooks) - A repository for ebooks， including C, C plus plus, Linux Kernel, Compiler, OS, Algorithm, Security, Database, Network, ML and DL
* [wangkuiwu/datastructs_and_algorithm](https://github.com/wangkuiwu/datastructs_and_algorithm) - Data struct and algorithm introduction and implementation in C/C++/Java.
* [yangminz/bcst_csapp](https://github.com/yangminz/bcst_csapp) - A C language repo to implement CSAPP
* [umanovskis/baremetal-arm](https://github.com/umanovskis/baremetal-arm) - An ebook about bare-metal programming for ARM
* [jianfengye/nginx-1.0.14_comment](https://github.com/jianfengye/nginx-1.0.14_comment) - nginx源码中文注释版
* [chrisjmccormick/word2vec_commented](https://github.com/chrisjmccormick/word2vec_commented) - Commented (but unaltered) version of original word2vec C implementation.
* [y123456yz/Reading-and-comprehense-redis-cluster](https://github.com/y123456yz/Reading-and-comprehense-redis-cluster) - 分布式NOSQL redis源码阅读中文分析注释，带详尽注释以及相关流程调用注释，提出改造点，redis cluster集群功能、节点扩容、槽位迁移、failover故障切换、一致性选举完整分析，对理解redis源码很有帮助，解决了source insight中文注释乱码问题,更新完毕
* [linyiqun/Redis-Code](https://github.com/linyiqun/Redis-Code) - redis键值数据库源码分析
* [plantegg/programmer_case](https://github.com/plantegg/programmer_case) - 程序员案例集锦

### Examples and Exercises

* [TheAlgorithms/C](https://github.com/TheAlgorithms/C) - Collection of various algorithms in mathematics, machine learning, computer science, physics, etc implemented in C for educational purposes.
* [NVIDIA/cuda-samples](https://github.com/NVIDIA/cuda-samples) - Samples for CUDA Developers which demonstrates features in CUDA Toolkit
* [remzi-arpacidusseau/ostep-code](https://github.com/remzi-arpacidusseau/ostep-code) - Code from various chapters in OSTEP (http://www.ostep.org)
* [kangjianwei/Data-Structure](https://github.com/kangjianwei/Data-Structure) - 《数据结构》-严蔚敏.吴伟民-教材源码与习题解析
* [begeekmyfriend/leetcode](https://github.com/begeekmyfriend/leetcode) - LeetCode in pure C
* [Exely/CSAPP-Labs](https://github.com/Exely/CSAPP-Labs) - Solutions and Notes for Labs of Computer Systems: A Programmer's Perspective 3rd Editon // 《深入理解计算机系统》第三版的实验文件、解答与笔记
* [MinhasKamal/CreepyCodeCollection](https://github.com/MinhasKamal/CreepyCodeCollection) - A Nonsense Collection of Disgusting Codes
* [TrisH0x2A/project-box](https://github.com/TrisH0x2A/project-box) - C projects: algorithms, games, and networking
* [flutter/codelabs](https://github.com/flutter/codelabs) - Flutter codelab examples
* [h0mbre/Learning-C](https://github.com/h0mbre/Learning-C) - A series of mini-projects used to learn C for beginners
* [AllAlgorithms/c](https://github.com/AllAlgorithms/c) - Implementation of All ▲lgorithms in C Programming Language *(archived)*
* [DreamAndDead/CSAPP-3e-Solutions](https://github.com/DreamAndDead/CSAPP-3e-Solutions) - CSAPP 3e Solutions
* [forthespada/MyPoorWebServer](https://github.com/forthespada/MyPoorWebServer) - 一款可运行的基于C++ 实现的WebServer服务器，基于《TCPIP网络编程》和《Linux高性能服务器编程》实现的服务器项目。
* [cloudflare/cloudflare-blog](https://github.com/cloudflare/cloudflare-blog) - Cloudflare Blog code samples
* [RainbowRoad1/Cgame](https://github.com/RainbowRoad1/Cgame) - 一些用C编写的小游戏, 14行贪吃蛇 22行2048 22行俄罗斯方块 25行扫雷...以及各种小玩意
* [lemire/Code-used-on-Daniel-Lemire-s-blog](https://github.com/lemire/Code-used-on-Daniel-Lemire-s-blog) - This is a repository for the code posted on my blog
* [Billy-Ellis/Exploit-Challenges](https://github.com/Billy-Ellis/Exploit-Challenges) - A collection of vulnerable ARM binaries for practicing exploit development
* [Unity-Technologies/NativeRenderingPlugin](https://github.com/Unity-Technologies/NativeRenderingPlugin) - C++ Rendering Plugin example for Unity
* [jwasham/practice-c](https://github.com/jwasham/practice-c) - Part of my daily plan for studying C.
* [justin-lathrop/c](https://github.com/justin-lathrop/c) - C Programming Projects *(archived)*
* [nlsandler/write_a_c_compiler](https://github.com/nlsandler/write_a_c_compiler) - Test suite to help you write your own C compiler
* [jimon/osx_app_in_plain_c](https://github.com/jimon/osx_app_in_plain_c) - A simple showcase how to create a simple OS X app in plain C without any Objective-C
* [LeechanX/Data-Structures-and-Algorithms-in-C](https://github.com/LeechanX/Data-Structures-and-Algorithms-in-C) - 所有基础数据结构和算法的纯C语言实现，如各自排序、链表、栈、队列、各种树以及应用、图算法、字符串匹配算法、回溯、并查集等，献丑了
* [xxyzz/ostep-hw](https://github.com/xxyzz/ostep-hw) - Operating Systems: Three Easy Pieces(OSTEP) homework and project solutions
* [Adamkadaban/CTFs](https://github.com/Adamkadaban/CTFs) - CTF Cheat Sheet + Writeups / Files for some of the Security CTFs that I've done
* [raysan5/raylib-games](https://github.com/raysan5/raylib-games) - A collection of small sample games made with raylib
* [bloominstituteoftechnology/C-Web-Server](https://github.com/bloominstituteoftechnology/C-Web-Server) - A simple webserver written in C
* [yourtion/LearningMasteringAlgorithms-C](https://github.com/yourtion/LearningMasteringAlgorithms-C) - Mastering Algorithms with C 《算法精解：C语言描述》源码及Xcode工程、Linux工程
* [openglsuperbible/sb7code](https://github.com/openglsuperbible/sb7code) - Source code and supporting material for the 7th Edition of OpenGL SuperBible
* [munificent/mark-sweep](https://github.com/munificent/mark-sweep) - A simple mark-sweep garbage collector in C
* [OpenGLInsights/OpenGLInsightsCode](https://github.com/OpenGLInsights/OpenGLInsightsCode) - Source code for OpenGL Insights
* [igrr/esp32-cam-demo](https://github.com/igrr/esp32-cam-demo) - Demo for working with a camera on ESP32 *(archived)*
* [cirosantilli/cpp-cheat](https://github.com/cirosantilli/cpp-cheat) - MOVING TO: https://github.com/cirosantilli/linux-kernel-module-cheat#userland-content SEE README. C, C++, POSIX and Linux system programming minimal examples. Asserts used wherever possible. Hello worlds for cool third party libraries and build systems. Cheatsheets, tutorials and mini-projects. 移至：https://github.com/cirosantilli/linux-kernel-module-cheat#userland-content查看自述文件。 C，C ++，POSIX和Linux系统编程的最少示例。 尽可能使用断言。 酷第三方库和构建系统的世界。 备忘单，教程和小型项目。
* [ccpalettes/the-c-programming-language-second-edition-solutions](https://github.com/ccpalettes/the-c-programming-language-second-edition-solutions) - Solutions for all exercises in the book "The C Programming Language - Second Edition"(referred to as K&R, after its authors' initials) by Brian W. Kernighan and Dennis M. Ritchie.

## Language and Tooling

### Compilers and Interpreters

* [rui314/chibicc](https://github.com/rui314/chibicc) - A small C compiler
* [rswier/c4](https://github.com/rswier/c4) - C in four functions
* [Tencent/xLua](https://github.com/Tencent/xLua) - xLua is a lua programming solution for C# ( Unity, .Net, Mono) , it supports android, ios, windows, linux, osx, etc.
* [wren-lang/wren](https://github.com/wren-lang/wren) - The Wren Programming Language. Wren is a small, fast, class-based concurrent scripting language.
* [rui314/8cc](https://github.com/rui314/8cc) - A Small C Compiler
* [c3lang/c3c](https://github.com/c3lang/c3c) - Compiler for the C3 language
* [skeeto/w64devkit](https://github.com/skeeto/w64devkit) - Portable C and C++ Development Kit for x64 (and x86) Windows
* [marcobambini/gravity](https://github.com/marcobambini/gravity) - Gravity Programming Language
* [janet-lang/janet](https://github.com/janet-lang/janet) - A dynamic language and bytecode vm
* [zenc-lang/zenc](https://github.com/zenc-lang/zenc) - Write like a high-level language, run like C.
* [westes/flex](https://github.com/westes/flex) - The Fast Lexical Analyzer - scanner generator for lexing in C and C++
* [quickjs-zh/QuickJS](https://github.com/quickjs-zh/QuickJS) - QuickJS是一个小型并且可嵌入的Javascript引擎，它支持ES2020规范，包括模块，异步生成器和代理器。
* [jakogut/tinyvm](https://github.com/jakogut/tinyvm) - TinyVM is a small, fast, lightweight virtual machine written in pure ANSI C.
* [checkedc/checkedc](https://github.com/checkedc/checkedc) - Checked C is an extension to C that lets programmers write C code with bounds checking and improved type-safety. The goal is to let people easily make their existing C code type-safe and eliminate entire classes of errors.
* [TinyCC/tinycc](https://github.com/TinyCC/tinycc) - Unofficial mirror of mob development branch
* [cc65/cc65](https://github.com/cc65/cc65) - cc65 - a freeware C compiler for 6502 based systems
* [vnmakarov/mir](https://github.com/vnmakarov/mir) - A lightweight JIT compiler based on MIR (Medium Internal Representation) and C11 JIT compiler and interpreter based on MIR
* [drh/lcc](https://github.com/drh/lcc) - The lcc retargetable ANSI C compiler
* [tj/luna](https://github.com/tj/luna) - luna programming language - a small, elegant VM implemented in C *(archived)*
* [nature-lang/nature](https://github.com/nature-lang/nature) - The Nature Programming Language
* [atomvm/AtomVM](https://github.com/atomvm/AtomVM) - Tiny Erlang VM
* [pocketpy/pocketpy](https://github.com/pocketpy/pocketpy) - Portable Python 3.x Interpreter in Modern C for Game Scripting
* [vtereshkov/umka-lang](https://github.com/vtereshkov/umka-lang) - Umka: a statically typed embeddable scripting language
* [cesanta/mjs](https://github.com/cesanta/mjs) - Embedded JavaScript engine for C/C++
* [DanielXMoore/Civet](https://github.com/DanielXMoore/Civet) - A TypeScript superset that favors more types and less typing
* [rui314/9cc](https://github.com/rui314/9cc) - A Small C Compiler
* [xorvoid/sectorc](https://github.com/xorvoid/sectorc) - A C Compiler that fits in the 512 byte boot sector of an x86 machine
* [metacall/core](https://github.com/metacall/core) - MetaCall: The ultimate polyglot programming experience.
* [vinniefalco/LuaBridge](https://github.com/vinniefalco/LuaBridge) - A lightweight, dependency-free library for binding Lua to C++
* [pikasTech/PikaPython](https://github.com/pikasTech/PikaPython) - An ultra-lightweight Python interpreter that runs with only 4KB of RAM, zero dependencies. It is ready to use out of the box without any configuration required and easy to extend with C. Similar project: MicroPython, JerryScript.
* [Zaneham/Booth](https://github.com/Zaneham/Booth) - Open-source CUDA, Triton and HIP compiler targeting multiple GPU and CPU architectures.
* [justjake/quickjs-emscripten](https://github.com/justjake/quickjs-emscripten) - Safely execute untrusted Javascript in your Javascript, and execute synchronous code that uses async functions
* [WebAssembly/wasi-sdk](https://github.com/WebAssembly/wasi-sdk) - WASI-enabled WebAssembly C/C++ toolchain
* [Robert-van-Engelen/tinylisp](https://github.com/Robert-van-Engelen/tinylisp) - Lisp in 99 lines of C and how to write one yourself. Includes 21 Lisp primitives, garbage collection and REPL. Includes tail-call optimized versions for speed and reduced memory use.
* [alexfru/SmallerC](https://github.com/alexfru/SmallerC) - Simple C compiler
* [rui314/minilisp](https://github.com/rui314/minilisp) - A readable lisp in less than 1k lines of C
* [ThakeeNathees/pocketlang](https://github.com/ThakeeNathees/pocketlang) - A lightweight, fast embeddable scripting language.
* [Battelle/movfuscator](https://github.com/Battelle/movfuscator) - The single instruction C compiler
* [rxi/fe](https://github.com/rxi/fe) - A tiny, embeddable language implemented in ANSI C
* [ninia/jep](https://github.com/ninia/jep) - Embed Python in Java
* [cesanta/v7](https://github.com/cesanta/v7) - Embedded JavaScript engine for C/C++
* [sysprog21/shecc](https://github.com/sysprog21/shecc) - A self-hosting and educational C optimizing compiler
* [andrei-markeev/ts2c](https://github.com/andrei-markeev/ts2c) - Convert Javascript/TypeScript to C
* [skvadrik/re2c](https://github.com/skvadrik/re2c) - Lexer generator for C, C++, D, Go, Haskell, Java, JS, OCaml, Python, Rust, Swift, V and Zig.
* [RealNeGate/Cuik](https://github.com/RealNeGate/Cuik) - A Modern C11 compiler (STILL EARLY)
* [dibyendumajumdar/ravi](https://github.com/dibyendumajumdar/ravi) - Ravi is a dialect of Lua, featuring limited optional static typing, JIT and AOT compilers
* [Jamesbarford/holyc-lang](https://github.com/Jamesbarford/holyc-lang) - HolyC compiler & transpiler
* [z88dk/z88dk](https://github.com/z88dk/z88dk) - The development kit for over a hundred z80 family machines - c compiler, assembler, linker, libraries.
* [JuliaPoo/Artfuscator](https://github.com/JuliaPoo/Artfuscator) - A C compiler targeting an artistically pleasing nightmare for reverse engineers
* [jserv/amacc](https://github.com/jserv/amacc) - Small C Compiler generating ELF executable Arm architecture, supporting JIT execution
* [berry-lang/berry](https://github.com/berry-lang/berry) - A ultra-lightweight embedded scripting language optimized for microcontrollers.
* [HVML/PurC](https://github.com/HVML/PurC) - The prime HVML interpreter for C Language.
* [overmighty/i-use-arch-btw](https://github.com/overmighty/i-use-arch-btw) - "I use Arch btw" but it's a Turing-complete programming language.
* [larmel/lacc](https://github.com/larmel/lacc) - A simple, self-hosting C compiler
* [tekknolagi/carp](https://github.com/tekknolagi/carp) - "interesting" VM in C. Let's see how this goes. *(archived)*
* [VictorTaelin/Interaction-Calculus](https://github.com/VictorTaelin/Interaction-Calculus) - A programming language and model of computation that matches the optimal λ-calculus reduction algorithm perfectly.
* [jnz/q3vm](https://github.com/jnz/q3vm) - Q3VM - Single file (vm.c) bytecode virtual machine/interpreter for C-language input
* [ccxvii/mujs](https://github.com/ccxvii/mujs) - https://codeberg.org/ccxvii/mujs
* [LingDong-/wax](https://github.com/LingDong-/wax) - A tiny programming language that transpiles to C, C++, Java, TypeScript, Python, C#, Swift, Lua and WebAssembly 🚀
* [hexagonal-sun/bic](https://github.com/hexagonal-sun/bic) - A C interpreter and API explorer.
* [michaelforney/cproc](https://github.com/michaelforney/cproc) - C compiler (mirror)
* [c2lang/c2compiler](https://github.com/c2lang/c2compiler) - the c2 programming language
* [turbolent/w2c2](https://github.com/turbolent/w2c2) - Translates WebAssembly modules to portable C
* [justinmeza/lci](https://github.com/justinmeza/lci) - A LOLCODE interpreter written in C.
* [Beariish/bolt](https://github.com/Beariish/bolt) - High-performance, real-time optimized, and statically typed embedded language implemented in C.
* [tpoechtrager/cctools-port](https://github.com/tpoechtrager/cctools-port) - Apple cctools port for Linux and *BSD
* [MoarVM/MoarVM](https://github.com/MoarVM/MoarVM) - A VM with adaptive optimization and JIT compilation, built for Rakudo
* [felixangell/mac](https://github.com/felixangell/mac) - bytecode interpreter in c (blog post)
* [riolet/rix](https://github.com/riolet/rix) - Rix language combines the power of C language and the convenience of a high level language
* [ASDAlexander77/TypeScript2Cxx](https://github.com/ASDAlexander77/TypeScript2Cxx) - TypeScript to C++
* [lpsantil/rt0](https://github.com/lpsantil/rt0) - A minimal C runtime for Linux i386 & x86_64

### Build Systems

* [xmake-io/xmake](https://github.com/xmake-io/xmake) - 🔥 A cross-platform build utility based on Lua
* [Kitware/CMake](https://github.com/Kitware/CMake) - Mirror of CMake upstream repository
* [premake/premake-core](https://github.com/premake/premake-core) - Premake
* [tsoding/nob.h](https://github.com/tsoding/nob.h) - Header only library for writing build recipes in C.
* [distcc/distcc](https://github.com/distcc/distcc) - distributed builds for C, C++ and Objective C
* [ObKo/stm32-cmake](https://github.com/ObKo/stm32-cmake) - CMake for stm32 developing.
* [michaelforney/samurai](https://github.com/michaelforney/samurai) - ninja-compatible build tool written in C

### Debugging and Profiling

* [plasma-umass/coz](https://github.com/plasma-umass/coz) - Coz: Causal Profiling
* [iqiyi/xCrash](https://github.com/iqiyi/xCrash) - 🔥 xCrash provides the Android app with the ability to capture java crash, native crash and ANR. No root permission or any system permissions are required.
* [namhyung/uftrace](https://github.com/namhyung/uftrace) - Function graph tracer for C/C++/Rust/Python
* [Celtoys/Remotery](https://github.com/Celtoys/Remotery) - Single C file, Realtime CPU/GPU Profiler with Remote Web Viewer
* [open-telemetry/opentelemetry-ebpf-profiler](https://github.com/open-telemetry/opentelemetry-ebpf-profiler) - The production-scale datacenter profiler (C/C++, Go, Rust, Python, Java, NodeJS, .NET, PHP, Ruby, Perl, ...)
* [armink/CmBacktrace](https://github.com/armink/CmBacktrace) - Advanced fault backtrace library for ARM Cortex-M series MCU | ARM Cortex-M 系列 MCU 错误追踪库
* [cgdb/cgdb](https://github.com/cgdb/cgdb) - Console front-end to the GNU debugger
* [ianlancetaylor/libbacktrace](https://github.com/ianlancetaylor/libbacktrace) - A C library that may be linked into a C/C++ program to produce symbolic backtraces
* [vitoplantamura/BugChecker](https://github.com/vitoplantamura/BugChecker) - SoftICE-like kernel debugger for Windows 11
* [crash-utility/crash](https://github.com/crash-utility/crash) - Linux kernel crash utility NOTE: The github PRs are not accepted, please subscribe to mail list via https://lists.crash-utility.osci.io/admin/lists/devel.lists.crash-utility.osci.io/ for contribution and discussion. Or post your patch/issue to mail list: devel@lists.crash-utility.osci.io
* [everettjf/appletrace](https://github.com/everettjf/appletrace) - 🍎Objective C Method Tracing Call Chart
* [xroche/coffeecatch](https://github.com/xroche/coffeecatch) - CoffeeCatch, a tiny native POSIX signal catcher (especially useful for JNI code on Android/Dalvik)

## Web

### Web Frameworks

* [laruence/yaf](https://github.com/laruence/yaf) - Fast php framework written in c, built in php extension
* [jorisvink/kore](https://github.com/jorisvink/kore) - An easy to use, scalable and secure web application framework for writing web APIs in C or Python. || This is a read-only mirror, please see https://kore.io/mail and https://kore.io/source for information on how to contribute via the mailing lists.
* [boazsegev/facil.io](https://github.com/boazsegev/facil.io) - Your high performance web application C framework
* [davidmoreno/onion](https://github.com/davidmoreno/onion) - C library to create simple HTTP servers and Web Applications.
* [emweb/wt](https://github.com/emweb/wt) - Wt, C++ Web Toolkit
* [danielwaterworth/Raphters](https://github.com/danielwaterworth/Raphters) - [DEPRECATED] A web framework for C.
* [babelouest/ulfius](https://github.com/babelouest/ulfius) - Web Framework to build REST APIs, Webservices or any HTTP endpoint in C language. Can stream large amount of data, integrate JSON data with Jansson, and create websocket services
* [ashtonjamesd/lavandula](https://github.com/ashtonjamesd/lavandula) - a lightweight web framework in c
* [balde/balde](https://github.com/balde/balde) - A microframework for C based on GLib.
* [riolet/WAFer](https://github.com/riolet/WAFer) - WAFer is a C language-based software platform for scalable server-side and networking applications. Think node.js for C programmers.

### Web Servers and Proxies

* [lpereira/lwan](https://github.com/lpereira/lwan) - Experimental, scalable, high performance HTTP server
* [3proxy/3proxy](https://github.com/3proxy/3proxy) - 3proxy - tiny free proxy server
* [civetweb/civetweb](https://github.com/civetweb/civetweb) - Embedded C/C++ web server
* [jonashaag/bjoern](https://github.com/jonashaag/bjoern) - A screamingly fast Python 2/3 WSGI server written in C.
* [chobits/ngx_http_proxy_connect_module](https://github.com/chobits/ngx_http_proxy_connect_module) - A forward proxy module for CONNECT request handling
* [jeremycw/httpserver.h](https://github.com/jeremycw/httpserver.h) - Single header library for writing non-blocking HTTP servers in C
* [MapServer/MapServer](https://github.com/MapServer/MapServer) - Source code of the MapServer project. Please submit pull requests to the 'main' branch.
* [haywire/haywire](https://github.com/haywire/haywire) - Haywire is an asynchronous HTTP server framework written in C that's built using the event loop based libuv platform layer that node.js is built on top of.
* [FRiCKLE/ngx_cache_purge](https://github.com/FRiCKLE/ngx_cache_purge) - nginx module which adds ability to purge content from FastCGI, proxy, SCGI and uWSGI caches.
* [examplecode/mproxy](https://github.com/examplecode/mproxy) - c 语言实现的一个最小的http代理，代理支持设置加密隧道，可以躲避防火墙的监测
* [aperezdc/ngx-fancyindex](https://github.com/aperezdc/ngx-fancyindex) - Fancy indexes module for the Nginx web server
* [varnish/Varnish-Cache](https://github.com/varnish/Varnish-Cache) - Moved. New address: https://github.com/varnishcache/varnish-cache/ *(archived)*
* [alibaba/nginx-http-concat](https://github.com/alibaba/nginx-http-concat) - A Nginx module for concatenating files in a given context: CSS and JS files usually
* [zyearn/zaver](https://github.com/zyearn/zaver) - Yet another fast and efficient HTTP server
* [allinurl/gwsocket](https://github.com/allinurl/gwsocket) - fast, standalone, language-agnostic WebSocket server RFC6455 compliant
* [solusipse/ureq](https://github.com/solusipse/ureq) - Micro C library for handling HTTP requests on low resource systems.
* [vozlt/nginx-module-sysguard](https://github.com/vozlt/nginx-module-sysguard) - Nginx sysguard module

## Data and Storage

### Databases

* [citusdata/citus](https://github.com/citusdata/citus) - Distributed PostgreSQL as an extension
* [Netflix/dynomite](https://github.com/Netflix/dynomite) - A generic dynamo implementation for different k-v storage engines
* [vlcn-io/cr-sqlite](https://github.com/vlcn-io/cr-sqlite) - Convergent, Replicated SQLite. Multi-writer and CRDT support for SQLite
* [hydradatabase/columnar](https://github.com/hydradatabase/columnar) - Postgres-native columnar storage extension
* [symisc/unqlite](https://github.com/symisc/unqlite) - An Embedded NoSQL, Transactional Database Engine
* [citusdata/cstore_fdw](https://github.com/citusdata/cstore_fdw) - Columnar storage extension for Postgres built as a foreign data wrapper. Check out https://github.com/citusdata/citus for a modernized columnar storage implementation built as a table access method.
* [HypoPG/hypopg](https://github.com/HypoPG/hypopg) - Hypothetical Indexes for PostgreSQL
* [bloomberg/comdb2](https://github.com/bloomberg/comdb2) - Bloomberg's distributed RDBMS
* [Softmotions/ejdb](https://github.com/Softmotions/ejdb) - :snowboarder: EJDB2 — Embeddable JSON Database engine C library. Simple XPath like query language (JQL).
* [apache/cloudberry](https://github.com/apache/cloudberry) - One advanced and mature open-source MPP (Massively Parallel Processing) database. Open source alternative to Greenplum Database.
* [armon/bloomd](https://github.com/armon/bloomd) - C network daemon for bloom filters
* [traildb/traildb](https://github.com/traildb/traildb) - TrailDB is an efficient tool for storing and querying series of events
* [danielealbano/cachegrand](https://github.com/danielealbano/cachegrand) - cachegrand - a modern data ingestion, processing and serving platform built for today's hardware
* [alibaba/ApsaraCache](https://github.com/alibaba/ApsaraCache) - archived | ApsaraCache is a Redis branch originated from Alibaba Group. *(archived)*

### Database Clients and ORMs

* [phpredis/phpredis](https://github.com/phpredis/phpredis) - A PHP extension for Redis
* [redis/hiredis](https://github.com/redis/hiredis) - Minimalistic C client for Redis >= 1.2
* [yandex/odyssey](https://github.com/yandex/odyssey) - Scalable PostgreSQL connection pooler
* [SRombauts/SQLiteCpp](https://github.com/SRombauts/SQLiteCpp) - SQLiteC++ (SQLiteCpp) is a smart and easy to use C++ SQLite3 wrapper.
* [pganalyze/libpg_query](https://github.com/pganalyze/libpg_query) - C library for accessing the PostgreSQL parser outside of the server environment
* [session-replay-tools/cetus](https://github.com/session-replay-tools/cetus) - Cetus is high-performance middleware designed to provide transparent routing between your application and backend MySQL servers.
* [oracle/python-cx_Oracle](https://github.com/oracle/python-cx_Oracle) - Obsolete Python interface to Oracle Database, now superseded by python-oracledb
* [mongodb/mongo-c-driver](https://github.com/mongodb/mongo-c-driver) - The Official MongoDB driver for C language
* [ged/ruby-pg](https://github.com/ged/ruby-pg) - A PostgreSQL client library for Ruby
* [rogerbinns/apsw](https://github.com/rogerbinns/apsw) - Another Python SQLite wrapper
* [esnme/ultramysql](https://github.com/esnme/ultramysql) - A fast MySQL driver written in pure C/C++ for Python. Compatible with gevent through monkey patching. *(archived)*

### Serialization and Formats

* [DaveGamble/cJSON](https://github.com/DaveGamble/cJSON) - Ultralightweight JSON parser in ANSI C
* [nanopb/nanopb](https://github.com/nanopb/nanopb) - Protocol Buffers with small code size
* [ultrajson/ultrajson](https://github.com/ultrajson/ultrajson) - Ultra fast JSON decoder and encoder written in C with Python bindings
* [ibireme/yyjson](https://github.com/ibireme/yyjson) - The fastest JSON library in C
* [akheron/jansson](https://github.com/akheron/jansson) - C library for encoding, decoding and manipulating JSON data
* [json-c/json-c](https://github.com/json-c/json-c) - https://github.com/json-c/json-c is the official code repository for json-c. See the wiki for release tarballs for download. API docs at http://json-c.github.io/json-c/
* [ohler55/oj](https://github.com/ohler55/oj) - Optimized JSON
* [lloyd/yajl](https://github.com/lloyd/yajl) - A fast streaming JSON parsing library in C.
* [jmcnamara/libxlsxwriter](https://github.com/jmcnamara/libxlsxwriter) - A C library for creating Excel XLSX files.
* [cloudwu/pbc](https://github.com/cloudwu/pbc) - A protocol buffers library for C *(archived)*
* [protocolbuffers/upb](https://github.com/protocolbuffers/upb) - a small protobuf implementation in C *(archived)*
* [brianmario/yajl-ruby](https://github.com/brianmario/yajl-ruby) - A streaming JSON parsing and encoding library for Ruby (C bindings to yajl)
* [kgabis/parson](https://github.com/kgabis/parson) - Lightweight JSON library written in C.
* [libexpat/libexpat](https://github.com/libexpat/libexpat) - :herb: Fast streaming XML parser written in C99 with >90% test coverage; moved from SourceForge to GitHub
* [json-parser/json-parser](https://github.com/json-parser/json-parser) - Very low footprint DOM-style JSON parser written in portable ANSI C
* [vlm/asn1c](https://github.com/vlm/asn1c) - The ASN.1 Compiler
* [yaml/libyaml](https://github.com/yaml/libyaml) - Canonical source repository for LibYAML
* [maxmind/libmaxminddb](https://github.com/maxmind/libmaxminddb) - C library for the MaxMind DB file format
* [mpx/lua-cjson](https://github.com/mpx/lua-cjson) - Lua CJSON is a fast JSON encoding/parsing module for Lua
* [HDFGroup/hdf5](https://github.com/HDFGroup/hdf5) - Official HDF5® Library Repository
* [nicklockwood/FastCoding](https://github.com/nicklockwood/FastCoding) - A faster and more flexible binary file format replacement for NSCoding, Property Lists and JSON
* [kosma/minmea](https://github.com/kosma/minmea) - a lightweight GPS NMEA 0183 parser library in pure C
* [cesanta/frozen](https://github.com/cesanta/frozen) - JSON parser and generator for C/C++ with scanf/printf like interface. Targeting embedded systems.
* [armink/struct2json](https://github.com/armink/struct2json) - A fast convert library between the JSON and C structure. Implement structure serialization and deserialization for C. | C 结构体与 JSON 快速互转库，快速实现 C 结构体的序列化及反序列化
* [kovidgoyal/html5-parser](https://github.com/kovidgoyal/html5-parser) - Fast C based HTML 5 parsing for python
* [gabriel/yajl-objc](https://github.com/gabriel/yajl-objc) - Objective-C bindings for YAJL (Yet Another JSON Library) C library

## Machine Learning and AI

### LLM and Inference

* [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) - LLM inference in C/C++
* [colbymchenry/codegraph](https://github.com/colbymchenry/codegraph) - Pre-indexed code knowledge graph, auto syncs on code changes, for Claude Code, Codex, Gemini, Cursor, OpenCode, AntiGravity, Kiro, CoPilot, and Hermes Agent — fewer tokens, fewer tool calls, 100% local
* [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) - High-performance code intelligence MCP server. Indexes codebases into a persistent knowledge graph — average repo in milliseconds. 158 languages, sub-ms queries, 99% fewer tokens. Single static binary, zero dependencies.
* [JustVugg/colibri](https://github.com/JustVugg/colibri) - Run frontier MoE models on hardware you already own — pure C, zero deps, experts streamed from disk. Tiny engine, immense model. 🐦
* [karpathy/llama2.c](https://github.com/karpathy/llama2.c) - Inference Llama 2 in one file of pure C
* [TEN-framework/ten-framework](https://github.com/TEN-framework/ten-framework) - Open-source framework for conversational voice AI agents
* [FareedKhan-dev/kimi-k3-in-c](https://github.com/FareedKhan-dev/kimi-k3-in-c) - A 2.78-trillion-parameter Kimi K3 running inference on a single CPU in 8.24 GB of RAM. Portable C99: no BLAS, no framework, no GPU.
* [cactus-compute/cactus](https://github.com/cactus-compute/cactus) - Quantization, kernels, runtime and inference engine for mobiles, wearables, smart home and robots.
* [Facico/Chinese-Vicuna](https://github.com/Facico/Chinese-Vicuna) - Chinese-Vicuna: A Chinese Instruction-following LLaMA-based Model —— 一个中文低资源的llama+lora方案，结构参考alpaca
* [antirez/h3.c](https://github.com/antirez/h3.c) - MiniMax H3 inference engine for Mac computers
* [sqliteai/warp](https://github.com/sqliteai/warp) - Run the full 2.78-trillion-parameter Kimi K3 model or GLM-5.3-Flash beyond available RAM by streaming activated weights directly from NVMe. A dependency-free, embeddable C inference engine.
* [espressif/esp-claw](https://github.com/espressif/esp-claw) - ESP-Claw, a "Chat Coding" AI agent framework for IoT devices
* [marella/ctransformers](https://github.com/marella/ctransformers) - Python bindings for the Transformer models implemented in C/C++ using GGML library.
* [nmntz/bloomz.cpp](https://github.com/nmntz/bloomz.cpp) - C++ implementation for BLOOM

### Machine Learning Frameworks

* [catboost/catboost](https://github.com/catboost/catboost) - A fast, scalable, high performance Gradient Boosting on Decision Trees library, used for ranking, classification, regression and other machine learning tasks for Python, R, Java, C++. Supports computation on CPU and GPU.
* [codeplea/genann](https://github.com/codeplea/genann) - simple neural network library in C99
* [glouw/tinn](https://github.com/glouw/tinn) - A tiny neural network library
* [antirez/iris.c](https://github.com/antirez/iris.c) - Flux 2 image generation model pure C inference
* [apoorvnandan/tensor.h](https://github.com/apoorvnandan/tensor.h) - creating a tiny tensor library in raw C
* [doonny/PipeCNN](https://github.com/doonny/PipeCNN) - An OpenCL-based FPGA Accelerator for Convolutional Neural Networks
* [mit-han-lab/tinyengine](https://github.com/mit-han-lab/tinyengine) - [NeurIPS 2020] MCUNet: Tiny Deep Learning on IoT Devices; [NeurIPS 2021] MCUNetV2: Memory-Efficient Patch-based Inference for Tiny Deep Learning; [NeurIPS 2022] MCUNetV3: On-Device Training Under 256KB Memory
* [attractivechaos/kann](https://github.com/attractivechaos/kann) - A lightweight C library for artificial neural networks
* [100/Cranium](https://github.com/100/Cranium) - 🤖 A portable, header-only, artificial neural network library written in C99

## Networking and Distributed

### Networking

* [lionsoul2014/ip2region](https://github.com/lionsoul2014/ip2region) - Ip2region is an offline IP-to-Region localization library and IP data management framework with both IPv4 and IPv6 supports, 10-microsecond level query efficiency, xdb search client for many programming languages
* [skywind3000/kcp](https://github.com/skywind3000/kcp) - :zap: KCP - A Fast and Reliable ARQ Protocol
* [shadowsocks/shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev) - Bug-fix-only libev port of shadowsocks. Future development moved to shadowsocks-rust
* [amnezia-vpn/amnezia-client](https://github.com/amnezia-vpn/amnezia-client) - Amnezia VPN Client (Desktop+Mobile)
* [coturn/coturn](https://github.com/coturn/coturn) - coturn TURN server project
* [FreeRDP/FreeRDP](https://github.com/FreeRDP/FreeRDP) - FreeRDP is a free remote desktop protocol library and clients
* [pymumu/smartdns](https://github.com/pymumu/smartdns) - A local DNS server to obtain the fastest website IP for the best Internet experience, support DoT, DoH, DoQ. 一个本地DNS服务器，获取最快的网站IP，获得最佳上网体验，支持DoH，DoT，DoQ。
* [ithewei/libhv](https://github.com/ithewei/libhv) - 🔥 比libevent/libuv/asio更易用的网络库。A c/c++ network library for developing TCP/UDP/SSL/HTTP/WebSocket/MQTT/Redis client/server.
* [neutrinolabs/xrdp](https://github.com/neutrinolabs/xrdp) - xrdp: an open source RDP server
* [InterceptSuite/ProxyBridge](https://github.com/InterceptSuite/ProxyBridge) - Proxifier Alternative to redirect any Windows/MacOS/Linux TCP and UDP traffic to HTTP/Socks5 proxy
* [jagt/clumsy](https://github.com/jagt/clumsy) - clumsy makes your network condition on Windows significantly worse, but in a controlled and interactive manner.
* [ldcsaa/HP-Socket](https://github.com/ldcsaa/HP-Socket) - High Performance TCP/UDP/HTTP Communication Component
* [cjdelisle/cjdns](https://github.com/cjdelisle/cjdns) - An encrypted IPv6 network using public-key cryptography for address allocation and a distributed hash table for routing.
* [warmcat/libwebsockets](https://github.com/warmcat/libwebsockets) - canonical libwebsockets.org networking library
* [torproject/tor](https://github.com/torproject/tor) - unofficial git repo -- report bugs/issues/pull requests on https://gitlab.torproject.org/ --
* [microsoft/msquic](https://github.com/microsoft/msquic) - Cross-platform, C implementation of the IETF QUIC protocol, exposed to C, C++, C# and Rust.
* [stephane/libmodbus](https://github.com/stephane/libmodbus) - A Modbus library for Linux, Mac OS, FreeBSD and Windows
* [openssh/openssh-portable](https://github.com/openssh/openssh-portable) - Portable OpenSSH
* [apache/guacamole-server](https://github.com/apache/guacamole-server) - The Apache Guacamole proxy daemon (guacd), C API (libguac), and protocol support.
* [meshcore-dev/MeshCore](https://github.com/meshcore-dev/MeshCore) - A new lightweight, hybrid routing mesh protocol for packet radios
* [shadowsocks/ChinaDNS](https://github.com/shadowsocks/ChinaDNS) - Protect yourself against DNS poisoning in China.
* [asterisk/asterisk](https://github.com/asterisk/asterisk) - The official Asterisk Project repository.
* [open62541/open62541](https://github.com/open62541/open62541) - Open source implementation of OPC UA (OPC Unified Architecture) aka IEC 62541 licensed under Mozilla Public License v2.0
* [acl-dev/acl](https://github.com/acl-dev/acl) - C/C++ server and network library, including coroutine,redis client,http/https/websocket,mqtt, mysql/postgresql/sqlite client with C/C++ for Linux, Android, iOS, MacOS, Windows, Harmony,etc..
* [linux-can/can-utils](https://github.com/linux-can/can-utils) - Linux-CAN / SocketCAN user space applications
* [mas-bandwidth/yojimbo](https://github.com/mas-bandwidth/yojimbo) - A network library for client/server games written in C++
* [open5gs/open5gs](https://github.com/open5gs/open5gs) - Open5GS is a C-language Open Source implementation for 5G Core and EPC, i.e. the core network of LTE/NR network (Release-19)
* [linux-rdma/rdma-core](https://github.com/linux-rdma/rdma-core) - RDMA core userspace libraries and daemons
* [c-ares/c-ares](https://github.com/c-ares/c-ares) - A C library for asynchronous DNS requests
* [apple/cups](https://github.com/apple/cups) - Apple CUPS Sources *(archived)*
* [OpenEtherCATsociety/SOEM](https://github.com/OpenEtherCATsociety/SOEM) - Simple Open Source EtherCAT Master
* [CANopenNode/CANopenNode](https://github.com/CANopenNode/CANopenNode) - CANopen protocol stack
* [Lora-net/LoRaMac-node](https://github.com/Lora-net/LoRaMac-node) - Reference implementation and documentation of a LoRa network node.
* [nfc-tools/libnfc](https://github.com/nfc-tools/libnfc) - Platform independent Near Field Communication (NFC) library
* [OpenPrinting/cups](https://github.com/OpenPrinting/cups) - OpenPrinting CUPS Sources
* [openucx/ucx](https://github.com/openucx/ucx) - Unified Communication X (mailing list - https://elist.ornl.gov/mailman/listinfo/ucx-group)
* [pi-hole/FTL](https://github.com/pi-hole/FTL) - The Pi-hole FTL engine
* [miniupnp/miniupnp](https://github.com/miniupnp/miniupnp) - UPnP IGD implementation
* [libssh2/libssh2](https://github.com/libssh2/libssh2) - the SSH library
* [sepfy/libpeer](https://github.com/sepfy/libpeer) - WebRTC Library for IoT/Embedded Device using C
* [espressif/esp-csi](https://github.com/espressif/esp-csi) - Applications based on Wi-Fi CSI (Channel state information), such as indoor positioning, human detection
* [seemoo-lab/owl](https://github.com/seemoo-lab/owl) - An open Apple Wireless Direct Link (AWDL) implementation written in C
* [cisco-system-traffic-generator/trex-core](https://github.com/cisco-system-traffic-generator/trex-core) - trex-core site
* [ngtcp2/ngtcp2](https://github.com/ngtcp2/ngtcp2) - ngtcp2 project is an effort to implement IETF QUIC protocol
* [rxi/dyad](https://github.com/rxi/dyad) - Asynchronous networking for C *(archived)*
* [emqx/neuron](https://github.com/emqx/neuron) - Open source industrial connectivity server
* [zfl9/chinadns-ng](https://github.com/zfl9/chinadns-ng) - chinadns 重构增强版，支持域名分流、ipset/nftset、UDP/TCP/DoT
* [LibVNC/libvncserver](https://github.com/LibVNC/libvncserver) - LibVNCServer/LibVNCClient are cross-platform C libraries that allow you to easily implement VNC server or client functionality in your program.
* [appneta/tcpreplay](https://github.com/appneta/tcpreplay) - Edit and replay captured network traffic at arbitrary speeds — a suite of pcap tools for *NIX and Windows.
* [tass-belgium/picotcp](https://github.com/tass-belgium/picotcp) - PicoTCP is a free TCP/IP stack implementation
* [royhills/arp-scan](https://github.com/royhills/arp-scan) - The ARP Scanner
* [dovecot/core](https://github.com/dovecot/core) - Dovecot mail server
* [bryanpkc/corkscrew](https://github.com/bryanpkc/corkscrew) - A tool for tunneling SSH through HTTP proxies
* [schweikert/fping](https://github.com/schweikert/fping) - High performance ping tool
* [awslabs/amazon-kinesis-video-streams-webrtc-sdk-c](https://github.com/awslabs/amazon-kinesis-video-streams-webrtc-sdk-c) - Amazon Kinesis Video Streams Webrtc SDK is for developers to install and customize realtime communication between devices and enable secure streaming of video, audio to Kinesis Video Streams.
* [opengnb/opengnb](https://github.com/opengnb/opengnb) - GNB is open source de-centralized SDVN to achieve layer3 network via p2p with the ultimate capability of NAT Traversal.GNB是一个开源的去中心化的具有极致内网穿透能力的通过P2P进行三层网络交换的SDVN。
* [troglobit/inadyn](https://github.com/troglobit/inadyn) - In-a-Dyn is a dynamic DNS client with multiple SSL/TLS library support *(archived)*
* [ngtcp2/nghttp3](https://github.com/ngtcp2/nghttp3) - HTTP/3 library written in C
* [zpl-c/enet](https://github.com/zpl-c/enet) - ⚡️ ENet reliable UDP networking library
* [Netis/cloud-probe](https://github.com/Netis/cloud-probe) - A Software Probe for network packet capturing and forwarding in Cloud/Kubernetes and Virtualized environment.
* [liudf0716/apfree-wifidog](https://github.com/liudf0716/apfree-wifidog) - apfree-wifidog is a high-performance captive portal solution that serves as a gateway between your wireless networks and the Internet. Optimized for both HTTP and HTTPS traffic, it ensures secure border control while enabling seamless user authentication and efficient network management. 购买下面的链接中的服务支持我的开源
* [obgm/libcoap](https://github.com/obgm/libcoap) - A CoAP (RFC 7252) implementation in C
* [debevv/nanoMODBUS](https://github.com/debevv/nanoMODBUS) - A compact MODBUS RTU/TCP C library for embedded/microcontrollers
* [nxrighthere/ENet-CSharp](https://github.com/nxrighthere/ENet-CSharp) - Reliable UDP networking library
* [libplctag/libplctag](https://github.com/libplctag/libplctag) - This C library provides a portable and simple API for accessing Allen-Bradley and Modbus PLC data over Ethernet.
* [diegocr/netcat](https://github.com/diegocr/netcat) - NetCat for Windows
* [EIPStackGroup/OpENer](https://github.com/EIPStackGroup/OpENer) - OpENer is an EtherNet/IP stack for I/O adapter devices. It supports multiple I/O and explicit connections and includes objects and services for making EtherNet/IP-compliant products as defined in the ODVA specification.
* [OpenEtherCATsociety/SOES](https://github.com/OpenEtherCATsociety/SOES) - Simple Open Source EtherCAT Slave
* [liudf0716/xfrpc](https://github.com/liudf0716/xfrpc) - xfrpc 是一个轻量级的 FRP 客户端，完美兼容 frps，采用 C 语言实现，专为 OpenWRT 和物联网等资源受限系统优化设计。它针对 ROM 和 RAM 空间有限的设备，提供高效的内网穿透解决方案。xfrpc 集成了xDPI（深度包检测）功能，增强了安全性，有效防止内网穿透中因恶意嗅探导致的安全威胁，确保数据传输和网络访问的可靠保护。购买下面的链接中的服务支持我的开源
* [Exim/exim](https://github.com/Exim/exim) - Exim Mail Transport Agent - source, testsuite and documentation *(archived)*
* [angt/glorytun](https://github.com/angt/glorytun) - Multipath UDP tunnel
* [NMSSH/NMSSH](https://github.com/NMSSH/NMSSH) - NMSSH is an Objective-C wrapper for libssh2, with a sweet API.
* [CongducPham/LowCostLoRaGw](https://github.com/CongducPham/LowCostLoRaGw) - Low-cost LoRa IoT & gateway with SX12XX (SX1261/62/68; SX1272/76/77/78/79; SX1280/81), RaspberryPI and Arduino boards
* [libtrading/libtrading](https://github.com/libtrading/libtrading) - Libtrading, an ultra low-latency trading connectivity library for C and C++.
* [tatsuhiro-t/wslay](https://github.com/tatsuhiro-t/wslay) - The WebSocket library in C
* [dinhvh/libetpan](https://github.com/dinhvh/libetpan) - Mail Framework for C Language
* [tatsuhiro-t/spdylay](https://github.com/tatsuhiro-t/spdylay) - The experimental SPDY protocol version 2, 3 and 3.1 implementation in C
* [ideawu/c1000k](https://github.com/ideawu/c1000k) - A tool to test if your OS supports 1 million connections(c1000k/c1m)
* [liudf0716/apfree_wifidog](https://github.com/liudf0716/apfree_wifidog) - clone from apfree-wifidog *(archived)*

### RPC and Messaging

* [eclipse-paho/paho.mqtt.c](https://github.com/eclipse-paho/paho.mqtt.c) - An Eclipse Paho C client library for MQTT for Windows, Linux and MacOS. API documentation: https://eclipse-paho.github.io/paho.mqtt.c/
* [eclipse-paho/paho.mqtt.embedded-c](https://github.com/eclipse-paho/paho.mqtt.embedded-c) - Paho MQTT C client library for embedded systems. Paho is an Eclipse IoT project (https://iot.eclipse.org/)
* [laruence/yar](https://github.com/laruence/yar) - Light, concurrent RPC framework for PHP & C
* [eclipse-cyclonedds/cyclonedds](https://github.com/eclipse-cyclonedds/cyclonedds) - Eclipse Cyclone DDS project
* [zeromq/czmq](https://github.com/zeromq/czmq) - High-level C binding for ØMQ
* [LiamBindle/MQTT-C](https://github.com/LiamBindle/MQTT-C) - A portable MQTT C client for embedded systems and PCs alike.
* [bus1/dbus-broker](https://github.com/bus1/dbus-broker) - Linux D-Bus Message Broker

### Distributed Systems

* [gluster/glusterfs](https://github.com/gluster/glusterfs) - Gluster Filesystem : Build your distributed storage in minutes
* [acassen/keepalived](https://github.com/acassen/keepalived) - Keepalived
* [stellar/stellar-core](https://github.com/stellar/stellar-core) - Reference implementation for the peer-to-peer agent that manages the Stellar network.
* [ElementsProject/lightning](https://github.com/ElementsProject/lightning) - Core Lightning — Lightning Network implementation focusing on spec compliance and performance
* [luke-jr/bfgminer](https://github.com/luke-jr/bfgminer) - Modular ASIC/FPGA miner written in C, featuring overclocking, monitoring, fan speed control and remote interface capabilities.
* [firedancer-io/firedancer](https://github.com/firedancer-io/firedancer) - Firedancer is Jump Crypto's Solana validator software.
* [corosync/corosync](https://github.com/corosync/corosync) - The Corosync Cluster Engine
* [willemt/raft](https://github.com/willemt/raft) - C implementation of the Raft Consensus protocol, BSD licensed
* [TrueBlocks/trueblocks-core](https://github.com/TrueBlocks/trueblocks-core) - The main repository for the TrueBlocks system
* [jgarzik/cpuminer](https://github.com/jgarzik/cpuminer) - CPU miner for bitcoin *(archived)*
* [sheepdog/sheepdog](https://github.com/sheepdog/sheepdog) - Distributed Storage System for QEMU
* [RJ/ketama](https://github.com/RJ/ketama) - C library for consistent hashing, and langauge bindings
* [canonical/raft](https://github.com/canonical/raft) - Unmaintained C implementation of the Raft consensus protocol *(archived)*
* [JayDDee/cpuminer-opt](https://github.com/JayDDee/cpuminer-opt) - Optimized multi algo CPU miner
* [oleganza/CoreBitcoin](https://github.com/oleganza/CoreBitcoin) - Awesome Bitcoin toolkit for ObjC and Swift
* [cbuchner1/CudaMiner](https://github.com/cbuchner1/CudaMiner) - a CUDA accelerated litecoin mining application based on pooler's CPU miner
* [lucasjones/cpuminer-multi](https://github.com/lucasjones/cpuminer-multi) - Multi-algo CPUMiner & Reference Cryptonote Miner (JSON-RPC 2.0)

### Cloud and Infrastructure

* [krallin/tini](https://github.com/krallin/tini) - A tiny but valid `init` for containers
* [lxc/lxc](https://github.com/lxc/lxc) - LXC - Linux Containers
* [containers/crun](https://github.com/containers/crun) - A fast and lightweight fully featured OCI runtime and C library for running containers
* [lucavallin/barco](https://github.com/lucavallin/barco) - Linux containers from scratch in C.
* [lxc/lxcfs](https://github.com/lxc/lxcfs) - FUSE filesystem for LXC
* [NVIDIA/libnvidia-container](https://github.com/NVIDIA/libnvidia-container) - NVIDIA container runtime library
* [aws/aws-iot-device-sdk-embedded-C](https://github.com/aws/aws-iot-device-sdk-embedded-C) - SDK for connecting to AWS IoT from a device using embedded C.
* [cbsd/cbsd](https://github.com/cbsd/cbsd) - Yet one more wrapper around jail, bhyve, QEMU and XEN

### Monitoring and Observability

* [allinurl/goaccess](https://github.com/allinurl/goaccess) - GoAccess is a real-time web log analyzer and interactive viewer that runs in a terminal in *nix systems or through your browser.
* [fluent/fluent-bit](https://github.com/fluent/fluent-bit) - Fast and Lightweight Logs, Metrics and Traces processor for Linux, BSD, OSX and Windows
* [arkime/arkime](https://github.com/arkime/arkime) - Arkime is an open source, large scale, full packet capturing, indexing, and database system.
* [vozlt/nginx-module-vts](https://github.com/vozlt/nginx-module-vts) - Nginx virtual host traffic status module
* [sysstat/sysstat](https://github.com/sysstat/sysstat) - Performance monitoring tools for Linux
* [collectd/collectd](https://github.com/collectd/collectd) - The system statistics collection daemon. Please send Pull Requests here!
* [groundcover-com/caretta](https://github.com/groundcover-com/caretta) - Instant K8s service dependency map, right to your Grafana.
* [statsite/statsite](https://github.com/statsite/statsite) - C implementation of statsd
* [vergoh/vnstat](https://github.com/vergoh/vnstat) - vnStat - a network traffic monitor for Linux and BSD
* [monitoringartist/zabbix-docker-monitoring](https://github.com/monitoringartist/zabbix-docker-monitoring) - :whale: Docker/Kubernetes/Mesos/Marathon/Chronos/LXC/LXD/Swarm container monitoring - Docker image, Zabbix template and C module

## User Interface

### GUI Toolkits

* [lvgl/lvgl](https://github.com/lvgl/lvgl) - LVGL is a free, full-featured embedded UI library for devices from small MCUs to 3D-capable MPUs, enhanced by LVGL Pro, a professional editor and tooling.
* [nicbarker/clay](https://github.com/nicbarker/clay) - High performance UI layout library in C.
* [webview/webview](https://github.com/webview/webview) - Tiny cross-platform webview library for C/C++. Uses WebKit (GTK/Cocoa) and Edge WebView2 (Windows).
* [vurtun/nuklear](https://github.com/vurtun/nuklear) - A single-header ANSI C gui library *(archived)*
* [Immediate-Mode-UI/Nuklear](https://github.com/Immediate-Mode-UI/Nuklear) - A single-header ANSI C immediate mode cross-platform GUI library
* [andlabs/libui](https://github.com/andlabs/libui) - Simple and portable (but not inflexible) GUI library in C that uses the native GUI technologies of each platform it supports.
* [raysan5/raygui](https://github.com/raysan5/raygui) - A simple and easy-to-use immediate-mode gui library
* [lc-soft/LCUI](https://github.com/lc-soft/LCUI) - C library for building user interfaces
* [cycfi/elements](https://github.com/cycfi/elements) - Elements C++ GUI library
* [AstraThreshold/oled-ui-astra](https://github.com/AstraThreshold/oled-ui-astra) - A smooth, easy-to-deploy, and easy-to-extend OLED UI framework, based on C++.
* [sudoevolve/EUI-NEO](https://github.com/sudoevolve/EUI-NEO) - EUI-NEO is a cross-platform, high-performance, low-overhead C++17 GPUI framework
* [golang-ui/nuklear](https://github.com/golang-ui/nuklear) - This project provides Go bindings for nuklear.h — a small ANSI C GUI library.
* [juliettef/IconFontCppHeaders](https://github.com/juliettef/IconFontCppHeaders) - C and C++ headers, C# and Python classes, Rust files and Go package for icon fonts Font Awesome, Fork Awesome, Google Material Design icons and symbols, Pictogrammers Material Design icons, Kenney game icons, Fontaudio, Codicons and Lucide.
* [ImpulseAdventure/GUIslice](https://github.com/ImpulseAdventure/GUIslice) - GUIslice drag & drop embedded GUI in C for touchscreen TFT on Arduino, Raspberry Pi, ARM, ESP8266 / ESP32 / M5stack using Adafruit-GFX / TFT_eSPI / UTFT / SDL
* [ocornut/imgui_club](https://github.com/ocornut/imgui_club) - Small extensions for Dear ImGui
* [randrew/layout](https://github.com/randrew/layout) - Single-file library for calculating 2D UI layouts using stacking boxes. Compiles as C99 or C++.
* [cztomczak/cef2go](https://github.com/cztomczak/cef2go) - Go lang bindings for the Chromium Embedded Framework (CEF)
* [libui-ng/libui-ng](https://github.com/libui-ng/libui-ng) - libui-ng: a portable GUI library for C. "libui for the next generation"
* [ghaerr/microwindows](https://github.com/ghaerr/microwindows) - The Nano-X Window System
* [wengkai/ACLLib](https://github.com/wengkai/ACLLib) - ACLLib is a bunch of C functions covers Win32API and provides simpler API to beginners for programming Windows GUI applications. It compiles with MinGW and MS Visual Studio Express

### Applications and End User Tools

* [Genymobile/scrcpy](https://github.com/Genymobile/scrcpy) - Display and control your Android device
* [obsproject/obs-studio](https://github.com/obsproject/obs-studio) - OBS Studio - Free and open source software for live streaming and screen recording
* [pbatard/rufus](https://github.com/pbatard/rufus) - The Reliable USB Formatting Utility
* [mpv-player/mpv](https://github.com/mpv-player/mpv) - 🎥 Command line media player
* [xiaojieonly/Ehviewer_CN_SXJ](https://github.com/xiaojieonly/Ehviewer_CN_SXJ) - ehviewer，用爱发电，快乐前行
* [jarun/nnn](https://github.com/jarun/nnn) - n³ The unorthodox terminal file manager
* [videolan/vlc](https://github.com/videolan/vlc) - VLC media player - plays everything, runs anywhere. Code here: https://code.videolan.org/videolan/vlc
* [sumatrapdfreader/sumatrapdf](https://github.com/sumatrapdfreader/sumatrapdf) - SumatraPDF reader
* [davatorium/rofi](https://github.com/davatorium/rofi) - Rofi: A window switcher, application launcher and dmenu replacement
* [winsiderss/systeminformer](https://github.com/winsiderss/systeminformer) - A free, powerful, multi-purpose tool that helps you monitor system resources, debug software and detect malware. Brought to you by Winsider Seminars & Solutions, Inc. @ https://windows-internals.com
* [cockpit-project/cockpit](https://github.com/cockpit-project/cockpit) - Cockpit is a web-based graphical interface for servers.
* [BasedHardware/omi](https://github.com/BasedHardware/omi) - AI that sees your screen, listens to your conversations and tells you what to do
* [jonas/tig](https://github.com/jonas/tig) - Text-mode interface for git
* [Wind4/vlmcsd](https://github.com/Wind4/vlmcsd) - KMS Emulator in C (currently runs on Linux including Android, FreeBSD, Solaris, Minix, Mac OS, iOS, Windows with or without Cygwin) *(archived)*
* [htop-dev/htop](https://github.com/htop-dev/htop) - htop - an interactive process viewer
* [karlstav/cava](https://github.com/karlstav/cava) - Cross-platform Audio Visualizer
* [cmus/cmus](https://github.com/cmus/cmus) - Small, fast and powerful console music player for Unix-like operating systems.
* [rvaiya/keyd](https://github.com/rvaiya/keyd) - A key remapping daemon for linux.
* [hishamhm/htop](https://github.com/hishamhm/htop) - htop is an interactive text-mode process viewer for Unix systems. It aims to be a better 'top'. *(archived)*
* [linuxmint/cinnamon](https://github.com/linuxmint/cinnamon) - A Linux desktop featuring a traditional layout, built from modern technology and introducing brand new innovative features.
* [dunst-project/dunst](https://github.com/dunst-project/dunst) - Lightweight and customizable notification daemon
* [abishekvashok/cmatrix](https://github.com/abishekvashok/cmatrix) - Terminal based "The Matrix" like implementation
* [vladelaina/Catime](https://github.com/vladelaina/Catime) - 💌A tiny (995KB) but mighty timer in **pure C** ! — almost no memory usage!❤️‍🔥 Supports clock, countdown, stopwatch, Pomodoro, and fully customizable tray animations (GIFs, CPU/Mem%) 💘 Don't be shy, join here🧸: https://discord.com/invite/W3tW2gtp6g
* [martanne/vis](https://github.com/martanne/vis) - A vi-like editor based on Plan 9's structural regular expressions
* [philippe44/AirConnect](https://github.com/philippe44/AirConnect) - Use AirPlay to stream to UPnP/Sonos & Chromecast devices
* [fwupd/fwupd](https://github.com/fwupd/fwupd) - A system daemon to allow session software to update firmware
* [Cateners/tiny_container](https://github.com/Cateners/tiny_container) - Click-to-run debian 13 with desktop environment on android!
* [neomutt/neomutt](https://github.com/neomutt/neomutt) - ✉️ Teaching an Old Dog New Tricks -- IRC: #neomutt on irc.libera.chat
* [rvaiya/warpd](https://github.com/rvaiya/warpd) - A modal keyboard-driven virtual pointer
* [tvheadend/tvheadend](https://github.com/tvheadend/tvheadend) - Tvheadend is the leading TV streaming server for Linux with ATSC, DVB-C/C2, DVB-S/S2, DVB-T/T2, IPTV, SAT>IP and unix pipe input sources
* [weechat/weechat](https://github.com/weechat/weechat) - The extensible chat client.
* [vifm/vifm](https://github.com/vifm/vifm) - Vifm is a file manager with curses interface, which provides Vim-like environment for managing objects within file systems, extended with some useful ideas from mutt.
* [hexchat/hexchat](https://github.com/hexchat/hexchat) - GTK+ IRC client *(archived)*
* [siduck/chadwm](https://github.com/siduck/chadwm) - Making dwm as beautiful as possible!
* [streetpea/chiaki-ng](https://github.com/streetpea/chiaki-ng) - Next-Generation of Chiaki (the open-source remote play client for PlayStation)
* [TheTumultuousUnicornOfDarkness/CPU-X](https://github.com/TheTumultuousUnicornOfDarkness/CPU-X) - CPU-X is a Free software that gathers information on CPU, motherboard and more
* [MidnightCommander/mc-old](https://github.com/MidnightCommander/mc-old) - Midnight Commander's repository *(archived)*
* [MayaPosch/NymphCast](https://github.com/MayaPosch/NymphCast) - Audio and video casting system with support for custom applications.
* [owntone/owntone-server](https://github.com/owntone/owntone-server) - Audio server that can play to AirPlay 1+2 speakers (multiroom), Chromecast and locally. Supports Spotify, internet radio and many file formats. Also MPD server, iTunes DAAP, smart playlists, Apple Remote and much more.
* [wlrfx/swayfx](https://github.com/wlrfx/swayfx) - SwayFX: Sway, but with eye candy!
* [chjj/compton](https://github.com/chjj/compton) - A compositor for X11.
* [cyring/CoreFreq](https://github.com/cyring/CoreFreq) - CoreFreq : CPU monitoring and tuning software designed for the 64-bit processors.
* [way-cooler/way-cooler](https://github.com/way-cooler/way-cooler) - Wayland compositor for AwesomeWM *(archived)*
* [cage-kiosk/cage](https://github.com/cage-kiosk/cage) - A Wayland kiosk
* [da-luce/astroterm](https://github.com/da-luce/astroterm) - A planetarium for your terminal! Explore stars, planets, constellations, and more, all rendered right in the command line—no telescope required. ✨🪐
* [DeaDBeeF-Player/deadbeef](https://github.com/DeaDBeeF-Player/deadbeef) - DeaDBeeF Player
* [libimobiledevice/idevicerestore](https://github.com/libimobiledevice/idevicerestore) - Restore/upgrade firmware of iOS devices
* [Sapd/HeadsetControl](https://github.com/Sapd/HeadsetControl) - Sidetone and Battery status for Logitech G930, G533, G633, G933 SteelSeries Arctis 7/PRO 2019 and Corsair VOID (Pro) in Linux and MacOSX
* [abb128/LiveCaptions](https://github.com/abb128/LiveCaptions) - Linux Desktop application that provides live captioning
* [PromyLOPh/pianobar](https://github.com/PromyLOPh/pianobar) - Repository moved to codeberg.org, see below. *(archived)*
* [leo-arch/clifm](https://github.com/leo-arch/clifm) - 💾 The shell-like, command-line terminal file manager
* [profanity-im/profanity](https://github.com/profanity-im/profanity) - Ncurses based XMPP client
* [gsass1/NTop](https://github.com/gsass1/NTop) - 💻 htop-like system-monitor for Windows with Vi-keybindings.
* [OpenCPN/OpenCPN](https://github.com/OpenCPN/OpenCPN) - A concise ChartPlotter/Navigator. A cross-platform ship-borne GUI application supporting * GPS/GPDS Postition Input * BSB Raster Chart Display * S57 Vector ENChart Display * AIS Input Decoding * Waypoint Autopilot Navigation
* [celluloid-player/celluloid](https://github.com/celluloid-player/celluloid) - A simple GTK+ frontend for mpv
* [libimobiledevice/ideviceinstaller](https://github.com/libimobiledevice/ideviceinstaller) - Manage apps of iOS devices
* [philj56/tofi](https://github.com/philj56/tofi) - Tiny dynamic menu for Wayland
* [mjakeman/extension-manager](https://github.com/mjakeman/extension-manager) - A utility for browsing and installing GNOME Shell Extensions.
* [lfos/calcurse](https://github.com/lfos/calcurse) - A text-based calendar and scheduling application
* [cdown/clipmenu](https://github.com/cdown/clipmenu) - Clipboard management using dmenu
* [deadpixi/mtm](https://github.com/deadpixi/mtm) - Perhaps the smallest useful terminal multiplexer in the world.
* [svenstaro/rofi-calc](https://github.com/svenstaro/rofi-calc) - 🖩 Do live calculations in rofi!
* [dev47apps/droidcam-linux-client](https://github.com/dev47apps/droidcam-linux-client) - GNU/Linux/nix client for DroidCam
* [nurupo/vlc-pause-click-plugin](https://github.com/nurupo/vlc-pause-click-plugin) - Plugin for VLC that pauses/plays video on mouse click
* [csete/gpredict](https://github.com/csete/gpredict) - Gpredict satellite tracking application
* [susam/uncap](https://github.com/susam/uncap) - Map Caps Lock to Escape or any key to any key
* [kkkgo/vlmcsd](https://github.com/kkkgo/vlmcsd) - 🔑Portable open-source KMS Emulator in C
* [xorg62/tty-clock](https://github.com/xorg62/tty-clock) - Clock using lib ncurses
* [GameTec-live/ChameleonUltraGUI](https://github.com/GameTec-live/ChameleonUltraGUI) - A GUI for the Chameleon Ultra written in Flutter for crossplatform
* [8bitbubsy/ft2-clone](https://github.com/8bitbubsy/ft2-clone) - Fasttracker 2 clone for Windows/macOS/Linux
* [ghostty-org/ghostling](https://github.com/ghostty-org/ghostling) - A minimum viable terminal emulator built on top of the libghostty C API. Ex minimo, infinita nascuntur. 👻🐣
* [uTox/uTox](https://github.com/uTox/uTox) - µTox the lightest and fluffiest Tox client
* [valinet/Win11DisableRoundedCorners](https://github.com/valinet/Win11DisableRoundedCorners) - A simple utility that cold patches dwm (uDWM.dll) in order to disable window rounded corners in Windows 11
* [JLErvin/berry](https://github.com/JLErvin/berry) - :strawberry: A healthy, byte-sized window manager
* [henrypp/chrlauncher](https://github.com/henrypp/chrlauncher) - Small and very fast portable launcher and updater for Chromium.
* [losnoco/Cog](https://github.com/losnoco/Cog) - Cog - A Free and Open Source Audio Player for macOS 10.15+
* [Rafostar/clapper](https://github.com/Rafostar/clapper) - Level up your video experience with a modern and user-friendly media player.
* [jgmenu/jgmenu](https://github.com/jgmenu/jgmenu) - An X11 menu
* [ubisoft/Chroma](https://github.com/ubisoft/Chroma) - Chroma (developed by Ubisoft) is a one-stop solution for detecting color blindness-related issues in games. It replicates Protanopia, Deuteranopia, and Tritanopia filters over the game screen, helping users flag accessibility concerns in real-time.
* [adsr/mle](https://github.com/adsr/mle) - flexible terminal-based text editor (C)
* [Keruspe/GPaste](https://github.com/Keruspe/GPaste) - Clipboard management system
* [Majjcom/ncmppGui](https://github.com/Majjcom/ncmppGui) - 一个使用C++编写的极速ncm转换GUI工具
* [Seagate/openSeaChest](https://github.com/Seagate/openSeaChest) - Cross platform utilities useful for configuring features and assessing health on SATA, SAS, NVMe, and USB storage devices.
* [nsxiv/nsxiv](https://github.com/nsxiv/nsxiv) - Read-only mirror of Neo Simple X Image Viewer
* [lpereira/hardinfo](https://github.com/lpereira/hardinfo) - System profiler and benchmark tool for Linux systems
* [moonlight-stream/moonlight-chrome](https://github.com/moonlight-stream/moonlight-chrome) - GameStream client for ChromeOS *(archived)*
* [FedeDP/Clight](https://github.com/FedeDP/Clight) - A C daemon that turns your webcam into a light sensor. It will adjust screen backlight based on ambient brightness.
* [jergusg/k380-function-keys-conf](https://github.com/jergusg/k380-function-keys-conf) - Make function keys default on Logitech k380 bluetooth keyboard
* [wroberts/rogauracore](https://github.com/wroberts/rogauracore) - RGB keyboard control for Asus ROG laptops
* [wmutils/core](https://github.com/wmutils/core) - Set of window manipulation tools
* [hyperkineticnerd/OpenCorsairLink](https://github.com/hyperkineticnerd/OpenCorsairLink) - Linux and Mac OS support for the CorsairLink Devices
* [CristianHenzel/ClipIt](https://github.com/CristianHenzel/ClipIt) - ClipIt clipboard manager for GTK+
* [HarveyHunt/howm](https://github.com/HarveyHunt/howm) - A lightweight, X11 tiling window manager that behaves like vim
* [bitlbee/bitlbee](https://github.com/bitlbee/bitlbee) - An IRC to other chat networks gateway :bee:

## Graphics and Media

### Graphics and Rendering

* [glfw/glfw](https://github.com/glfw/glfw) - A multi-platform library for OpenGL, OpenGL ES, Vulkan, window and input
* [floooh/sokol](https://github.com/floooh/sokol) - minimal cross-platform standalone C headers
* [Dav1dde/glad](https://github.com/Dav1dde/glad) - Multi-Language Vulkan/GL/GLES/EGL/GLX/WGL Loader-Generator based on the official specs.
* [MrForExample/ComfyUI-3D-Pack](https://github.com/MrForExample/ComfyUI-3D-Pack) - An extensive node suite that enables ComfyUI to process 3D inputs (Mesh & UV Texture, etc) using cutting edge algorithms (3DGS, NeRF, etc.)
* [MrNeRF/LichtFeld-Studio](https://github.com/MrNeRF/LichtFeld-Studio) - Train, inspect, edit, automate, and export 3D Gaussian Splatting scenes from a single native application.
* [nigels-com/glew](https://github.com/nigels-com/glew) - The OpenGL Extension Wrangler Library
* [zauonlok/renderer](https://github.com/zauonlok/renderer) - A shader-based software renderer written from scratch in C89
* [tsoding/olive.c](https://github.com/tsoding/olive.c) - Simple 2D Graphics Library for C
* [skywind3000/mini3d](https://github.com/skywind3000/mini3d) - 3D Software Renderer in 700 Lines !!
* [jkuhlmann/cgltf](https://github.com/jkuhlmann/cgltf) - :diamond_shape_with_a_dot_inside: Single-file glTF 2.0 loader and writer written in C99
* [letoram/arcan](https://github.com/letoram/arcan) - The owls are not what they seem.
* [pelicanmapping/osgearth](https://github.com/pelicanmapping/osgearth) - 3D Maps & Terrain SDK (C++)
* [rougier/freetype-gl](https://github.com/rougier/freetype-gl) - OpenGL text using one vertex buffer, one texture and FreeType
* [ands/lightmapper](https://github.com/ands/lightmapper) - A C/C++ single-file library for drop-in lightmap baking. Just use your existing OpenGL renderer to bounce light!
* [ufbx/ufbx](https://github.com/ufbx/ufbx) - Single source file FBX loader
* [dariomanesku/cmftStudio](https://github.com/dariomanesku/cmftStudio) - cmftStudio - GUI counterpart for:
* [rswinkle/PortableGL](https://github.com/rswinkle/PortableGL) - An implementation of OpenGL 3.x-ish in clean C
* [grimfang4/sdl-gpu](https://github.com/grimfang4/sdl-gpu) - A library for high-performance, modern 2D graphics with SDL written in C.
* [sammycage/lunasvg](https://github.com/sammycage/lunasvg) - SVG rendering and manipulation library in C++
* [libretro/common-shaders](https://github.com/libretro/common-shaders) - Collection of commonly used Cg shaders. These shaders are usable by either HLSL and/or Cg runtime compilers. The cg2glsl script will translate most of these into GLSL shaders.
* [prideout/par](https://github.com/prideout/par) - single-file C libraries from Philip Allan Rideout
* [KhronosGroup/SPIRV-Reflect](https://github.com/KhronosGroup/SPIRV-Reflect) - SPIRV-Reflect is a lightweight library that provides a C/C++ reflection API for SPIR-V shader bytecode in Vulkan applications.
* [dariomanesku/cmft](https://github.com/dariomanesku/cmft) - Cross-platform open-source command-line cubemap filtering tool.
* [vkoskiv/c-ray](https://github.com/vkoskiv/c-ray) - c-ray is a small, simple path tracer written in C
* [datoviz/datoviz](https://github.com/datoviz/datoviz) - ⚡ Datoviz: high-performance GPU rendering for scientific data visualization
* [tcbrindle/raytracer.hpp](https://github.com/tcbrindle/raytracer.hpp) - Simple compile-time raytracer using C++17

### Game Development

* [raysan5/raylib](https://github.com/raysan5/raylib) - A simple and easy-to-use library to enjoy videogames programming
* [libretro/RetroArch](https://github.com/libretro/RetroArch) - Cross-platform, sophisticated frontend for the libretro API. Licensed GPLv3.
* [fogleman/Craft](https://github.com/fogleman/Craft) - A simple Minecraft clone written in C using modern OpenGL (shaders).
* [pygame/pygame](https://github.com/pygame/pygame) - 🐍🎮 pygame (the library) is a Free and Open Source python programming language library for making multimedia applications like games built on top of the excellent SDL library. C, Python, Native, OpenGL.
* [SanderMertens/flecs](https://github.com/SanderMertens/flecs) - A fast entity component system (ECS) for C & C++
* [RandyGaul/cute_headers](https://github.com/RandyGaul/cute_headers) - Collection of cross-platform one-file C/C++ libraries with no dependencies, primarily used for games
* [maximegmd/CyberEngineTweaks](https://github.com/maximegmd/CyberEngineTweaks) - Cyberpunk 2077 tweaks, hacks and scripting framework
* [NetHack/NetHack](https://github.com/NetHack/NetHack) - Official NetHack Git Repository
* [amzeratul/halley](https://github.com/amzeratul/halley) - A lightweight game engine written in modern C++
* [matrixcascade/PainterEngine](https://github.com/matrixcascade/PainterEngine) - PainterEngine is a application/game engine with software renderer,PainterEngine can be transplanted to any platform that supports C
* [eduard-permyakov/permafrost-engine](https://github.com/eduard-permyakov/permafrost-engine) - An OpenGL RTS game engine written in C
* [TASEmulators/BizHawk](https://github.com/TASEmulators/BizHawk) - BizHawk is a multi-system emulator written in C#. BizHawk provides nice features for casual gamers such as full screen, and joypad support in addition to full rerecording and debugging tools for all system cores.
* [crownengine/crown](https://github.com/crownengine/crown) - A complete and cross-platform game engine designed for flexibility, performance and fast iteration.
* [VadimBoev/FlappyBird](https://github.com/VadimBoev/FlappyBird) - Less than 100 Kilobytes. Works for Android 5.0 and above
* [chocolate-doom/chocolate-doom](https://github.com/chocolate-doom/chocolate-doom) - Chocolate Doom is a Doom source port that is minimalist and historically accurate.
* [slembcke/Chipmunk2D](https://github.com/slembcke/Chipmunk2D) - A fast and lightweight 2D game physics library.
* [gbdk-2020/gbdk-2020](https://github.com/gbdk-2020/gbdk-2020) - An updated version of GBDK, C compiler, assembler, linker and set of libraries for the Nintendo Gameboy, Nintendo Entertainment System, Sega Master System, Sega Game Gear.
* [LIJI32/SameBoy](https://github.com/LIJI32/SameBoy) - Game Boy and Game Boy Color emulator written in C
* [Stephane-D/SGDK](https://github.com/Stephane-D/SGDK) - SGDK - A free and open development kit for the Sega Mega Drive
* [yujqiao/DungeonRush](https://github.com/yujqiao/DungeonRush) - 👾🐍 A opensource game inspired by Snake, written in pure C with SDL
* [liballeg/allegro5](https://github.com/liballeg/allegro5) - The official Allegro 5 git repository. Pull requests welcome!
* [ClassiCube/ClassiCube](https://github.com/ClassiCube/ClassiCube) - Custom Minecraft Classic / ClassiCube client written in C from scratch (formerly ClassicalSharp in C#)
* [orangeduck/Corange](https://github.com/orangeduck/Corange) - Pure C Game Engine
* [sdlpal/sdlpal](https://github.com/sdlpal/sdlpal) - SDL-based reimplementation of the classic Chinese-language RPG known as PAL.
* [mgerdes/Open-Golf](https://github.com/mgerdes/Open-Golf) - A cross-platform minigolf game written in C.
* [pygame-community/pygame-ce](https://github.com/pygame-community/pygame-ce) - 🐍🎮 pygame - Community Edition is a FOSS Python library for multimedia applications (like games). Built on top of the excellent SDL library.
* [taisei-project/taisei](https://github.com/taisei-project/taisei) - A free and open-source Touhou Project fangame
* [pret/pokefirered](https://github.com/pret/pokefirered) - Decompilation of Pokémon FireRed/LeafGreen
* [mupen64plus/mupen64plus-core](https://github.com/mupen64plus/mupen64plus-core) - Core module of the Mupen64Plus project
* [angband/angband](https://github.com/angband/angband) - A free, single-player roguelike dungeon exploration game
* [zpl-c/librg](https://github.com/zpl-c/librg) - 🚀 Making multi-player gamedev simpler since 2017
* [travisvroman/kohi](https://github.com/travisvroman/kohi) - A game engine made as part of the Kohi Game Engine series on YouTube (and Twitch!), where we make a game engine from the ground up using C and Vulkan.
* [switchbrew/libnx](https://github.com/switchbrew/libnx) - Library for Switch Homebrew
* [tmewett/BrogueCE](https://github.com/tmewett/BrogueCE) - Brogue: Community Edition - a community-lead fork of the much-loved minimalist roguelike game
* [tsherif/space-shooter.c](https://github.com/tsherif/space-shooter.c) - A cross-platform, top-down 2D space shooter written in C using only platform libraries.
* [coop-deluxe/sm64coopdx](https://github.com/coop-deluxe/sm64coopdx) - An official continuation of https://github.com/djoslin0/sm64ex-coop on sm64coopdx for the enhancements and progress it already has.
* [CE-Programming/CEmu](https://github.com/CE-Programming/CEmu) - Third-party TI-84 Plus CE / TI-83 Premium CE emulator, focused on developer features
* [scottcgi/Mojoc](https://github.com/scottcgi/Mojoc) - A cross-platform, open-source, pure C game engine for mobile game.
* [floooh/chips](https://github.com/floooh/chips) - 8-bit chip and system emulators in standalone C headers
* [dethrace-labs/dethrace](https://github.com/dethrace-labs/dethrace) - Reverse engineering the 1997 game "Carmageddon"
* [phoboslab/high_impact](https://github.com/phoboslab/high_impact) - A 2d game engine written in C
* [alekmaul/pvsneslib](https://github.com/alekmaul/pvsneslib) - PVSnesLib : A small, open and free development kit for the Nintendo SNES
* [cxong/cdogs-sdl](https://github.com/cxong/cdogs-sdl) - Classic overhead run-and-gun game
* [HerculesWS/Hercules](https://github.com/HerculesWS/Hercules) - Hercules is a collaborative software development project revolving around the creation of a robust massively multiplayer online role playing game (MMORPG) server package. Written in C, the program is very versatile and provides NPCs, warps and modifications. The project is jointly managed by a group of volunteers located around the world as well as a tremendous community providing QA and support. Hercules is a continuation of the original Athena project.
* [RandyGaul/qu3e](https://github.com/RandyGaul/qu3e) - Lightweight and Simple 3D Open Source Physics Engine in C++ *(archived)*
* [pret/pokeruby](https://github.com/pret/pokeruby) - Decompilation of Pokémon Ruby/Sapphire
* [Cubitect/cubiomes](https://github.com/Cubitect/cubiomes) - C library that mimics the Minecraft biome generation.
* [naev/naev](https://github.com/naev/naev) - Naev has moved to codeberg! This is just a mirror.
* [Gigoteur/UnicornConsole](https://github.com/Gigoteur/UnicornConsole) - Unicorn Console: create quick fantasy game in Rust/Python/Lua/Rhai/Wasm !
* [Interrupt/systemshock](https://github.com/Interrupt/systemshock) - Shockolate - A minimalist and cross platform System Shock source port.
* [kroitor/gjk.c](https://github.com/kroitor/gjk.c) - Gilbert-Johnson-Keerthi (GJK) collision detection algorithm in 200 lines of clean plain C
* [wojciech-graj/doom-ascii](https://github.com/wojciech-graj/doom-ascii) - DooM in the terminal!
* [n64dev/cen64](https://github.com/n64dev/cen64) - Cycle-Accurate Nintendo 64 Emulator
* [RandyGaul/cute_framework](https://github.com/RandyGaul/cute_framework) - The *cutest* framework out there for creating 2D and 3D games in C++!
* [punesemu/puNES](https://github.com/punesemu/puNES) - Qt-based Nintendo Entertaiment System emulator and NSF/NSF2/NSFe Music Player (Linux, FreeBSD, OpenBSD and Windows)
* [loadzero/si78c](https://github.com/loadzero/si78c) - si78c is a memory accurate reimplementation of Space Invaders in C.
* [binji/smolnes](https://github.com/binji/smolnes) - NES emulator in <5000 bytes of C
* [septag/rizz](https://github.com/septag/rizz) - Small C game development framework *(archived)*
* [nepx/halfix](https://github.com/nepx/halfix) - x86 PC emulator that runs both natively and in the browser, via WebAssembly
* [bradharding/doomretro](https://github.com/bradharding/doomretro) - The classic, refined DOOM source port. For Windows PC.
* [fabiensanglard/chocolate_duke3D](https://github.com/fabiensanglard/chocolate_duke3D) - chocolate Duke Nukem,3D *(archived)*
* [MarilynDafa/Bulllord-Engine](https://github.com/MarilynDafa/Bulllord-Engine) - lightspeed lightweight elegant game engine in pure c

### Audio

* [mackron/miniaudio](https://github.com/mackron/miniaudio) - Audio playback and capture library written in C, in a single source file.
* [xiph/rnnoise](https://github.com/xiph/rnnoise) - Recurrent neural network for audio noise reduction
* [aubio/aubio](https://github.com/aubio/aubio) - a library for audio and music analysis
* [xiph/opus](https://github.com/xiph/opus) - Modern audio compression for the internet.
* [zrythm/zrythm](https://github.com/zrythm/zrythm) - a highly automated and intuitive digital audio workstation - official mirror
* [xiph/flac](https://github.com/xiph/flac) - Free Lossless Audio Codec
* [iPlug2/iPlug2](https://github.com/iPlug2/iPlug2) - C++ Audio Plug-in Framework for desktop, mobile, xr and web
* [free-audio/clap](https://github.com/free-audio/clap) - Audio Plugin API
* [vgmstream/vgmstream](https://github.com/vgmstream/vgmstream) - vgmstream - A library for playback of various streamed audio formats used in video games.
* [jarikomppa/soloud](https://github.com/jarikomppa/soloud) - Free, easy, portable audio engine for games
* [PortAudio/portaudio](https://github.com/PortAudio/portaudio) - PortAudio is a cross-platform, open-source C language library for real-time audio input and output.
* [andrewrk/libsoundio](https://github.com/andrewrk/libsoundio) - C library for cross-platform real-time audio input and output
* [mackron/dr_libs](https://github.com/mackron/dr_libs) - Audio decoding libraries for C/C++, each in a single source file.
* [libsndfile/libsndfile](https://github.com/libsndfile/libsndfile) - A C library for reading and writing sound files containing sampled audio data.
* [csound/csound](https://github.com/csound/csound) - Main repository for Csound
* [belangeo/pyo](https://github.com/belangeo/pyo) - Python DSP module
* [olilarkin/wdl-ol](https://github.com/olilarkin/wdl-ol) - Enhanced version of Cockos' iPlug - A simple-to-use C++ framework for developing cross platform audio plugins and targeting multiple plugin APIs with the same code. VST / VST3 / Audiounit / RTAS / AAX (Native) formats supported. NOTE: THIS IS OBSOLETE, PLEASE SEE IPLUG2: *(archived)*
* [james34602/JamesDSPManager](https://github.com/james34602/JamesDSPManager) - Audio DSP effects build on Android system framework layer. This is a repository contains a pack of high quality DSP algorithms specialized for audio processing.
* [schellingb/TinySoundFont](https://github.com/schellingb/TinySoundFont) - SoundFont2 synthesizer library in a single C/C++ file
* [cnlohr/colorchord](https://github.com/cnlohr/colorchord) - Chromatic Sound to Light Conversion System
* [i-rinat/apulse](https://github.com/i-rinat/apulse) - PulseAudio emulation for ALSA

### Image and Video

* [FFmpeg/FFmpeg](https://github.com/FFmpeg/FFmpeg) - Mirror of https://git.ffmpeg.org/ffmpeg.git
* [libvips/libvips](https://github.com/libvips/libvips) - A fast image processing library with low memory needs.
* [kornelski/pngquant](https://github.com/kornelski/pngquant) - Lossy PNG compressor — pngquant command based on libimagequant library
* [mltframework/mlt](https://github.com/mltframework/mlt) - MLT Multimedia Framework
* [AravisProject/aravis](https://github.com/AravisProject/aravis) - A vision library for genicam based cameras
* [libass/libass](https://github.com/libass/libass) - libass is a portable subtitle renderer for the ASS/SSA (Advanced Substation Alpha/Substation Alpha) subtitle format.
* [uclouvain/openjpeg](https://github.com/uclouvain/openjpeg) - Official repository of the OpenJPEG project
* [alessandrofrancesconi/gimp-plugin-bimp](https://github.com/alessandrofrancesconi/gimp-plugin-bimp) - BIMP. Batch Image Manipulation Plugin for GIMP.
* [richgel999/fpng](https://github.com/richgel999/fpng) - Super fast C++ .PNG writer/reader
* [libgd/libgd](https://github.com/libgd/libgd) - GD Graphics Library
* [AnJoiner/FFmpegCommand](https://github.com/AnJoiner/FFmpegCommand) - FFmpegCommand适用于Android的FFmpeg命令库，实现了对音视频相关的处理，能够快速的处理音视频，大概功能包括：音视频剪切，音视频转码，音视频解码原始数据，音视频编码，视频转图片或gif，视频添加水印，多画面拼接，音频混音，视频亮度和对比度，音频淡入和淡出效果等
* [phoboslab/pl_mpeg](https://github.com/phoboslab/pl_mpeg) - Single file C library for decoding MPEG1 Video and MP2 Audio
* [wlanjie/trinity](https://github.com/wlanjie/trinity) - android video record editor muxer sdk
* [CCExtractor/ccextractor](https://github.com/CCExtractor/ccextractor) - CCExtractor - Official version maintained by the core team
* [randy408/libspng](https://github.com/randy408/libspng) - Simple, modern libpng alternative
* [intel/libva](https://github.com/intel/libva) - Libva is an implementation for VA-API (Video Acceleration API)
* [ant-media/LibRtmp-Client-for-Android](https://github.com/ant-media/LibRtmp-Client-for-Android) - It is probably the smallest(~60KB, fat version ~300KB) rtmp client for android. It calls librtmp functions over JNI interface

## Security

### Cryptography

* [jedisct1/libsodium](https://github.com/jedisct1/libsodium) - A modern, portable, easy to use crypto library.
* [veracrypt/VeraCrypt](https://github.com/veracrypt/VeraCrypt) - Disk encryption with strong security based on TrueCrypt
* [Cyan4973/xxHash](https://github.com/Cyan4973/xxHash) - Extremely fast non-cryptographic hash algorithm
* [kokke/tiny-AES-c](https://github.com/kokke/tiny-AES-c) - Small portable AES128/192/256 in C
* [aws/s2n-tls](https://github.com/aws/s2n-tls) - An implementation of the TLS/SSL protocols
* [OpenSC/OpenSC](https://github.com/OpenSC/OpenSC) - Open source smart card tools and middleware. PKCS#11/MiniDriver
* [open-quantum-safe/liboqs](https://github.com/open-quantum-safe/liboqs) - C library for prototyping and experimenting with quantum-resistant cryptography
* [lastpass/lastpass-cli](https://github.com/lastpass/lastpass-cli) - LastPass command line interface tool
* [bitcoin-core/secp256k1](https://github.com/bitcoin-core/secp256k1) - Optimized C library for EC operations on curve secp256k1
* [gurnec/HashCheck](https://github.com/gurnec/HashCheck) - HashCheck Shell Extension for Windows with added SHA2, SHA3, and multithreading; originally from code.kliu.org
* [B-Con/crypto-algorithms](https://github.com/B-Con/crypto-algorithms) - Basic implementations of standard cryptography algorithms, like AES and SHA-1.
* [trezor/trezor-firmware](https://github.com/trezor/trezor-firmware) - :lock: Trezor Firmware Monorepo
* [libtom/libtomcrypt](https://github.com/libtom/libtomcrypt) - LibTomCrypt is a fairly comprehensive, modular and portable cryptographic toolkit that provides developers with a vast array of well known published block ciphers, one-way hash functions, chaining modes, pseudo-random number generators, public key cryptography and a plethora of other routines.
* [apple/swift-crypto](https://github.com/apple/swift-crypto) - Open-source implementation of a substantial portion of the API of Apple CryptoKit suitable for use on all Swift supported platforms.
* [libressl/portable](https://github.com/libressl/portable) - LibreSSL Portable itself. This includes the build scaffold and compatibility layer that builds portable LibreSSL from the OpenBSD source code. Pull requests or patches sent to tech@openbsd.org are welcome.
* [cr-marcstevens/sha1collisiondetection](https://github.com/cr-marcstevens/sha1collisiondetection) - Library and command line tool to detect SHA-1 collision in a file
* [YeeZTech/YeeZ-Privacy-Computing](https://github.com/YeeZTech/YeeZ-Privacy-Computing) - Fidelius - YeeZ Privacy Computing 基于可信执行环境的熠智隐私计算中间件
* [PQClean/PQClean](https://github.com/PQClean/PQClean) - Clean, portable, tested implementations of post-quantum cryptography *(archived)*
* [microsoft/SymCrypt](https://github.com/microsoft/SymCrypt) - Core cryptographic library for Windows, Azure Linux and other products
* [FreeApophis/TrueCrypt](https://github.com/FreeApophis/TrueCrypt) - This repository applies all Versions of the Original TrueCrypt Source Files in order
* [jedisct1/libhydrogen](https://github.com/jedisct1/libhydrogen) - A lightweight, secure, easy-to-use crypto library suitable for constrained environments.
* [veorq/SipHash](https://github.com/veorq/SipHash) - High-speed secure pseudorandom function for short messages
* [CipherShed/CipherShed](https://github.com/CipherShed/CipherShed) - Main CipherShed Development

### Security Tools

* [hashcat/hashcat](https://github.com/hashcat/hashcat) - World's fastest and most advanced password recovery utility
* [openwall/john](https://github.com/openwall/john) - John the Ripper jumbo - advanced offline password cracker, which supports hundreds of hash and cipher types, and runs on many operating systems, CPUs, GPUs, and even some FPGAs
* [jgamblin/Mirai-Source-Code](https://github.com/jgamblin/Mirai-Source-Code) - Leaked Mirai Source Code for Research/IoC Development Purposes
* [hfiref0x/UACME](https://github.com/hfiref0x/UACME) - Defeating Windows User Account Control
* [Cisco-Talos/clamav](https://github.com/Cisco-Talos/clamav) - ClamAV - Documentation is here: https://docs.clamav.net
* [nbs-system/naxsi](https://github.com/nbs-system/naxsi) - NAXSI is an open-source, high performance, low rules maintenance WAF for NGINX *(archived)*
* [greenbone/openvas-scanner](https://github.com/greenbone/openvas-scanner) - This repository contains the scanner component for Greenbone Community Edition.
* [google/honggfuzz](https://github.com/google/honggfuzz) - Security oriented software fuzzer. Supports evolutionary, feedback-driven fuzzing based on code coverage (SW and HW based)
* [RfidResearchGroup/ChameleonUltra](https://github.com/RfidResearchGroup/ChameleonUltra) - The new generation chameleon based on NRF52840 makes the performance of card emulation more stable. And gave the chameleon the ability to read, write, and decrypt cards.
* [seemoo-lab/nexmon](https://github.com/seemoo-lab/nexmon) - The C-based Firmware Patching Framework for Broadcom/Cypress WiFi Chips that enables Monitor Mode, Frame Injection and much more
* [hfiref0x/KDU](https://github.com/hfiref0x/KDU) - Kernel Driver Utility
* [gloxec/CrossC2](https://github.com/gloxec/CrossC2) - generate CobaltStrike's cross-platform payload
* [brendan-rius/c-jwt-cracker](https://github.com/brendan-rius/c-jwt-cracker) - JWT brute force cracker written in C
* [rspamd/rspamd](https://github.com/rspamd/rspamd) - Rapid spam filtering system.
* [Notselwyn/CVE-2024-1086](https://github.com/Notselwyn/CVE-2024-1086) - Universal local privilege escalation Proof-of-Concept exploit for CVE-2024-1086, working on most Linux kernels between v5.14 and v6.6, including Debian, Ubuntu, and KernelCTF. The success rate is 99.4% in KernelCTF images.
* [m0nad/Diamorphine](https://github.com/m0nad/Diamorphine) - LKM rootkit for Linux Kernels 2.6.x/3.x/4.x/5.x/6.x (x86/x86_64 and ARM64)
* [ZerBea/hcxtools](https://github.com/ZerBea/hcxtools) - A small set of tools to convert packets from capture files to hash files for use with Hashcat or John the Ripper.
* [bats3c/shad0w](https://github.com/bats3c/shad0w) - A post exploitation framework designed to operate covertly on heavily monitored environments
* [berdav/CVE-2021-4034](https://github.com/berdav/CVE-2021-4034) - CVE-2021-4034 1day
* [xoreaxeaxeax/skitter-creek-bath-salts](https://github.com/xoreaxeaxeax/skitter-creek-bath-salts) - Unlocking _everything_ on the CPU with DRAM scrambling
* [h3xduck/TripleCross](https://github.com/h3xduck/TripleCross) - A Linux eBPF rootkit with a backdoor, C2, library injection, execution hijacking, persistence and stealth capabilities.
* [vxunderground/VX-API](https://github.com/vxunderground/VX-API) - Collection of various malicious functionality to aid in malware development
* [droe/sslsplit](https://github.com/droe/sslsplit) - Transparent SSL/TLS interception
* [trustedsec/CS-Situational-Awareness-BOF](https://github.com/trustedsec/CS-Situational-Awareness-BOF) - Situational Awareness commands implemented using Beacon Object Files
* [emsec/ChameleonMini](https://github.com/emsec/ChameleonMini) - The ChameleonMini is a versatile contactless smartcard emulator compliant to NFC. The ChameleonMini was developed by https://kasper-oswald.de. The device is available at https://shop.kasper.it. For further information see the Getting Started Page https://rawgit.com/emsec/ChameleonMini/master/Doc/Doxygen/html/_page__getting_started.html or the Wiki tab above.
* [DosX-dev/obfus.h](https://github.com/DosX-dev/obfus.h) - Macro-header for compile-time C obfuscation (tcc, win x86/x64)
* [xaitax/Chrome-App-Bound-Encryption-Decryption](https://github.com/xaitax/Chrome-App-Bound-Encryption-Decryption) - Bypass Chromium's App-Bound Encryption via Direct Syscall-based Reflective Process Hollowing. Extract cookies, passwords, payment methods & tokens from Chrome, Edge, Brave & Avast - fileless, user-mode, no admin required.
* [Fr4nkFletcher/ESP32-Marauder-Cheap-Yellow-Display](https://github.com/Fr4nkFletcher/ESP32-Marauder-Cheap-Yellow-Display) - ESP32Marauder Cheap Yellow Display
* [taviso/ctftool](https://github.com/taviso/ctftool) - Interactive CTF Exploration Tool
* [NebuSec/CyberMeowfia](https://github.com/NebuSec/CyberMeowfia) - PoCs and exploits for CVEs discovered by NebuSec.
* [zeustrojancode/Zeus](https://github.com/zeustrojancode/Zeus) - NOT MY CODE! Zeus trojan horse - leaked in 2011, I am not the author. This repository is for study purposes only, do not message me about your lame hacking attempts. *(archived)*
* [newaetech/chipwhisperer](https://github.com/newaetech/chipwhisperer) - ChipWhisperer - the complete open-source toolchain for side-channel power analysis and glitching attacks
* [gentilkiwi/kekeo](https://github.com/gentilkiwi/kekeo) - A little toolbox to play with Microsoft Kerberos in C
* [Meckazin/ChromeKatz](https://github.com/Meckazin/ChromeKatz) - Dump cookies and credentials directly from Chrome/Edge process memory
* [boku7/BokuLoader](https://github.com/boku7/BokuLoader) - A proof-of-concept Cobalt Strike Reflective Loader which aims to recreate, integrate, and enhance Cobalt Strike's evasion features!
* [outflanknl/C2-Tool-Collection](https://github.com/outflanknl/C2-Tool-Collection) - A collection of tools which integrate with Cobalt Strike (and possibly other C2 frameworks) through BOF and reflective DLL loading techniques.
* [danigargu/CVE-2020-0796](https://github.com/danigargu/CVE-2020-0796) - CVE-2020-0796 - Windows SMBv3 LPE exploit #SMBGhost
* [hfiref0x/TDL](https://github.com/hfiref0x/TDL) - Driver loader for bypassing Windows x64 Driver Signature Enforcement *(archived)*
* [am0nsec/HellsGate](https://github.com/am0nsec/HellsGate) - Original C Implementation of the Hell's Gate VX Technique
* [trustedsec/CS-Remote-OPs-BOF](https://github.com/trustedsec/CS-Remote-OPs-BOF) - Remote operations commands implemented using Beacon Object Files
* [arthepsy/CVE-2021-4034](https://github.com/arthepsy/CVE-2021-4034) - PoC for PwnKit: Local Privilege Escalation Vulnerability in polkit’s pkexec (CVE-2021-4034)
* [Arinerron/CVE-2022-0847-DirtyPipe-Exploit](https://github.com/Arinerron/CVE-2022-0847-DirtyPipe-Exploit) - A root exploit for CVE-2022-0847 (Dirty Pipe)
* [scrt/avcleaner](https://github.com/scrt/avcleaner) - C/C++ source obfuscator for antivirus bypass
* [MatthewKuKanich/CAN_Commander](https://github.com/MatthewKuKanich/CAN_Commander) - CAN Commander is a comprehensive tool designed for the reverse engineering of CAN (Controller Area Network) bus systems. This project aims to provide a robust platform for automotive enthusiasts, engineers, and security researchers to interact with and analyze CAN networks, facilitating a deeper understanding and manipulation of communication.
* [timwr/CVE-2016-5195](https://github.com/timwr/CVE-2016-5195) - CVE-2016-5195 (dirtycow/dirtyc0w) proof of concept for Android
* [mempodippy/vlany](https://github.com/mempodippy/vlany) - Linux LD_PRELOAD rootkit (x86 and x86_64 architectures)
* [nil0x42/duplicut](https://github.com/nil0x42/duplicut) - Remove duplicates from MASSIVE wordlist, without sorting it (for dictionary-based password cracking)
* [hfiref0x/VBoxHardenedLoader](https://github.com/hfiref0x/VBoxHardenedLoader) - VirtualBox VM detection mitigation loader *(archived)*
* [mikeryan/crackle](https://github.com/mikeryan/crackle) - Crack and decrypt BLE encryption
* [hfiref0x/UPGDSED](https://github.com/hfiref0x/UPGDSED) - Universal PatchGuard and Driver Signature Enforcement Disable *(archived)*
* [frankmorgner/vsmartcard](https://github.com/frankmorgner/vsmartcard) - umbrella project for emulation of smart card readers or smart cards
* [jvoisin/snuffleupagus](https://github.com/jvoisin/snuffleupagus) - Security module for php7 and php8 - Killing bugclasses and virtual-patching the rest!
* [Eugnis/spectre-attack](https://github.com/Eugnis/spectre-attack) - Example of using revealed "Spectre" exploit (CVE-2017-5753 and CVE-2017-5715)
* [lockedbyte/CVE-Exploits](https://github.com/lockedbyte/CVE-Exploits) - PoC exploits for software vulnerabilities
* [ScottyBauer/Android_Kernel_CVE_POCs](https://github.com/ScottyBauer/Android_Kernel_CVE_POCs) - A list of my CVE's with POCs
* [ANSSI-FR/AD-control-paths](https://github.com/ANSSI-FR/AD-control-paths) - Active Directory Control Paths auditing and graphing tools *(archived)*
* [suvllian/process-inject](https://github.com/suvllian/process-inject) - 在Windows环境下的进程注入方法：远程线程注入、创建进程挂起注入、反射注入、APCInject、SetWindowHookEX注入
* [timwhitez/Cobalt-Strike-Aggressor-Scripts](https://github.com/timwhitez/Cobalt-Strike-Aggressor-Scripts) - Cobalt Strike Aggressor 插件包
* [cos120/captcha_crack](https://github.com/cos120/captcha_crack) - 选字验证码破解，试验过网易和极验，破解率99
* [laruence/taint](https://github.com/laruence/taint) - Taint is a PHP extension, used for detecting XSS codes
* [ionescu007/SpecuCheck](https://github.com/ionescu007/SpecuCheck) - SpecuCheck is a Windows utility for checking the state of the software mitigations and hardware against CVE-2017-5754 (Meltdown), CVE-2017-5715 (Spectre v2), CVE-2018-3260 (Foreshadow), and CVE-2018-3639 (Spectre v4)
* [nullsecuritynet/tools](https://github.com/nullsecuritynet/tools) - Security and Hacking Tools, Exploits, Proof of Concepts, Shellcodes, Scripts.

### Reverse Engineering

* [radareorg/radare2](https://github.com/radareorg/radare2) - UNIX-like reverse engineering framework and command-line toolset
* [capstone-engine/capstone](https://github.com/capstone-engine/capstone) - Capstone disassembly/disassembler framework for ARM, ARM64 (ARMv8), Alpha, BPF, Ethereum VM, HPPA, LoongArch, M68K, M680X, Mips, MOS65XX, PPC, RISC-V(rv32G/rv64G), SH, Sparc, SystemZ, TMS320C64X, TriCore, Webassembly, XCore and X86.
* [zyantific/zydis](https://github.com/zyantific/zydis) - Fast and lightweight x86/x86-64 disassembler and code generation library
* [pret/pokeemerald](https://github.com/pret/pokeemerald) - Decompilation of Pokémon Emerald
* [Perfare/Zygisk-Il2CppDumper](https://github.com/Perfare/Zygisk-Il2CppDumper) - Using Zygisk to dump il2cpp data at runtime
* [djkaty/Il2CppInspector](https://github.com/djkaty/Il2CppInspector) - Powerful automated tool for reverse engineering Unity IL2CPP binaries
* [hfiref0x/WinObjEx64](https://github.com/hfiref0x/WinObjEx64) - Windows Object Explorer 64-bit
* [rdbo/libmem](https://github.com/rdbo/libmem) - Advanced Game Hacking Library for C, Modern C++, Rust and Python (Windows/Linux/FreeBSD) (Process/Memory Hacking) (Hooking/Detouring) (Cross Platform) (x86/x64) (DLL/SO Injection) (Internal/External) (Assembler/Disassembler)
* [frida/frida-gum](https://github.com/frida/frida-gum) - Cross-platform instrumentation and introspection library written in C
* [ufrisk/LeechCore](https://github.com/ufrisk/LeechCore) - LeechCore - Physical Memory Acquisition Library & The LeechAgent Remote Memory Acquisition Agent
* [yulingtianxia/BlockHook](https://github.com/yulingtianxia/BlockHook) - Hook Objective-C blocks. A powerful AOP tool.
* [HoShiMin/HookLib](https://github.com/HoShiMin/HookLib) - The functions interception library written on pure C and NativeAPI with UserMode and KernelMode support
* [McGill-DMaS/Kam1n0-Community](https://github.com/McGill-DMaS/Kam1n0-Community) - The Kam1n0 Assembly Analysis Platform

## Concurrency and Performance

### Concurrency and Parallelism

* [libevent/libevent](https://github.com/libevent/libevent) - Event notification library
* [hnes/libaco](https://github.com/hnes/libaco) - A blazing fast and lightweight C asymmetric coroutine library 💎 ⛅🚀⛅🌞
* [sustrik/libmill](https://github.com/sustrik/libmill) - Go-style concurrency in C
* [concurrencykit/ck](https://github.com/concurrencykit/ck) - Concurrency primitives, safe memory reclamation mechanisms and non-blocking (including lock-free) data structures designed to aid in the research, design and implementation of high performance concurrent systems developed in C99+.
* [open-mpi/ompi](https://github.com/open-mpi/ompi) - Open MPI main development repository
* [swiftlang/swift-corelibs-libdispatch](https://github.com/swiftlang/swift-corelibs-libdispatch) - The libdispatch Project, (a.k.a. Grand Central Dispatch), for concurrency on multicore hardware
* [cloudwu/coroutine](https://github.com/cloudwu/coroutine) - A asymmetric coroutine library for C.
* [Pithikos/C-Thread-Pool](https://github.com/Pithikos/C-Thread-Pool) - A minimal but powerful thread pool in ANSI C
* [sustrik/libdill](https://github.com/sustrik/libdill) - Structured concurrency in C
* [facebookarchive/libphenom](https://github.com/facebookarchive/libphenom) - An eventing framework for building high performance and high scalability systems in C. *(archived)*
* [tidwall/neco](https://github.com/tidwall/neco) - Concurrency library for C (coroutines)
* [QuantumLeaps/qpc](https://github.com/QuantumLeaps/qpc) - QP/C Real-Time Event Framework/RTOS implements event-driven Active Object (Actor) model combined with Hierarchical State Machines. Specifically designed for embedded systems (e.g., ARM Cortex-M MCUs).
* [yann-shi/libcsp](https://github.com/yann-shi/libcsp) - A concurrency C library 10x faster than Golang.
* [google/nsync](https://github.com/google/nsync) - nsync is a C library that exports various synchronization primitives, such as mutexes
* [edubart/minicoro](https://github.com/edubart/minicoro) - Single header stackful cross-platform coroutine library in pure C.
* [wangbojing/NtyCo](https://github.com/wangbojing/NtyCo) - 纯c版本的协程实现，汇编切换，调度器实现，包含服务器端案例，客户端并发测试案例
* [mbrossard/threadpool](https://github.com/mbrossard/threadpool) - A simple C Thread pool implementation
* [iqiyi/libfiber](https://github.com/iqiyi/libfiber) - The high performance c/c++ coroutine/fiber library for Linux/FreeBSD/MacOS/Windows, supporting select/poll/epoll/kqueue/iouring/iocp/windows GUI.
* [halayli/lthread](https://github.com/halayli/lthread) - lthread, a multicore enabled coroutine library written in C
* [naasking/async.h](https://github.com/naasking/async.h) - Stackless Async Subroutines for C
* [socketry/cool.io](https://github.com/socketry/cool.io) - Simple evented I/O for Ruby.

### Performance and Optimization

* [lz4/lz4](https://github.com/lz4/lz4) - Extremely Fast Compression algorithm
* [bdwgc/bdwgc](https://github.com/bdwgc/bdwgc) - The Boehm-Demers-Weiser conservative C/C++ Garbage Collector (bdwgc, also known as bdw-gc, boehm-gc, libgc)
* [PlummersSoftwareLLC/Primes](https://github.com/PlummersSoftwareLLC/Primes) - Prime number projects in 100+ programming languages, to compare their speed - and their programmer's cleverness
* [richgel999/miniz](https://github.com/richgel999/miniz) - miniz: Single C source file zlib-replacement library, originally from code.google.com/p/miniz
* [ColinIanKing/stress-ng](https://github.com/ColinIanKing/stress-ng) - This is the stress-ng upstream project git repository. stress-ng will stress test a computer system in various selectable ways. It was designed to exercise various physical subsystems of a computer as well as the various operating system kernel interfaces.
* [mjansson/rpmalloc](https://github.com/mjansson/rpmalloc) - Public domain cross platform lock free thread caching 16-byte aligned memory allocator implemented in C
* [zlib-ng/zlib-ng](https://github.com/zlib-ng/zlib-ng) - zlib replacement with optimizations for "next generation" systems.
* [RRZE-HPC/likwid](https://github.com/RRZE-HPC/likwid) - Performance monitoring and benchmarking suite
* [tukaani-project/xz](https://github.com/tukaani-project/xz) - XZ Utils
* [kuba--/zip](https://github.com/kuba--/zip) - A portable, simple zip library written in C
* [Cyan4973/FiniteStateEntropy](https://github.com/Cyan4973/FiniteStateEntropy) - New generation entropy codecs : Finite State Entropy and Huff0
* [zlib-ng/minizip-ng](https://github.com/zlib-ng/minizip-ng) - Fork of the popular zip manipulation library found in the zlib distribution.
* [eembc/coremark](https://github.com/eembc/coremark) - CoreMark® is an industry-standard benchmark that measures the performance of central processing units (CPU) and embedded microcrontrollers (MCU).
* [orangeduck/tgc](https://github.com/orangeduck/tgc) - A Tiny Garbage Collector for C
* [Blosc/c-blosc](https://github.com/Blosc/c-blosc) - A blocking, shuffling and loss-less compression library that can be faster than `memcpy()`.
* [nih-at/libzip](https://github.com/nih-at/libzip) - A C library for reading, creating, and modifying zip archives.
* [CCareaga/heap_allocator](https://github.com/CCareaga/heap_allocator) - A simple heap memory allocator in ~200 lines.
* [powturbo/TurboPFor-Integer-Compression](https://github.com/powturbo/TurboPFor-Integer-Compression) - Fastest Integer Compression
* [KhronosGroup/OpenCL-Headers](https://github.com/KhronosGroup/OpenCL-Headers) - Khronos OpenCL-Headers
* [intel/intel-cmt-cat](https://github.com/intel/intel-cmt-cat) - User space software for Intel(R) Resource Director Technology
* [dyu/ffi-overhead](https://github.com/dyu/ffi-overhead) - comparing the c ffi (foreign function interface) overhead on various programming languages

## Testing and Quality

### Testing

* [ThrowTheSwitch/Unity](https://github.com/ThrowTheSwitch/Unity) - Simple unit testing for C
* [cucumber/common](https://github.com/cucumber/common) - A home for issues that are common to multiple cucumber repositories
* [linux-test-project/ltp](https://github.com/linux-test-project/ltp) - Linux Test Project (mailing list: https://lists.linux.it/listinfo/ltp)
* [Snaipe/Criterion](https://github.com/Snaipe/Criterion) - A cross-platform C and C++ unit testing framework for the 21st century
* [silentbicycle/greatest](https://github.com/silentbicycle/greatest) - A C testing library in 1 file. No dependencies, no dynamic allocation. ISC licensed.
* [libcheck/check](https://github.com/libcheck/check) - A unit testing framework for C
* [meekrosoft/fff](https://github.com/meekrosoft/fff) - A testing micro framework for creating function test doubles
* [ThrowTheSwitch/CMock](https://github.com/ThrowTheSwitch/CMock) - Mock/stub generator for C
* [silentbicycle/theft](https://github.com/silentbicycle/theft) - property-based testing for C: generate input to find obscure bugs, then reduce to minimal failing input

## Utilities

### Command Line Tools

* [git/git](https://github.com/git/git) - Git Source Code Mirror - This is a publish-only repository but pull requests can be turned into patches to the mailing list via GitGitGadget (https://gitgitgadget.github.io/). Please follow Documentation/SubmittingPatches procedure for any of your improvements.
* [ggreer/the_silver_searcher](https://github.com/ggreer/the_silver_searcher) - A code-searching tool similar to ack, but faster.
* [fastfetch-cli/fastfetch](https://github.com/fastfetch-cli/fastfetch) - A maintained, feature-rich and performance oriented, neofetch like system information tool.
* [coreutils/coreutils](https://github.com/coreutils/coreutils) - Public mirror. Pull requests and Issues accepted
* [dvorka/hstr](https://github.com/dvorka/hstr) - Bash and Zsh shell history TUI suggest box - easily view, navigate, search and manage your command history.
* [mridgers/clink](https://github.com/mridgers/clink) - Bash's powerful command line editing in cmd.exe
* [jhawthorn/fzy](https://github.com/jhawthorn/fzy) - :mag: A simple, fast fuzzy finder for the terminal
* [altdesktop/playerctl](https://github.com/altdesktop/playerctl) - 🎧 mpris media player command-line controller for vlc, mpv, RhythmBox, web browsers, cmus, mpd, spotify and others.
* [mvp/uhubctl](https://github.com/mvp/uhubctl) - uhubctl - USB hub per-port power control
* [okbob/pspg](https://github.com/okbob/pspg) - Unix pager (with very rich functionality) designed for work with tables. Designed for PostgreSQL, but MySQL is supported too. Works well with pgcli too. Can be used as CSV or TSV viewer too. It supports searching, selecting rows, columns, or block and export selected area to clipboard.
* [bugaevc/wl-clipboard](https://github.com/bugaevc/wl-clipboard) - Command-line copy/paste utilities for Wayland
* [posva/catimg](https://github.com/posva/catimg) - 🦦 Insanely fast image printing in your terminal
* [tanakh/cmdline](https://github.com/tanakh/cmdline) - A Command Line Parser
* [ridiculousfish/cdecl-blocks](https://github.com/ridiculousfish/cdecl-blocks) - The venerable cdecl, with Apple blocks support
* [tj/mon](https://github.com/tj/mon) - mon(1) - Simple single-process process monitoring program written in C
* [mptre/pick](https://github.com/mptre/pick) - A fuzzy search tool for the command-line
* [cofyc/argparse](https://github.com/cofyc/argparse) - Command-line arguments parsing library.
* [rwos/gti](https://github.com/rwos/gti) - a git launcher :-)

### Logging and Configuration

* [armink/EasyLogger](https://github.com/armink/EasyLogger) - An ultra-lightweight(ROM<1.6K, RAM<0.3k), high-performance C/C++ log library. | 一款超轻量级(ROM<1.6K, RAM<0.3k)、高性能的 C/C++ 日志库
* [rxi/log.c](https://github.com/rxi/log.c) - A simple logging library implemented in C99
* [benhoyt/inih](https://github.com/benhoyt/inih) - Simple .INI file parser in C, good for embedded systems
* [HardySimpson/zlog](https://github.com/HardySimpson/zlog) - A reliable, high-performance, thread safe, flexsible, clear-model, pure C logging library.
* [syslog-ng/syslog-ng](https://github.com/syslog-ng/syslog-ng) - syslog-ng is an enhanced log daemon, supporting a wide range of input and output methods: syslog, unstructured text, queueing, SQL & NoSQL.
* [rsyslog/rsyslog](https://github.com/rsyslog/rsyslog) - High-performance log ingestion and ETL engine
* [hyperrealm/libconfig](https://github.com/hyperrealm/libconfig) - C/C++ Library for Processing Structured Configuration Files
* [laruence/yaconf](https://github.com/laruence/yaconf) - A PHP Persistent Configurations Container
* [rokath/trice](https://github.com/rokath/trice) - 🟢 Super-fast, tiny C/C++ tracing with printf look-and-feel, even in interrupts ⚡, plus real-time PC logging 💻

### Text Processing

* [antirez/sds](https://github.com/antirez/sds) - Simple Dynamic Strings library for C
* [ashvardanian/StringZilla](https://github.com/ashvardanian/StringZilla) - Up to 100x faster strings for C, C++, CUDA, Python, Rust, Swift, JS, & Go, leveraging NEON, AVX2, AVX-512, SVE, GPGPU, & SWAR to accelerate search, hashing, sorting, edit distances, sketches, and memory ops 🦖
* [orangeduck/mpc](https://github.com/orangeduck/mpc) - A Parser Combinator library for C
* [kkos/oniguruma](https://github.com/kkos/oniguruma) - regular expression library *(archived)*
* [sisong/HDiffPatch](https://github.com/sisong/HDiffPatch) - a C\C++ library and command-line tools for Diff & Patch between binary files or directories(folder); cross-platform; runs fast; create small delta/differential; support large files and limit memory requires when diff & patch.
* [commonmark/cmark](https://github.com/commonmark/cmark) - CommonMark parsing and rendering library and program in C
* [vmg/sundown](https://github.com/vmg/sundown) - Standards compliant, fast, secure markdown processing library in C
* [sheredom/utf8.h](https://github.com/sheredom/utf8.h) - 📚 single header utf8 string functions for C and C++
* [kokke/tiny-regex-c](https://github.com/kokke/tiny-regex-c) - Small portable regex in C
* [mity/md4c](https://github.com/mity/md4c) - C Markdown parser. Fast. SAX-like interface. Compliant to CommonMark specification.
* [JuliaStrings/utf8proc](https://github.com/JuliaStrings/utf8proc) - a clean C library for processing UTF-8 Unicode data
* [WojciechMula/pyahocorasick](https://github.com/WojciechMula/pyahocorasick) - Python module (C extension and plain python) implementing Aho-Corasick algorithm
* [galkahana/PDF-Writer](https://github.com/galkahana/PDF-Writer) - High performance library for creating, modiyfing and parsing PDF files in C++
* [Orc/discount](https://github.com/Orc/discount) - My C implementation of John Gruber's Markdown markup language
* [skullchap/chadstr](https://github.com/skullchap/chadstr) - Chad Strings - The Chad way to handle strings in C.
* [jgm/peg-markdown](https://github.com/jgm/peg-markdown) - An implementation of markdown in C, using a PEG grammar
* [k-takata/Onigmo](https://github.com/k-takata/Onigmo) - Onigmo is a regular expressions library forked from Oniguruma.

### Files and Operating System

* [systemd/systemd](https://github.com/systemd/systemd) - The systemd System and Service Manager
* [libusb/libusb](https://github.com/libusb/libusb) - A cross-platform library to access USB devices
* [dokan-dev/dokany](https://github.com/dokan-dev/dokany) - User mode file system library for windows with FUSE Wrapper
* [checkpoint-restore/criu](https://github.com/checkpoint-restore/criu) - Checkpoint/Restore tool
* [inotify-tools/inotify-tools](https://github.com/inotify-tools/inotify-tools) - inotify-tools is a library and a set of command-line programs providing a simple interface to inotify.
* [proot-me/proot](https://github.com/proot-me/proot) - chroot, mount --bind, and binfmt_misc without privilege/setup for Linux
* [sahib/rmlint](https://github.com/sahib/rmlint) - Extremely fast tool to remove duplicates and other lint from your filesystem
* [pbatard/libwdi](https://github.com/pbatard/libwdi) - Windows Driver Installer library for USB devices
* [libusb/hidapi](https://github.com/libusb/hidapi) - A Simple cross-platform library for communicating with HID devices
* [Dr-Noob/cpufetch](https://github.com/Dr-Noob/cpufetch) - Simple yet fancy CPU architecture fetching tool
* [linux-nvme/nvme-cli](https://github.com/linux-nvme/nvme-cli) - NVMe management command line interface.
* [nfs-ganesha/nfs-ganesha](https://github.com/nfs-ganesha/nfs-ganesha) - NFS-Ganesha is an NFSv3,v4,v4.1 fileserver that runs in user mode on most UNIX/Linux systems
* [opsengine/cpulimit](https://github.com/opsengine/cpulimit) - CPU usage limiter for Linux
* [libimobiledevice/usbmuxd](https://github.com/libimobiledevice/usbmuxd) - A socket daemon to multiplex connections from and to iOS devices
* [systemd/casync](https://github.com/systemd/casync) - Content-Addressable Data Synchronization Tool
* [Fazecast/jSerialComm](https://github.com/Fazecast/jSerialComm) - Platform-independent serial port access for Java
* [sheredom/subprocess.h](https://github.com/sheredom/subprocess.h) - 🐜 single header process launching solution for C and C++
* [pytorch/cpuinfo](https://github.com/pytorch/cpuinfo) - CPU INFOrmation library (x86/x86-64/ARM/ARM64, Linux/Windows/Android/macOS/iOS)
* [tronkko/dirent](https://github.com/tronkko/dirent) - C/C++ library for retrieving information on files and directories
* [vsergeev/c-periphery](https://github.com/vsergeev/c-periphery) - A C library for peripheral I/O (GPIO, LED, PWM, SPI, I2C, MMIO, Serial) in Linux.
* [libimobiledevice/ifuse](https://github.com/libimobiledevice/ifuse) - A fuse filesystem to access the contents of iOS devices
* [pbatard/uefi-ntfs](https://github.com/pbatard/uefi-ntfs) - UEFI:NTFS - Boot NTFS or exFAT partitions from UEFI
* [psankar/simplefs](https://github.com/psankar/simplefs) - A simple, kernel-space, on-disk filesystem from the scratch
* [skarnet/s6](https://github.com/skarnet/s6) - The s6 supervision suite.
* [lavoiesl/osx-cpu-temp](https://github.com/lavoiesl/osx-cpu-temp) - Outputs current CPU temperature for OSX
* [cxong/tinydir](https://github.com/cxong/tinydir) - Lightweight, portable and easy to integrate C directory and file reader
* [saprykin/plibsys](https://github.com/saprykin/plibsys) - Highly portable C system library: threads and synchronization primitives, sockets (TCP, UDP, SCTP), IPv4 and IPv6, IPC, hash functions (MD5, SHA-1, SHA-2, SHA-3, GOST), binary trees (RB, AVL) and more. Native code performance.

### General Purpose Libraries

* [nothings/stb](https://github.com/nothings/stb) - stb single-file public domain libraries for C/C++
* [jart/cosmopolitan](https://github.com/jart/cosmopolitan) - build-once run-anywhere c library
* [pocoproject/poco](https://github.com/pocoproject/poco) - The POCO C++ Libraries are powerful cross-platform C++ libraries for building network- and internet-based applications that run on desktop, server, mobile, IoT, and embedded systems.
* [orangeduck/Cello](https://github.com/orangeduck/Cello) - Higher level programming in C
* [swiftlang/swift-corelibs-foundation](https://github.com/swiftlang/swift-corelibs-foundation) - The Foundation Project, providing core utilities, internationalization, and OS independence
* [tboox/tbox](https://github.com/tboox/tbox) - 🎁 A glib-like multi-platform c library
* [troydhanson/uthash](https://github.com/troydhanson/uthash) - C macros for hash tables and more
* [attractivechaos/klib](https://github.com/attractivechaos/klib) - A standalone and lightweight C library
* [fragglet/c-algorithms](https://github.com/fragglet/c-algorithms) - A library of common data structures and algorithms written in C.
* [gozfree/gear-lib](https://github.com/gozfree/gear-lib) - Gear-Lib, C library for IOT Embedded Multimedia and Network
* [yitter/IdGenerator](https://github.com/yitter/IdGenerator) - 💎多语言实现，高性能生成唯一数字ID。 💎优化的雪花算法（SnowFlake）——雪花漂移算法，在缩短ID长度的同时，具备极高瞬时并发处理能力（50W/0.1s）。 💎原生支持 C#/Java/Go/Rust/C/JavaScript/TypeScript/Python/Pascal 多语言，提供其它适用于其它语言的多线程安全调用动态库（FFI）。💎支持容器环境自动扩容（自动注册 WorkerId ），单机或分布式唯一IdGenerator。💎顶尖优化，超强效能。
* [srdja/Collections-C](https://github.com/srdja/Collections-C) - A library of generic data structures for the C language.
* [tezc/sc](https://github.com/tezc/sc) - Common libraries and data structures for C.
* [mattiasgustavsson/libs](https://github.com/mattiasgustavsson/libs) - Single-file public domain libraries for C/C++
* [scandum/quadsort](https://github.com/scandum/quadsort) - Quadsort is a branchless stable adaptive mergesort faster than quicksort.
* [cs50/libcs50](https://github.com/cs50/libcs50) - This is CS50's Library for C.
* [RoaringBitmap/CRoaring](https://github.com/RoaringBitmap/CRoaring) - Roaring bitmaps in C (and C++), with SIMD (AVX2, AVX-512 and NEON) optimizations: used by Apache Doris, ClickHouse, Alibaba Tair, Redpanda, YDB and StarRocks
* [begeekmyfriend/bplustree](https://github.com/begeekmyfriend/bplustree) - A minimal but extreme fast B+ tree indexing structure demo for billions of key-value storage
* [picolibc/picolibc](https://github.com/picolibc/picolibc) - picolibc - a C library designed for embedded 32- and 64- bit systems.
* [MaJerle/lwrb](https://github.com/MaJerle/lwrb) - Lightweight generic ring buffer manager library
* [Water-Melon/Melon](https://github.com/Water-Melon/Melon) - A generic cross-platform C library that includes many commonly used components and frameworks, and a new scripting language interpreter. It currently supports C99 and Aspect-Oriented Programming (AOP).
* [vurtun/lib](https://github.com/vurtun/lib) - single header libraries for C/C++
* [Crypto-toolbox/HFT-Orderbook](https://github.com/Crypto-toolbox/HFT-Orderbook) - Limit Order Book for high-frequency trading (HFT), as described by WK Selph, implemented in Python3 and C
* [glouw/ctl](https://github.com/glouw/ctl) - The C Template Library
* [mkirchner/gc](https://github.com/mkirchner/gc) - Simple, zero-dependency garbage collection for C
* [antirez/rax](https://github.com/antirez/rax) - A radix tree implementation in ANSI C
* [KaisenAmin/c_std](https://github.com/KaisenAmin/c_std) - Implementation of C++ standard libraries in C
* [graphitemaster/incbin](https://github.com/graphitemaster/incbin) - Include binary files in C/C++
* [rustyrussell/ccan](https://github.com/rustyrussell/ccan) - The C Code Archive Network
* [P-p-H-d/mlib](https://github.com/P-p-H-d/mlib) - M*LIB is a library of generic and type safe containers / data structures in pure C language (C99 / C11) for a wide collection of container (comparable to the C++ STL).
* [wangyi-fudan/wyhash](https://github.com/wangyi-fudan/wyhash) - The FASTEST QUALITY hash function, random number generators (PRNG) and hash map.
* [managarm/mlibc](https://github.com/managarm/mlibc) - Portable C standard library
* [hirrolot/metalang99](https://github.com/hirrolot/metalang99) - Full-blown preprocessor metaprogramming
* [JimmyLefevre/kb](https://github.com/JimmyLefevre/kb) - kb single-header C/C++ libraries
* [zpl-c/zpl](https://github.com/zpl-c/zpl) - 📐 Pushing the boundaries of simplicity
* [tidwall/hashmap.c](https://github.com/tidwall/hashmap.c) - Hash map implementation in C.
* [wolkykim/qlibc](https://github.com/wolkykim/qlibc) - qLibc is a simple and yet powerful C library providing generic data structures and algorithms.
* [pfultz2/Cloak](https://github.com/pfultz2/Cloak) - A mini-preprocessor library to demostrate the recursive capabilites of the preprocessor
* [happyfish100/libfastcommon](https://github.com/happyfish100/libfastcommon) - c common functions library extracted from my open source project FastDFS. this library is very simple and stable. functions including: string, logger, chain, hash, socket, ini file reader, base64 encode / decode, url encode / decode, fast timer, skiplist, object pool etc. detail info please see the c header files.
* [eteran/c-vector](https://github.com/eteran/c-vector) - A dynamic array implementation in C similar to the one found in standard C++
* [septag/sx](https://github.com/septag/sx) - Portable base library for C programmers, designed for performance and simplicity. *(archived)*
* [armon/libart](https://github.com/armon/libart) - Adaptive Radix Trees implemented in C
* [nemequ/portable-snippets](https://github.com/nemequ/portable-snippets) - Collection of miscellaneous portable C snippets.
* [stateless-me/uuidv47](https://github.com/stateless-me/uuidv47) - ⚡ UUIDv47 = v4 privacy + v7 performance
* [scandum/blitsort](https://github.com/scandum/blitsort) - Blitsort is an in-place stable adaptive rotate mergesort / quicksort.
* [MichaelJWelsh/cdsa](https://github.com/MichaelJWelsh/cdsa) - A library of generic intrusive data structures and algorithms in ANSI C

## Systems and Hardware

### Operating Systems and Kernels

* [reactos/reactos](https://github.com/reactos/reactos) - A free Windows-compatible Operating System
* [acidanthera/OpenCorePkg](https://github.com/acidanthera/OpenCorePkg) - OpenCore bootloader
* [ravynsoft/ravynos](https://github.com/ravynsoft/ravynos) - An open-source OS project that aims to provide source and binary compatibility with macOS® and a similar user experience.
* [klange/toaruos](https://github.com/klange/toaruos) - Complete, independent operating system built by humans.
* [RIOT-OS/RIOT](https://github.com/RIOT-OS/RIOT) - RIOT - The friendly OS for IoT
* [CloverHackyColor/CloverBootloader](https://github.com/CloverHackyColor/CloverBootloader) - Bootloader for macOS, Windows and Linux in UEFI and in legacy mode
* [contiki-os/contiki](https://github.com/contiki-os/contiki) - The official git repository for Contiki, the open source OS for the Internet of Things
* [cesanta/mongoose-os](https://github.com/cesanta/mongoose-os) - Mongoose OS - an IoT Firmware Development Framework. Supported microcontrollers: ESP32, ESP8266, CC3220, CC3200, STM32F4, STM32L4, STM32F7. Amazon AWS IoT, Microsoft Azure, Google IoT Core integrated. Code in C or JavaScript.
* [cnlohr/mini-rv32ima](https://github.com/cnlohr/mini-rv32ima) - A tiny C header-only risc-v emulator.
* [embox/embox](https://github.com/embox/embox) - Modular and configurable OS for embedded applications
* [contiki-ng/contiki-ng](https://github.com/contiki-ng/contiki-ng) - Contiki-NG: The OS for Next Generation IoT Devices
* [Harvey-OS/harvey](https://github.com/Harvey-OS/harvey) - A distributed operating system *(archived)*
* [LekKit/RVVM](https://github.com/LekKit/RVVM) - The RISC-V Virtual Machine
* [rswier/swieros](https://github.com/rswier/swieros) - A tiny hand crafted CPU emulator, C compiler, and Operating System
* [brutal-org/brutal](https://github.com/brutal-org/brutal) - 🏢 An operating system inspired by brutalist design that combines the ideals of UNIX from the 1970s with modern technology and engineering
* [weston-embedded/uC-OS3](https://github.com/weston-embedded/uC-OS3) - µC/OS-III is a preemptive, highly portable, and scalable real-time kernel. Designed for ease of use on a huge number of CPU architectures.
* [particle-iot/device-os](https://github.com/particle-iot/device-os) - Device OS (Firmware) for Particle Devices
* [FDOS/kernel](https://github.com/FDOS/kernel) - FreeDOS kernel - implements the core MS-DOS/PC-DOS (R) compatible operating system. It is derived from Pat Villani's DOS-C kernel and released under the GPL v2 or later. Please see http://www.freedos.org/ for more details about the FreeDOS (TM) Project.
* [halfer53/winix](https://github.com/halfer53/winix) - A UNIX-style Operating System for the Waikato RISC Architecture Microprocessor (WRAMP)
* [qrush/unix](https://github.com/qrush/unix) - Mirror of the Restoration of 1st Edition UNIX kernel sources from pdf document.
* [apache/mynewt-core](https://github.com/apache/mynewt-core) - An OS to build, deploy and securely manage billions of devices
* [ChibiOS/ChibiOS](https://github.com/ChibiOS/ChibiOS) - Read only mirror of SVN ChibiOS repository at https://sourceforge.net/projects/chibios/
* [joexbayer/RetrOS-32](https://github.com/joexbayer/RetrOS-32) - A x86 32bit Hobby Operatingsystem with graphics, multitasking, networking and 32bit C-Compiler for i386 architecture.
* [Supercip971/WingOS](https://github.com/Supercip971/WingOS) - a little 64bit microkernel based operating system written in c++ with smp support
* [SilverRainZ/OS67](https://github.com/SilverRainZ/OS67) - An unix-like toy kernel

### Embedded and Firmware

* [qmk/qmk_firmware](https://github.com/qmk/qmk_firmware) - Open-source keyboard firmware for Atmel AVR and Arm USB families
* [hrvach/deskhop](https://github.com/hrvach/deskhop) - Fast Desktop Switching Device
* [peng-zhihui/L-ink_Card](https://github.com/peng-zhihui/L-ink_Card) - Smart NFC & ink-Display Card
* [crosspoint-reader/crosspoint-reader](https://github.com/crosspoint-reader/crosspoint-reader) - Open-source e-reader firmware
* [peng-zhihui/HoloCubic](https://github.com/peng-zhihui/HoloCubic) - 带网络功能的伪全息透明显示桌面站
* [tianocore/edk2](https://github.com/tianocore/edk2) - EDK II
* [witnessmenow/ESP32-Cheap-Yellow-Display](https://github.com/witnessmenow/ESP32-Cheap-Yellow-Display) - Building a community around a cheap ESP32 Display with a touch screen
* [InfiniTimeOrg/InfiniTime](https://github.com/InfiniTimeOrg/InfiniTime) - Firmware for Pinetime smartwatch written in C++ and based on FreeRTOS
* [stm32duino/Arduino_Core_STM32](https://github.com/stm32duino/Arduino_Core_STM32) - STM32 core support for Arduino
* [RavenSystem/esp-homekit-devices](https://github.com/RavenSystem/esp-homekit-devices) - Advanced firmware to add native Apple HomeKit and custom configurations, compatible with any SoC based on ESP32, ESP32-S, ESP32-C and ESP8266 series. (Shelly, Sonoff, Electrodragon, Tuya...)
* [coreboot/coreboot](https://github.com/coreboot/coreboot) - Read-only mirror of https://review.coreboot.org/coreboot.git. Synced every hour. We don't handle Pull Requests.
* [virtio-win/kvm-guest-drivers-windows](https://github.com/virtio-win/kvm-guest-drivers-windows) - Windows paravirtualized drivers for QEMU\KVM
* [EdgeTX/edgetx](https://github.com/EdgeTX/edgetx) - EdgeTX is the cutting edge open source firmware for your R/C radio
* [rsta2/circle](https://github.com/rsta2/circle) - A C++ bare metal environment for Raspberry Pi with USB (32 and 64 bit)
* [MarlinFirmware/Configurations](https://github.com/MarlinFirmware/Configurations) - Configurations for Marlin Firmware
* [HermannBjorgvin/Clawdmeter](https://github.com/HermannBjorgvin/Clawdmeter) - ESP32 desk dashboard that shows Claude Code usage
* [cherry-embedded/CherryUSB](https://github.com/cherry-embedded/CherryUSB) - CherryUSB is a tiny and beautiful, high performance and portable USB host and device stack for embedded system with USB IP
* [egzumer/uv-k5-firmware-custom](https://github.com/egzumer/uv-k5-firmware-custom) - A merge between https://github.com/OneOfEleven/uv-k5-firmware-custom and https://github.com/fagci/uv-k5-firmware-fagci-mod
* [buserror/simavr](https://github.com/buserror/simavr) - simavr is a lean, mean and hackable AVR simulator for linux & OSX
* [SpenceKonde/ATTinyCore](https://github.com/SpenceKonde/ATTinyCore) - Arduino core for ATtiny 1634, 828, x313, x4, x41, x5, x61, x7 and x8
* [brektrou/rtl8821CU](https://github.com/brektrou/rtl8821CU) - Realtek RTL8811CU/RTL8821CU USB Wi-Fi adapter driver for Linux
* [ARM-software/CMSIS_5](https://github.com/ARM-software/CMSIS_5) - CMSIS Version 5 Development Repository *(archived)*
* [cnlohr/ch32fun](https://github.com/cnlohr/ch32fun) - Open source minimal stack for the ch32 and ch5xx WCH RISC-V Microcontrollers
* [joan2937/pigpio](https://github.com/joan2937/pigpio) - pigpio is a C library for the Raspberry which allows control of the General Purpose Input Outputs (GPIO).
* [cnlohr/channel3](https://github.com/cnlohr/channel3) - ESP8266 Analog Broadcast Television Interface
* [pimoroni/pimoroni-pico](https://github.com/pimoroni/pimoroni-pico) - Libraries and examples to support Pimoroni Pico add-ons in C++ and MicroPython.
* [bitcraze/crazyflie-firmware](https://github.com/bitcraze/crazyflie-firmware) - The main firmware for the Crazyflie Nano Quadcopter, Crazyflie Bolt Quadcopter and Roadrunner Positioning Tag.
* [easytarget/esp32-cam-webserver](https://github.com/easytarget/esp32-cam-webserver) - Expanded version of the Espressif ESP webcam
* [arduino/ArduinoCore-avr](https://github.com/arduino/ArduinoCore-avr) - The Official Arduino AVR core
* [dekuNukem/bob_cassette_rewinder](https://github.com/dekuNukem/bob_cassette_rewinder) - Renew and Refill Bob Cassettes for 98% Cost Saving!
* [nasa/cFS](https://github.com/nasa/cFS) - The Core Flight System (cFS)
* [Time-Appliances-Project/Time-Card](https://github.com/Time-Appliances-Project/Time-Card) - Develop an end-to-end hypothetical reference model, network architectures, precision time tools, performance objectives and the methods to distribute, operate, monitor time synchronization within data center and much more...
* [eclipse-mraa/mraa](https://github.com/eclipse-mraa/mraa) - Linux Library for low speed IO Communication in C with bindings for C++, Python, Node.js & Java. Supports generic io platforms, as well as Intel Edison, Intel Joule, Raspberry Pi and many more.
* [analogdevicesinc/no-OS](https://github.com/analogdevicesinc/no-OS) - Software drivers in C for systems without an operating system
* [ClimbSnail/HoloCubic_AIO](https://github.com/ClimbSnail/HoloCubic_AIO) - HoloCubic超多功能AIO固件 基于esp32-arduino的天气时钟、相册、视频播放、桌面投屏、web服务、bilibili粉丝等
* [cariboulabs/cariboulite](https://github.com/cariboulabs/cariboulite) - CaribouLite turns any 40-pin Raspberry-Pi into a Tx/Rx 6GHz SDR
* [STMicroelectronics/STM32CubeF4](https://github.com/STMicroelectronics/STM32CubeF4) - STM32Cube MCU Full Package for the STM32F4 series - (HAL + LL Drivers, CMSIS Core, CMSIS Device, MW libraries plus a set of Projects running on all boards provided by ST (Nucleo, Evaluation and Discovery Kits))
* [n0xa/m5stick-nemo](https://github.com/n0xa/m5stick-nemo) - M5 Stick C firmware for high-tech pranks and digital self defense
* [Bumblebee-Project/Bumblebee](https://github.com/Bumblebee-Project/Bumblebee) - Bumblebee daemon and client rewritten in C
* [FrameworkComputer/EmbeddedController](https://github.com/FrameworkComputer/EmbeddedController) - Embedded Controller firmware for the Framework Laptop
* [Polprzewodnikowy/SummerCart64](https://github.com/Polprzewodnikowy/SummerCart64) - SummerCart64 - a fully open source N64 flashcart
* [45clouds/WirelessCarPlay](https://github.com/45clouds/WirelessCarPlay) - Wireless CarPlay for CarPlay enabled cars
* [feaser/openblt](https://github.com/feaser/openblt) - Official read-only mirror of the SVN OpenBLT bootloader repository. Updated daily.
* [gnif/vendor-reset](https://github.com/gnif/vendor-reset) - Linux kernel vendor specific hardware reset module for sequences that are too complex/complicated to land in pci_quirks.c
* [candle-usb/candleLight_fw](https://github.com/candle-usb/candleLight_fw) - gs_usb compatible firmware for candleLight, cantact and canable
* [stawel/cheali-charger](https://github.com/stawel/cheali-charger) - cheap lipo charger
* [STMicroelectronics/STMems_Standard_C_drivers](https://github.com/STMicroelectronics/STMems_Standard_C_drivers) - Platform-independent drivers for STMicroelectronics MEMS motion sensors, environmental sensors, infrared sensors and biosensors, based on standard C programming language.
* [KevinOConnor/can2040](https://github.com/KevinOConnor/can2040) - Software CAN bus implementation for rp2040 micro-controllers
* [morrownr/8821cu-20210916](https://github.com/morrownr/8821cu-20210916) - Linux Driver for USB WiFi Adapters that are based on the RTL8811CU, RTL8821CU, RTL8821CUH and RTL8731AU Chipsets - v5.12.0.4
* [openxc/uds-c](https://github.com/openxc/uds-c) - Unified Diagnostics Service (UDS) and OBD-II (On Board Diagnostics for Vehicles) C Library
* [kiibohd/controller](https://github.com/kiibohd/controller) - Kiibohd Controller
* [pvaret/rtl8192cu-fixes](https://github.com/pvaret/rtl8192cu-fixes) - Realtek 8192 chipset driver, ported to kernel 3.11.
* [MaltWhiskey/Mega-Cube](https://github.com/MaltWhiskey/Mega-Cube) - 16x16x16 PL9823 Cube with Teensy 4.0 and FlexIO driver
* [konosubakonoakua/FPGA_MCU_Debugger_Collections](https://github.com/konosubakonoakua/FPGA_MCU_Debugger_Collections) - 各种LInk大合集

## Science and Math

### Mathematics

* [recp/cglm](https://github.com/recp/cglm) - 📽 Highly Optimized 2D / 3D Graphics Math (glm) for C
* [igraph/igraph](https://github.com/igraph/igraph) - Library for the analysis of networks
* [codeplea/tinyexpr](https://github.com/codeplea/tinyexpr) - tiny recursive descent expression parser, compiler, and evaluation engine for math expressions
* [ashvardanian/NumKong](https://github.com/ashvardanian/NumKong) - SIMD-accelerated distances, dot products, matrix ops, geospatial & geometric kernels for 16 numeric types — from 6-bit floats to 64-bit complex — across x86, Arm, RISC-V, and WASM, with bindings for Python, Rust, C, C++, Swift, JS, and Go 📐
* [HandmadeMath/HandmadeMath](https://github.com/HandmadeMath/HandmadeMath) - A simple math library for games and computer graphics. Compatible with both C and C++. Public domain and easy to modify.
* [DrTimothyAldenDavis/SuiteSparse](https://github.com/DrTimothyAldenDavis/SuiteSparse) - The official SuiteSparse library: a suite of sparse matrix algorithms authored or co-authored by Tim Davis, Texas A&M University.
* [msteinbeck/tinyspline](https://github.com/msteinbeck/tinyspline) - ANSI C library for NURBS, B-Splines, and Bézier curves with interfaces for C++, C#, D, Go, Java, Javascript, Lua, Octave, PHP, Python, R, and Ruby.
* [simondlevy/TinyEKF](https://github.com/simondlevy/TinyEKF) - Lightweight C/C++ Extended Kalman Filter with Python for prototyping
* [ARM-software/CMSIS-DSP](https://github.com/ARM-software/CMSIS-DSP) - CMSIS-DSP embedded compute library for Cortex-M and Cortex-A
* [cvxopt/cvxopt](https://github.com/cvxopt/cvxopt) - CVXOPT -- Python Software for Convex Optimization
* [libtom/libtommath](https://github.com/libtom/libtommath) - LibTomMath is a free open source portable number theoretic multiple-precision integer library written entirely in C.
* [felselva/mathc](https://github.com/felselva/mathc) - Pure C math library for 2D and 3D programming

### Scientific Computing

* [grbl/grbl](https://github.com/grbl/grbl) - An open source, embedded, high performance g-code-parser and CNC milling controller written in optimized C that will run on a straight Arduino
* [gnea/grbl](https://github.com/gnea/grbl) - An open source, embedded, high performance g-code-parser and CNC milling controller written in optimized C that will run on a straight Arduino
* [cleanflight/cleanflight](https://github.com/cleanflight/cleanflight) - Clean-code version of the baseflight flight controller firmware
* [ucb-bar/chipyard](https://github.com/ucb-bar/chipyard) - An Agile RISC-V SoC Design Framework with in-order cores, out-of-order cores, accelerators, and more
* [samtools/samtools](https://github.com/samtools/samtools) - Tools (written in C using htslib) for manipulating next-generation sequencing data
* [SlugLab/CXLMemSim](https://github.com/SlugLab/CXLMemSim) - CXLMemSim: Practical Performance Simulation and Characterization of CXL 3.0 Memory Systems
* [Duet3D/RepRapFirmware](https://github.com/Duet3D/RepRapFirmware) - OO C++ RepRap Firmware
* [GenericMappingTools/gmt](https://github.com/GenericMappingTools/gmt) - The Generic Mapping Tools
* [samtools/htslib](https://github.com/samtools/htslib) - C library for high-throughput sequencing data formats
* [pms67/PID](https://github.com/pms67/PID) - PID controller implementation written in C.
* [pysam-developers/pysam](https://github.com/pysam-developers/pysam) - Pysam is a Python package for reading, manipulating, and writing genomics data such as SAM/BAM/CRAM and VCF/BCF files. It's a lightweight wrapper of the HTSlib API, the same one that powers samtools, bcftools, and tabix.
* [charliegerard/Epoc.js](https://github.com/charliegerard/Epoc.js) - Node.js addon for the Emotiv C++ SDK

## Other

* [torvalds/linux](https://github.com/torvalds/linux) - Linux kernel source tree
* [microsoft/PowerToys](https://github.com/microsoft/PowerToys) - Microsoft PowerToys is a collection of utilities that supercharge productivity and customization on Windows
* [ventoy/Ventoy](https://github.com/ventoy/Ventoy) - A new bootable USB solution.
* [redis/redis](https://github.com/redis/redis) - For developers, who are building real-time data-driven applications, Redis is the preferred, fastest, and most feature-rich cache, data structure server, and document and vector query engine.
* [ggml-org/whisper.cpp](https://github.com/ggml-org/whisper.cpp) - Port of OpenAI's Whisper model in C/C++
* [tmux/tmux](https://github.com/tmux/tmux) - tmux source code
* [curl/curl](https://github.com/curl/curl) - A command line tool and library for transferring data with URL syntax, supporting DICT, FILE, FTP, FTPS, GOPHER, GOPHERS, HTTP, HTTPS, IMAP, IMAPS, LDAP, LDAPS, MQTT, MQTTS, POP3, POP3S, RTSP, SCP, SFTP, SMB, SMBS, SMTP, SMTPS, TELNET, TFTP, WS and WSS. libcurl offers a myriad of powerful features
* [wg/wrk](https://github.com/wg/wrk) - Modern HTTP benchmarking tool
* [php/php-src](https://github.com/php/php-src) - The PHP Interpreter
* [jqlang/jq](https://github.com/jqlang/jq) - Command-line JSON processor
* [valinet/ExplorerPatcher](https://github.com/valinet/ExplorerPatcher) - This project aims to enhance the working environment on Windows
* [bilibili/ijkplayer](https://github.com/bilibili/ijkplayer) - Android/iOS video player based on FFmpeg n3.4, with MediaCodec, VideoToolbox support.
* [kingToolbox/WindTerm](https://github.com/kingToolbox/WindTerm) - A professional cross-platform SSH/Sftp/Shell/Telnet/Tmux/Serial terminal.
* [lizongying/my-tv](https://github.com/lizongying/my-tv) - 我的电视 电视直播软件，安装即可使用
* [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede) - Lean's LEDE source
* [nginx/nginx](https://github.com/nginx/nginx) - The official NGINX Open Source repository.
* [openssl/openssl](https://github.com/openssl/openssl) - General purpose TLS and crypto library
* [cfenollosa/os-tutorial](https://github.com/cfenollosa/os-tutorial) - How to create an OS from scratch
* [asmvik/yabai](https://github.com/asmvik/yabai) - A tiling window manager for macOS based on binary space partitioning
* [ValdikSS/GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI) - GoodbyeDPI — Deep Packet Inspection circumvention utility (for Windows)
* [openwrt/openwrt](https://github.com/openwrt/openwrt) - This repository is a mirror of https://git.openwrt.org/openwrt/openwrt.git It is for reference only and is not active for check-ins. We will continue to accept Pull Requests here. They will be merged via staging trees then into openwrt.git.
* [facebook/zstd](https://github.com/facebook/zstd) - Zstandard - Fast real-time compression algorithm
* [libuv/libuv](https://github.com/libuv/libuv) - Cross-platform asynchronous I/O
* [valkey-io/valkey](https://github.com/valkey-io/valkey) - A flexible distributed key-value database that is optimized for caching and other realtime workloads.
* [pjreddie/darknet](https://github.com/pjreddie/darknet) - Convolutional Neural Networks
* [robertdavidgraham/masscan](https://github.com/robertdavidgraham/masscan) - TCP port scanner, spews SYN packets asynchronously, scanning entire Internet in under 5 minutes.
* [taosdata/TDengine](https://github.com/taosdata/TDengine) - High-performance, scalable time-series database designed for Industrial IoT (IIoT) scenarios
* [arendst/Tasmota](https://github.com/arendst/Tasmota) - Alternative firmware for ESP8266 and ESP32 based devices with easy configuration using webUI, OTA updates, automation using timers or rules, expandability and entirely local control over MQTT, HTTP, Serial or KNX. Full documentation at
* [HandBrake/HandBrake](https://github.com/HandBrake/HandBrake) - HandBrake's development repository
* [timescale/timescaledb](https://github.com/timescale/timescaledb) - A time-series database for high-performance real-time analytics packaged as a Postgres extension
* [pgvector/pgvector](https://github.com/pgvector/pgvector) - Open-source vector similarity search for Postgres
* [iovisor/bcc](https://github.com/iovisor/bcc) - BCC - Tools for BPF-based Linux IO analysis, networking, monitoring, and more
* [DarkFlippers/unleashed-firmware](https://github.com/DarkFlippers/unleashed-firmware) - Flipper Zero Unleashed Firmware
* [antirez/ds4](https://github.com/antirez/ds4) - DeepSeek 4 Flash and PRO local inference engine for Metal, CUDA and ROCm
* [micropython/micropython](https://github.com/micropython/micropython) - MicroPython - a lean and efficient Python implementation for microcontrollers and constrained systems
* [postgres/postgres](https://github.com/postgres/postgres) - Mirror of the official PostgreSQL GIT repository. Note that this is just a *mirror* - we don't work with pull requests on github. To contribute, please see https://wiki.postgresql.org/wiki/Submitting_a_Patch
* [gentilkiwi/mimikatz](https://github.com/gentilkiwi/mimikatz) - A little tool to play with Windows security
* [julycoding/The-Art-Of-Programming-By-July-2nd](https://github.com/julycoding/The-Art-Of-Programming-By-July-2nd) - 本项目曾冲到全球第一，干货集锦见本页面最底部，另完整精致的纸质版《编程之法：面试和算法心得》已在京东/当当上销售
* [ish-app/ish](https://github.com/ish-app/ish) - Linux shell for iOS
* [Awesome-HarmonyOS/HarmonyOS](https://github.com/Awesome-HarmonyOS/HarmonyOS) - A curated list of awesome things related to HarmonyOS. 华为鸿蒙操作系统。
* [ExistentialAudio/BlackHole](https://github.com/ExistentialAudio/BlackHole) - BlackHole is a modern macOS audio loopback driver that allows applications to pass audio to other applications with zero additional latency.
* [sandboxie-plus/Sandboxie](https://github.com/sandboxie-plus/Sandboxie) - Sandboxie Plus & Classic
* [espressif/esp-idf](https://github.com/espressif/esp-idf) - Espressif IoT Development Framework. Official development framework for Espressif SoCs.
* [brunodev85/winlator](https://github.com/brunodev85/winlator) - Android application for running Windows applications with Wine and Box86/Box64
* [ffmpegwasm/ffmpeg.wasm](https://github.com/ffmpegwasm/ffmpeg.wasm) - FFmpeg for browser, powered by WebAssembly
* [UberGuidoZ/Flipper](https://github.com/UberGuidoZ/Flipper) - Playground (and dump) of stuff I make or modify for the Flipper Zero
* [ImageMagick/ImageMagick](https://github.com/ImageMagick/ImageMagick) - ImageMagick is a free, open-source software suite for creating, editing, converting, and displaying images. It supports 200+ formats and offers powerful command-line tools and APIs for automation, scripting, and integration across platforms.
* [NVIDIA/open-gpu-kernel-modules](https://github.com/NVIDIA/open-gpu-kernel-modules) - NVIDIA Linux open GPU kernel module source
* [swaywm/sway](https://github.com/swaywm/sway) - i3-compatible Wayland compositor
* [tursodatabase/libsql](https://github.com/tursodatabase/libsql) - libSQL is a fork of SQLite that is both Open Source, and Open Contributions.
* [woltapp/blurhash](https://github.com/woltapp/blurhash) - A very compact representation of a placeholder for an image.
* [flipperdevices/flipperzero-firmware](https://github.com/flipperdevices/flipperzero-firmware) - Flipper Zero firmware source code
* [libsdl-org/SDL](https://github.com/libsdl-org/SDL) - Simple DirectMedia Layer
* [zephyrproject-rtos/zephyr](https://github.com/zephyrproject-rtos/zephyr) - Primary Git Repository for the Zephyr Project. Zephyr is a new generation, scalable, optimized, secure RTOS for multiple hardware architectures.
* [bol-van/zapret](https://github.com/bol-van/zapret) - DPI bypass multi platform
* [peng-zhihui/Dummy-Robot](https://github.com/peng-zhihui/Dummy-Robot) - 我的超迷你机械臂机器人项目。
* [gojue/ecapture](https://github.com/gojue/ecapture) - Capturing SSL/TLS plaintext without a CA certificate using eBPF. Supported on Linux/Android kernels for amd64/arm64.
* [haiwen/seafile](https://github.com/haiwen/seafile) - Beyond file syncing and sharing, a new way to organize your files with extensible file properties and flexible views
* [duixcom/Duix-Avatar](https://github.com/duixcom/Duix-Avatar) - 🚀 Truly open-source AI avatar(digital human) toolkit for offline video generation and digital human cloning.
* [SpacehuhnTech/esp8266_deauther](https://github.com/SpacehuhnTech/esp8266_deauther) - Affordable WiFi hacking platform for testing and learning
* [srwi/EverythingToolbar](https://github.com/srwi/EverythingToolbar) - Everything integration for the Windows taskbar.
* [OpenVPN/openvpn](https://github.com/OpenVPN/openvpn) - OpenVPN is an open source VPN daemon
* [memcached/memcached](https://github.com/memcached/memcached) - memcached development tree
* [cloudwu/skynet](https://github.com/cloudwu/skynet) - A lightweight online game framework
* [arut/nginx-rtmp-module](https://github.com/arut/nginx-rtmp-module) - NGINX-based Media Streaming Server
* [openresty/openresty](https://github.com/openresty/openresty) - High Performance Web Platform Based on Nginx and LuaJIT
* [Curzibn/Luban](https://github.com/Curzibn/Luban) - Luban 2（鲁班 2） —— 高效简洁的 Android 图片压缩工具库，像素级还原微信朋友圈压缩策略。(An efficient and concise Android image compression library that closely replicates the compression strategy of WeChat Moments.)
* [qemu/qemu](https://github.com/qemu/qemu) - Official QEMU mirror. Please see https://www.qemu.org/contribute/ for how to submit changes to QEMU. Pull Requests are disabled. Please only use release tarballs from the QEMU website.
* [nmap/nmap](https://github.com/nmap/nmap) - Nmap - the Network Mapper. Github mirror of official SVN repository.
* [SoftEtherVPN/SoftEtherVPN](https://github.com/SoftEtherVPN/SoftEtherVPN) - Cross-platform multi-protocol VPN software. Pull requests are welcome. The stable version is available at https://github.com/SoftEtherVPN/SoftEtherVPN_Stable.
* [microsoft/mimalloc](https://github.com/microsoft/mimalloc) - mimalloc is a compact general purpose allocator with excellent performance.
* [alibaba/tengine](https://github.com/alibaba/tengine) - A high-performance web server and reverse proxy, 100% compatible with nginx.
* [raspberrypi/linux](https://github.com/raspberrypi/linux) - Kernel source tree for Raspberry Pi-provided kernel builds. Issues unrelated to the linux kernel should be posted on the community forum at https://forums.raspberrypi.com/
* [cesanta/mongoose](https://github.com/cesanta/mongoose) - Embedded web server, with TCP/IP network stack, MQTT and Websocket
* [darktable-org/darktable](https://github.com/darktable-org/darktable) - darktable is an open source photography workflow application and raw developer
* [octalmage/robotjs](https://github.com/octalmage/robotjs) - Node.js Desktop Automation.
* [colmap/colmap](https://github.com/colmap/colmap) - COLMAP - Structure-from-Motion and Multi-View Stereo
* [redcanaryco/atomic-red-team](https://github.com/redcanaryco/atomic-red-team) - Small and highly portable detection tests based on MITRE's ATT&CK.
* [google/sanitizers](https://github.com/google/sanitizers) - AddressSanitizer, ThreadSanitizer, MemorySanitizer
* [openzfs/zfs](https://github.com/openzfs/zfs) - OpenZFS on Linux and FreeBSD
* [twitter/twemproxy](https://github.com/twitter/twemproxy) - A fast, light-weight proxy for memcached and redis
* [FelixKratz/SketchyBar](https://github.com/FelixKratz/SketchyBar) - A highly customizable macOS status bar replacement
* [tsl0922/ttyd](https://github.com/tsl0922/ttyd) - Share your terminal over the web
* [vanhauser-thc/thc-hydra](https://github.com/vanhauser-thc/thc-hydra) - hydra
* [RT-Thread/rt-thread](https://github.com/RT-Thread/rt-thread) - RT-Thread is an open source IoT Real-Time Operating System (RTOS). https://rt-thread.github.io/rt-thread/
* [EZLippi/Tinyhttpd](https://github.com/EZLippi/Tinyhttpd) - Tinyhttpd 是J. David Blackstone在1999年写的一个不到 500 行的超轻量型 Http Server，用来学习非常不错，可以帮助我们真正理解服务器程序的本质。官网:http://tinyhttpd.sourceforge.net
* [Klipper3d/klipper](https://github.com/Klipper3d/klipper) - Klipper is a 3d-printer firmware
* [openresty/lua-nginx-module](https://github.com/openresty/lua-nginx-module) - Embed the Power of Lua into NGINX HTTP servers
* [Tencent/wcdb](https://github.com/Tencent/wcdb) - WCDB is a cross-platform database framework developed by WeChat.
* [immortalwrt/immortalwrt](https://github.com/immortalwrt/immortalwrt) - An opensource OpenWrt variant for mainland China users.
* [h2o/h2o](https://github.com/h2o/h2o) - H2O - the optimized HTTP/1, HTTP/2, HTTP/3 server
* [betaflight/betaflight](https://github.com/betaflight/betaflight) - Open Source Flight Controller Firmware
* [screetsec/TheFatRat](https://github.com/screetsec/TheFatRat) - Thefatrat a massive exploiting tool : Easy tool to generate backdoor and easy tool to post exploitation attack like browser attack and etc . This tool compiles a malware with popular payload and then the compiled malware can be execute on windows, android, mac . The malware that created with this tool also have an ability to bypass most AV software protection .
* [apple/darwin-xnu](https://github.com/apple/darwin-xnu) - Legacy mirror of Darwin Kernel. Replaced by https://github.com/apple-oss-distributions/xnu *(archived)*
* [eclipse-mosquitto/mosquitto](https://github.com/eclipse-mosquitto/mosquitto) - Eclipse Mosquitto - An open source MQTT broker
* [jemalloc/jemalloc](https://github.com/jemalloc/jemalloc)
* [leandromoreira/ffmpeg-libav-tutorial](https://github.com/leandromoreira/ffmpeg-libav-tutorial) - FFmpeg libav tutorial - learn how media works from basic to transmuxing, transcoding and more. Translations: 🇺🇸 🇨🇳 🇰🇷 🇪🇸 🇻🇳 🇧🇷 🇷🇺
* [bellard/quickjs](https://github.com/bellard/quickjs) - Public repository of the QuickJS Javascript Engine.
* [Syllo/nvtop](https://github.com/Syllo/nvtop) - GPU & Accelerator process monitoring for AMD, Apple, Huawei, Intel, NVIDIA and Qualcomm
* [dicedb/dicedb](https://github.com/dicedb/dicedb) - Open-source, low-latency key/value engine built on Valkey with query subscriptions and hierarchical storage tiers.
* [rofl0r/proxychains-ng](https://github.com/rofl0r/proxychains-ng) - proxychains ng (new generation) - a preloader which hooks calls to sockets in dynamically linked programs and redirects it through one or more socks/http proxies. continuation of the unmaintained proxychains project. the sf.net page is currently not updated, use releases from github release page instead.
* [libgit2/libgit2](https://github.com/libgit2/libgit2) - A cross-platform, linkable library implementation of Git that you can use in your application.
* [i3/i3](https://github.com/i3/i3) - A tiling window manager for X11
* [microsoft/WSL2-Linux-Kernel](https://github.com/microsoft/WSL2-Linux-Kernel) - The source for the Linux kernel used in Windows Subsystem for Linux 2 (WSL2)
* [Dr-TSNG/ZygiskNext](https://github.com/Dr-TSNG/ZygiskNext) - Standalone implementation of Zygisk
* [yugabyte/yugabyte-db](https://github.com/yugabyte/yugabyte-db) - YugabyteDB - the cloud native distributed SQL database for mission-critical applications.
* [imbushuo/mac-precision-touchpad](https://github.com/imbushuo/mac-precision-touchpad) - Windows Precision Touchpad Driver Implementation for Apple MacBook / Magic Trackpad
* [sqlite/sqlite](https://github.com/sqlite/sqlite) - Official Git mirror of the SQLite source tree
* [henrypp/memreduct](https://github.com/henrypp/memreduct) - Lightweight real-time memory management application to monitor and clean system memory on your computer.
* [erincatto/box2d](https://github.com/erincatto/box2d) - Box2D is a 2D physics engine for games
* [mit-pdos/xv6-riscv](https://github.com/mit-pdos/xv6-riscv) - Xv6 for RISC-V
* [lua/lua](https://github.com/lua/lua) - A copy of the Lua development repository, as seen by the Lua team. Mirrored irregularly. All communication should be through the Lua mailing list https://www.lua.org/lua-l.html
* [tporadowski/redis](https://github.com/tporadowski/redis) - Native port of Redis for Windows. Redis is an in-memory database that persists on disk. The data model is key-value, but many different kind of values are supported: Strings, Lists, Sets, Sorted Sets, Hashes, Streams, HyperLogLogs. This repository contains unofficial port of Redis to Windows.
* [huangzworks/redis-3.0-annotated](https://github.com/huangzworks/redis-3.0-annotated) - 带有详细注释的 Redis 3.0 代码（annotated Redis 3.0 source code）。
* [xmrig/xmrig](https://github.com/xmrig/xmrig) - RandomX, KawPow, CryptoNight and GhostRider unified CPU/GPU miner and RandomX benchmark
* [Flipper-XFW/Xtreme-Firmware](https://github.com/Flipper-XFW/Xtreme-Firmware) - The Dom amongst the Flipper Zero Firmware. Give your Flipper the power and freedom it is really craving. Let it show you its true form. Dont delay, switch to the one and only true Master today! *(archived)*
* [VirusTotal/yara](https://github.com/VirusTotal/yara) - The pattern matching swiss knife
* [wireshark/wireshark](https://github.com/wireshark/wireshark) - Read-only mirror of Wireshark's Git repository at https://gitlab.com/wireshark/wireshark. You're welcome to submit pull requests there.
* [ahrm/sioyek](https://github.com/ahrm/sioyek) - Sioyek is a PDF viewer with a focus on textbooks and research papers
* [mit-pdos/xv6-public](https://github.com/mit-pdos/xv6-public) - xv6 OS
* [peng-zhihui/ElectronBot](https://github.com/peng-zhihui/ElectronBot)
* [AdAway/AdAway](https://github.com/AdAway/AdAway) - AdAway is a free and open source ad blocker for Android.
* [freebsd/freebsd-src](https://github.com/freebsd/freebsd-src) - The FreeBSD src tree publish-only repository. Experimenting with 'simple' pull requests....
* [unicorn-engine/unicorn](https://github.com/unicorn-engine/unicorn) - Unicorn CPU emulator framework (ARM, AArch64, M68K, Mips, Sparc, PowerPC, RiscV, S390x, TriCore, X86)
* [happyfish100/fastdfs](https://github.com/happyfish100/fastdfs) - FastDFS is a high performance distributed file system (DFS). It's major functions include: file storing, file syncing and file accessing, and design for high capacity and load balance. Wechat/Weixin public account (Chinese Language): fastdfs
* [QwenAudio/SenseVoice](https://github.com/QwenAudio/SenseVoice) - Open-source SenseVoiceSmall model for Mandarin, Cantonese, English, Japanese, and Korean ASR, language ID, emotion recognition, and audio event detection.
* [mattn/go-sqlite3](https://github.com/mattn/go-sqlite3) - sqlite3 driver for go using database/sql
* [meetecho/janus-gateway](https://github.com/meetecho/janus-gateway) - Janus WebRTC Server
* [torch/torch7](https://github.com/torch/torch7) - http://torch.ch
* [microsoft/react-native-code-push](https://github.com/microsoft/react-native-code-push) - React Native module for CodePush *(archived)*
* [antirez/kilo](https://github.com/antirez/kilo) - A text editor in less than 1000 LOC with syntax highlight and search.
* [Next-Flip/Momentum-Firmware](https://github.com/Next-Flip/Momentum-Firmware) - 🐬 Feature-rich, stable and customizable Flipper Firmware
* [flightlessmango/MangoHud](https://github.com/flightlessmango/MangoHud) - A Vulkan and OpenGL overlay for monitoring FPS, temperatures, CPU/GPU load and more.
* [nonstriater/Learn-Algorithms](https://github.com/nonstriater/Learn-Algorithms) - 算法学习笔记
* [henrypp/simplewall](https://github.com/henrypp/simplewall) - Simple tool to configure Windows Filtering Platform (WFP) which can configure network activity on your computer.
* [winfsp/winfsp](https://github.com/winfsp/winfsp) - Windows File System Proxy - FUSE for Windows
* [Xfennec/progress](https://github.com/Xfennec/progress) - Linux tool to show progress for cp, mv, dd, ... (formerly known as cv)
* [shellphish/how2heap](https://github.com/shellphish/how2heap) - A repository for learning various heap exploitation techniques.
* [n64decomp/sm64](https://github.com/n64decomp/sm64) - A Super Mario 64 decompilation, brought to you by a bunch of clever folks.
* [irungentoo/toxcore](https://github.com/irungentoo/toxcore) - The future of online communications.
* [esnet/iperf](https://github.com/esnet/iperf) - iperf3: A TCP, UDP, and SCTP network bandwidth measurement tool
* [SecWiki/windows-kernel-exploits](https://github.com/SecWiki/windows-kernel-exploits) - windows-kernel-exploits Windows平台提权漏洞集合
* [0xFA11/MultiplayerNetworkingResources](https://github.com/0xFA11/MultiplayerNetworkingResources) - A curated list of Multiplayer Game Network Programming Resources
* [CTCaer/hekate](https://github.com/CTCaer/hekate) - hekate - A GUI based Nintendo Switch Bootloader
* [neutralinojs/neutralinojs](https://github.com/neutralinojs/neutralinojs) - Portable and lightweight cross-platform desktop application development framework
* [containers/bubblewrap](https://github.com/containers/bubblewrap) - Low-level unprivileged sandboxing tool used by Flatpak and similar projects
* [skeeto/endlessh](https://github.com/skeeto/endlessh) - SSH tarpit that slowly sends an endless banner
* [squeaky-pl/japronto](https://github.com/squeaky-pl/japronto) - Screaming-fast Python 3.5+ HTTP toolkit integrated with pipelining HTTP server based on uvloop and picohttpparser.
* [timercrack/trader](https://github.com/timercrack/trader) - 期货自动交易
* [Ralim/IronOS](https://github.com/Ralim/IronOS) - Open Source Soldering Iron firmware
* [baskerville/bspwm](https://github.com/baskerville/bspwm) - A tiling window manager based on binary space partitioning
* [id-Software/Quake-III-Arena](https://github.com/id-Software/Quake-III-Arena) - Quake III Arena GPL Source Release
* [libimobiledevice/libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) - A cross-platform protocol library to communicate with iOS devices
* [asmvik/skhd](https://github.com/asmvik/skhd) - Simple hotkey daemon for macOS
* [greatscottgadgets/hackrf](https://github.com/greatscottgadgets/hackrf) - low cost software radio platform
* [asg017/sqlite-vec](https://github.com/asg017/sqlite-vec) - A vector search SQLite extension that runs anywhere!
* [antirez/disque](https://github.com/antirez/disque) - Disque is a distributed message broker
* [istoreos/istoreos](https://github.com/istoreos/istoreos) - 提供一个人人会用的的路由、NAS系统 （目前活跃的分支是 istoreos-24.10，main或master分支不维护请勿使用）
* [wasm3/wasm3](https://github.com/wasm3/wasm3) - 🚀 A fast WebAssembly interpreter and the most universal WASM runtime
* [bingoogolapple/BGAQRCode-Android](https://github.com/bingoogolapple/BGAQRCode-Android) - QRCode 扫描二维码、扫描条形码、相册获取图片后识别、生成带 Logo 二维码、支持微博微信 QQ 二维码扫描样式
* [yarrick/iodine](https://github.com/yarrick/iodine) - Official git repo for iodine dns tunnel
* [haad/proxychains](https://github.com/haad/proxychains) - proxychains - a tool that forces any TCP connection made by any given application to follow through proxy like TOR or any other SOCKS4, SOCKS5 or HTTP(S) proxy. Supported auth-types: "user/pass" for SOCKS4/5, "basic" for HTTP.
* [nodemcu/nodemcu-firmware](https://github.com/nodemcu/nodemcu-firmware) - Lua based interactive firmware for ESP8266, ESP8285 and ESP32
* [fontforge/fontforge](https://github.com/fontforge/fontforge) - Free (libre) font editor for Windows, Mac OS X and GNU+Linux
* [miloyip/json-tutorial](https://github.com/miloyip/json-tutorial) - 从零开始的 JSON 库教程
* [ufrisk/pcileech](https://github.com/ufrisk/pcileech) - Direct Memory Access (DMA) Attack Software
* [microsoft/Windows-driver-samples](https://github.com/microsoft/Windows-driver-samples) - This repo contains driver samples prepared for use with Microsoft Visual Studio and the Windows Driver Kit (WDK). It contains both Universal Windows Driver and desktop-only driver samples.
* [bartobri/no-more-secrets](https://github.com/bartobri/no-more-secrets) - A command line tool that recreates the famous data decryption effect seen in the 1992 movie Sneakers.
* [merbanan/rtl_433](https://github.com/merbanan/rtl_433) - Program to decode radio transmissions from devices on the ISM bands (and other frequencies)
* [FreeRTOS/FreeRTOS](https://github.com/FreeRTOS/FreeRTOS) - 'Classic' FreeRTOS distribution. Started as Git clone of FreeRTOS SourceForge SVN repo. Submodules the kernel.
* [maharmstone/btrfs](https://github.com/maharmstone/btrfs) - WinBtrfs - an open-source btrfs driver for Windows
* [libfuse/sshfs](https://github.com/libfuse/sshfs) - A network filesystem client to connect to SSH servers
* [netblue30/firejail](https://github.com/netblue30/firejail) - Linux namespaces and seccomp-bpf sandbox
* [aircrack-ng/aircrack-ng](https://github.com/aircrack-ng/aircrack-ng) - WiFi security auditing tools suite
* [jart/blink](https://github.com/jart/blink) - tiniest x86-64-linux emulator
* [OpenMathLib/OpenBLAS](https://github.com/OpenMathLib/OpenBLAS) - OpenBLAS is an optimized BLAS library based on GotoBLAS2 1.13 BSD version.
* [philipl/pifs](https://github.com/philipl/pifs) - πfs - the data-free filesystem!
* [phoboslab/qoi](https://github.com/phoboslab/qoi) - The “Quite OK Image Format” for fast, lossless image compression
* [antirez/smallchat](https://github.com/antirez/smallchat) - A minimal programming example for a chat server
* [EpicGames/raddebugger](https://github.com/EpicGames/raddebugger) - A native, user-mode, multi-process, graphical debugger.
* [jerryscript-project/jerryscript](https://github.com/jerryscript-project/jerryscript) - Ultra-lightweight JavaScript engine for the Internet of Things.
* [google-deepmind/lab](https://github.com/google-deepmind/lab) - A customisable 3D platform for agent-based AI research
* [mgba-emu/mgba](https://github.com/mgba-emu/mgba) - mGBA Game Boy Advance Emulator
* [mcmilk/7-Zip-zstd](https://github.com/mcmilk/7-Zip-zstd) - 7-Zip with support for Brotli, Fast-LZMA2, Lizard, LZ4, LZ5 and Zstandard
* [universal-ctags/ctags](https://github.com/universal-ctags/ctags) - A maintained ctags implementation
* [sqlcipher/sqlcipher](https://github.com/sqlcipher/sqlcipher) - SQLCipher is a standalone fork of SQLite that adds 256 bit AES encryption of database files and other security features.
* [liuliu/ccv](https://github.com/liuliu/ccv) - C-based/Cached/Core Computer Vision Library, A Modern Computer Vision Library
* [Zelda64Recomp/Zelda64Recomp](https://github.com/Zelda64Recomp/Zelda64Recomp) - Static recompilation of Majora's Mask (and soon Ocarina of Time) for PC (Windows/Linux/Mac)
* [stanfordnlp/GloVe](https://github.com/stanfordnlp/GloVe) - Software in C and data files for the popular GloVe model for distributed word representations, a.k.a. word vectors or embeddings
* [Serial-Studio/Serial-Studio](https://github.com/Serial-Studio/Serial-Studio) - Open-source telemetry dashboard. Supports UART, BLE, MQTT, Modbus, CAN Bus and more.
* [vysheng/tg](https://github.com/vysheng/tg) - telegram-cli
* [OpenIntelWireless/itlwm](https://github.com/OpenIntelWireless/itlwm) - Intel Wi-Fi Drivers for macOS
* [sabrogden/Ditto](https://github.com/sabrogden/Ditto) - Ditto is an extension to the Windows Clipboard. You copy something to the Clipboard and Ditto takes what you copied and stores it in a database to retrieve at a later time.
* [hathach/tinyusb](https://github.com/hathach/tinyusb) - An open source cross-platform USB stack for embedded system
* [madler/zlib](https://github.com/madler/zlib) - A massively spiffy yet delicately unobtrusive compression library.
* [moonlight-stream/moonlight-android](https://github.com/moonlight-stream/moonlight-android) - GameStream client for Android
* [microsoft/winfile](https://github.com/microsoft/winfile) - Original Windows File Manager (winfile) with enhancements *(archived)*
* [ntop/n2n](https://github.com/ntop/n2n) - Peer-to-peer VPN
* [Mbed-TLS/mbedtls](https://github.com/Mbed-TLS/mbedtls) - An open source, portable, easy to use, readable and flexible TLS library, and reference implementation of the PSA Cryptography API. Releases are on a varying cadence, typically around 3 - 6 months between releases.
* [littlefs-project/littlefs](https://github.com/littlefs-project/littlefs) - A little fail-safe filesystem designed for microcontrollers
* [TelegramMessenger/MTProxy](https://github.com/TelegramMessenger/MTProxy)
* [RubyMetric/chsrc](https://github.com/RubyMetric/chsrc) - chsrc 全平台通用换源工具与框架. Change Source everywhere for every software
* [haproxy/haproxy](https://github.com/haproxy/haproxy) - HAProxy Load Balancer's development branch (mirror of git.haproxy.org)
* [rxi/microui](https://github.com/rxi/microui) - A tiny immediate-mode UI library
* [espeak-ng/espeak-ng](https://github.com/espeak-ng/espeak-ng) - eSpeak NG is an open source speech synthesizer that supports more than hundred languages and accents.
* [akopytov/sysbench](https://github.com/akopytov/sysbench) - Scriptable database and system performance benchmark
* [s-macke/VoxelSpace](https://github.com/s-macke/VoxelSpace) - Terrain rendering algorithm in less than 20 lines of code
* [AFLplusplus/AFLplusplus](https://github.com/AFLplusplus/AFLplusplus) - The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more!
* [pawelsalawa/letos](https://github.com/pawelsalawa/letos) - A free, open source, multi-platform SQLite database manager.
* [beanstalkd/beanstalkd](https://github.com/beanstalkd/beanstalkd) - Beanstalk is a simple, fast work queue.
* [fulldecent/system-bus-radio](https://github.com/fulldecent/system-bus-radio) - Transmits AM radio on computers without radio transmitting hardware.
* [LumaTeam/Luma3DS](https://github.com/LumaTeam/Luma3DS) - Nintendo 3DS "Custom Firmware"
* [olikraus/u8g2](https://github.com/olikraus/u8g2) - U8glib library for monochrome displays, version 2
* [peng-zhihui/HelloWord-Keyboard](https://github.com/peng-zhihui/HelloWord-Keyboard)
* [pwn20wndstuff/Undecimus](https://github.com/pwn20wndstuff/Undecimus) - unc0ver jailbreak for iOS 11.0 - 12.4
* [rizonesoft/Notepad3](https://github.com/rizonesoft/Notepad3) - Notepad like text editor based on the Scintilla source code. Notepad3 based on code from Notepad2 and MiniPath on code from metapath. Download Notepad3:
* [OISF/suricata](https://github.com/OISF/suricata) - Suricata is a network Intrusion Detection System, Intrusion Prevention System and Network Security Monitoring engine developed by the OISF and the Suricata community.
* [opa334/Dopamine](https://github.com/opa334/Dopamine) - Dopamine is a semi-untethered jailbreak for iOS 15 to 26(.0.1)
* [uber/h3](https://github.com/uber/h3) - Hexagonal hierarchical geospatial indexing system
* [palera1n/palera1n](https://github.com/palera1n/palera1n) - Jailbreak for A8 through A11, T2 devices, on iOS/iPadOS/tvOS 15.0, bridgeOS 5.0 and higher.
* [nodejs/http-parser](https://github.com/nodejs/http-parser) - http request/response parser for c *(archived)*
* [machyve/xhyve](https://github.com/machyve/xhyve) - xhyve, a lightweight OS X virtualization solution
* [GNOME/gimp](https://github.com/GNOME/gimp) - Read-only mirror of https://gitlab.gnome.org/GNOME/gimp
* [zmap/zmap](https://github.com/zmap/zmap) - ZMap is a fast single packet network scanner designed for Internet-wide network surveys.
* [Provenance-Emu/Provenance](https://github.com/Provenance-Emu/Provenance) - iOS & tvOS multi-emulator frontend, supporting various Atari, Bandai, NEC, Nintendo, Sega, SNK and Sony console systems… Get Started: https://wiki.provenance-emu.com |
* [axboe/fio](https://github.com/axboe/fio) - Flexible I/O Tester
* [winfsp/sshfs-win](https://github.com/winfsp/sshfs-win) - SSHFS For Windows
* [nelhage/reptyr](https://github.com/nelhage/reptyr) - Reparent a running program to a new terminal
* [PufferAI/PufferLib](https://github.com/PufferAI/PufferLib) - Puffing up reinforcement learning
* [nanomsg/nanomsg](https://github.com/nanomsg/nanomsg) - nanomsg library
* [FASTSHIFT/X-TRACK](https://github.com/FASTSHIFT/X-TRACK) - A GPS bicycle speedometer that supports offline maps and track recording
* [erincatto/box3d](https://github.com/erincatto/box3d) - Box3D is a 3D physics engine for games
* [sparklemotion/nokogiri](https://github.com/sparklemotion/nokogiri) - Nokogiri (鋸) makes it easy and painless to work with XML and HTML from Ruby.
* [lmarzen/esp32-weather-epd](https://github.com/lmarzen/esp32-weather-epd) - A low-power E-Paper weather display powered by an ESP32 microcontroller. Utilizes the OpenWeatherMap API.
* [microsoft/WinObjC](https://github.com/microsoft/WinObjC) - Objective-C for Windows *(archived)*
* [JoeDog/siege](https://github.com/JoeDog/siege) - Siege is an http load tester and benchmarking utility
* [google/ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy) - A DevTools proxy (Chrome Remote Debugging Protocol) for iOS devices (Safari Remote Web Inspector).
* [RMerl/asuswrt-merlin.ng](https://github.com/RMerl/asuswrt-merlin.ng) - Third party firmware for Asus routers (newer codebase)
* [bellard/mquickjs](https://github.com/bellard/mquickjs) - Public repository of the Micro QuickJS Javascript Engine
* [guanzhi/GmSSL](https://github.com/guanzhi/GmSSL) - 支持国密SM2/SM3/SM4/SM9/SSL的密码工具箱
* [sharpbracket/redshift](https://github.com/sharpbracket/redshift) - Redshift adjusts the color temperature of your screen according to your surroundings. This may help your eyes hurt less if you are working in front of the screen at night. *(archived)*
* [libfuse/libfuse](https://github.com/libfuse/libfuse) - The reference implementation of the Linux FUSE (Filesystem in Userspace) interface
* [peng-zhihui/HDMI-PI](https://github.com/peng-zhihui/HDMI-PI) - 我设计的一个HDMI转MIPI模块，可以用于驱动各种手机屏幕当显示器用。
* [tmate-io/tmate](https://github.com/tmate-io/tmate) - Instant Terminal Sharing
* [nesbox/TIC-80](https://github.com/nesbox/TIC-80) - TIC-80 is a fantasy computer for making, playing and sharing tiny games.
* [wasm-micro-runtime/wasm-micro-runtime](https://github.com/wasm-micro-runtime/wasm-micro-runtime) - WebAssembly Micro Runtime (WAMR)
* [vk-com/kphp-kdb](https://github.com/vk-com/kphp-kdb) - VK-KittenPHP/DB/Engine suite
* [id-Software/Quake](https://github.com/id-Software/Quake) - Quake GPL Source Release
* [RPISEC/MBE](https://github.com/RPISEC/MBE) - Course materials for Modern Binary Exploitation by RPISEC
* [remzi-arpacidusseau/ostep-projects](https://github.com/remzi-arpacidusseau/ostep-projects) - Projects for an undergraduate OS course
* [RfidResearchGroup/proxmark3](https://github.com/RfidResearchGroup/proxmark3) - Iceman Fork - Proxmark3
* [Meituan-Dianping/Logan](https://github.com/Meituan-Dianping/Logan) - Logan is a lightweight case logging system based on mobile platform.
* [FeralInteractive/gamemode](https://github.com/FeralInteractive/gamemode) - Optimise Linux system performance on demand
* [tinyproxy/tinyproxy](https://github.com/tinyproxy/tinyproxy) - tinyproxy - a light-weight HTTP/HTTPS proxy daemon for POSIX operating systems
* [TsudaKageyu/minhook](https://github.com/TsudaKageyu/minhook) - The Minimalistic x86/x64 API Hooking Library for Windows
* [wszqkzqk/deepin-wine-ubuntu](https://github.com/wszqkzqk/deepin-wine-ubuntu) - Deepin Wine for Ubuntu/Debian *(archived)*
* [MrGlockenspiel/activate-linux](https://github.com/MrGlockenspiel/activate-linux) - The "Activate Windows" watermark ported to Linux
* [xufuji456/FFmpegAndroid](https://github.com/xufuji456/FFmpegAndroid) - FFmpeg实现视频裁剪、水印、转码、编解码、转Gif动图；FFmpeg本地推流、H264与RTMP实时推流直播；OpenGL滤镜特效，视频拍摄。音视频学习路线，音视频知识总结、流媒体协议
* [arthenica/ffmpeg-kit](https://github.com/arthenica/ffmpeg-kit) - FFmpeg Kit for applications. Supports Android, Flutter, iOS, Linux, macOS, React Native and tvOS. Supersedes MobileFFmpeg, flutter_ffmpeg and react-native-ffmpeg. *(archived)*
* [jedisct1/dsvpn](https://github.com/jedisct1/dsvpn) - A Dead Simple VPN.
* [Airblader/i3](https://github.com/Airblader/i3) - A fork of the i3 window manager with gaps and some other features. :warning: i3-gaps has been merged into i3. *(archived)*
* [edenhill/kcat](https://github.com/edenhill/kcat) - Generic command line non-JVM Apache Kafka producer and consumer
* [LuaJIT/LuaJIT](https://github.com/LuaJIT/LuaJIT) - Mirror of the LuaJIT git repository
* [memovai/mimiclaw](https://github.com/memovai/mimiclaw) - MimiClaw: Harness on a $5 chip. No OS(Linux). No Node.js. No Mac mini. No Raspberry Pi. No VPS. Hardware agents OS.
* [seL4/seL4](https://github.com/seL4/seL4) - The seL4 microkernel
* [mozilla/mozjpeg](https://github.com/mozilla/mozjpeg) - Improved JPEG encoder.
* [memononen/nanovg](https://github.com/memononen/nanovg) - Antialiased 2D vector drawing library on top of OpenGL for UI and visualizations.
* [kbengine/kbengine](https://github.com/kbengine/kbengine) - A MMOG engine of server.
* [andmarti1424/sc-im](https://github.com/andmarti1424/sc-im) - sc-im - Spreadsheet Calculator Improvised -- An ncurses spreadsheet program for terminal
* [gnif/LookingGlass](https://github.com/gnif/LookingGlass) - An extremely low latency KVMFR (KVM FrameRelay) implementation for guests with VGA PCI Passthrough.
* [eradman/entr](https://github.com/eradman/entr) - Run arbitrary commands when files change
* [LongSoft/UEFITool](https://github.com/LongSoft/UEFITool) - UEFI firmware image viewer and editor
* [SecWiki/linux-kernel-exploits](https://github.com/SecWiki/linux-kernel-exploits) - linux-kernel-exploits Linux平台提权漏洞集合
* [ptitSeb/box64](https://github.com/ptitSeb/box64) - Box64 - Linux Userspace x86_64 Emulator with a twist, targeted at ARM64, RV64 and LoongArch Linux devices
* [Meituan-Dianping/SQLAdvisor](https://github.com/Meituan-Dianping/SQLAdvisor) - 输入SQL，输出索引优化建议
* [mruby/mruby](https://github.com/mruby/mruby) - Lightweight Ruby
* [baidu/dperf](https://github.com/baidu/dperf) - dperf: High-Performance Network Load Testing Tool Based on DPDK
* [ZipArchive/ZipArchive](https://github.com/ZipArchive/ZipArchive) - ZipArchive is a simple utility class for zipping and unzipping files on iOS, macOS and tvOS.
* [justinfrankel/licecap](https://github.com/justinfrankel/licecap) - LICEcap simple animated screen capture tool for Windows and OS X
* [nginx/unit](https://github.com/nginx/unit) - NGINX Unit - universal web app server - a lightweight and versatile open source server that simplifies the application stack by natively executing application code across eight different programming language runtimes. *(archived)*
* [zeldaret/oot](https://github.com/zeldaret/oot) - Decompilation of The Legend of Zelda: Ocarina of Time
* [Netflix/vmaf](https://github.com/Netflix/vmaf) - Perceptual video quality assessment based on multi-method fusion.
* [facebook/fishhook](https://github.com/facebook/fishhook) - A library that enables dynamically rebinding symbols in Mach-O binaries running on iOS.
* [bol-van/zapret2](https://github.com/bol-van/zapret2) - anti-dpi software
* [portapack-mayhem/mayhem-firmware](https://github.com/portapack-mayhem/mayhem-firmware) - The firmware for the HackRF+PortaPack H1/H2/H4/H4M
* [CameraKit/camerakit-android](https://github.com/CameraKit/camerakit-android) - Library for Android Camera 1 and 2 APIs. Massively increase stability and reliability of photo and video capture on all Android devices.
* [P-H-C/phc-winner-argon2](https://github.com/P-H-C/phc-winner-argon2) - The password hash Argon2, winner of PHC
* [vercel-labs/zerolang](https://github.com/vercel-labs/zerolang) - The Programming Language for Agents
* [HarbourMasters/Shipwright](https://github.com/HarbourMasters/Shipwright)
* [facebookincubator/katran](https://github.com/facebookincubator/katran) - A high performance layer 4 load balancer
* [ExpressLRS/ExpressLRS](https://github.com/ExpressLRS/ExpressLRS) - High Performance Open Source Radio Control Link
* [DualCoder/vgpu_unlock](https://github.com/DualCoder/vgpu_unlock) - Unlock vGPU functionality for consumer grade GPUs.
* [mpc-hc/mpc-hc](https://github.com/mpc-hc/mpc-hc) - MPC-HC's main repository. For support use our Trac: https://trac.mpc-hc.org/ *(archived)*
* [visit1985/mdp](https://github.com/visit1985/mdp) - A command-line based markdown presentation tool.
* [pervognsen/bitwise](https://github.com/pervognsen/bitwise) - Bitwise is an educational project where we create the software/hardware stack for a computer from scratch. *(archived)*
* [martin-ger/esp_wifi_repeater](https://github.com/martin-ger/esp_wifi_repeater) - A full functional WiFi NAT Router (and now also a WiFi Repeater)
* [u-boot/u-boot](https://github.com/u-boot/u-boot) - "Das U-Boot" Source Tree
* [hpjansson/chafa](https://github.com/hpjansson/chafa) - 📺🗿 Terminal graphics for the 21st century.
* [mjolnirapp/mjolnir](https://github.com/mjolnirapp/mjolnir) - Lightweight automation and productivity app for OS X
* [RamonUnch/AltSnap](https://github.com/RamonUnch/AltSnap) - Maintained continuation of Stefan Sundin's AltDrag
* [RsyncProject/rsync](https://github.com/RsyncProject/rsync) - An open source utility that provides fast incremental file transfer. It also has useful features for backup and restore operations among many other use cases.
* [stlink-org/stlink](https://github.com/stlink-org/stlink) - Open source STM32 MCU programming toolset
* [clibs/clib](https://github.com/clibs/clib) - Package manager for the C programming language.
* [signalwire/freeswitch](https://github.com/signalwire/freeswitch) - FreeSWITCH is a Software Defined Telecom Stack enabling the digital transformation from proprietary telecom switches to a versatile software implementation that runs on any commodity hardware. From a Raspberry PI to a multi-core server, FreeSWITCH can unlock the telecommunications potential of any device.
* [yrutschle/sslh](https://github.com/yrutschle/sslh) - Applicative Protocol Multiplexer (e.g. share SSH and HTTPS on the same port)
* [ading2210/linuxpdf](https://github.com/ading2210/linuxpdf) - Linux running inside a PDF file via a RISC-V emulator
* [tectonic-typesetting/tectonic](https://github.com/tectonic-typesetting/tectonic) - A modernized, complete, self-contained TeX/LaTeX engine, powered by XeTeX and TeXLive.
* [vmg/redcarpet](https://github.com/vmg/redcarpet) - The safe Markdown parser, reloaded.
* [binbyu/Reader](https://github.com/binbyu/Reader) - A win32 txt file reader
* [hengyoush/kyanos](https://github.com/hengyoush/kyanos) - Kyanos is a networking analysis tool using eBPF. It can visualize the time packets spend in the kernel, capture requests/responses, makes troubleshooting more efficient.
* [XProger/OpenLara](https://github.com/XProger/OpenLara) - Classic Tomb Raider open-source engine
* [flatpak/flatpak](https://github.com/flatpak/flatpak) - Linux application sandboxing and distribution framework
* [ossec/ossec-hids](https://github.com/ossec/ossec-hids) - OSSEC is an Open Source Host-based Intrusion Detection System that performs log analysis, file integrity checking, policy monitoring, rootkit detection, real-time alerting and active response.
* [b4winckler/macvim](https://github.com/b4winckler/macvim) - Vim - the text editor - for Mac OS X
* [easychen/pushdeer](https://github.com/easychen/pushdeer) - 开放源码的无App推送服务，iOS14+扫码即用。亦支持快应用/iOS和Mac客户端、Android客户端、自制设备
* [V4bel/dirtyfrag](https://github.com/V4bel/dirtyfrag)
* [cilium/tetragon](https://github.com/cilium/tetragon) - eBPF-based Security Observability and Runtime Enforcement
* [google/pebble](https://github.com/google/pebble) - This is the latest version of the internal repository from Pebble Technology providing the software to run on Pebble watches. Proprietary source code has been removed from this repository and it will not compile as-is. This is for information only.
* [raspberrypi/pico-sdk](https://github.com/raspberrypi/pico-sdk)
* [LiteOS/LiteOS](https://github.com/LiteOS/LiteOS) - code and manual
* [Bodmer/TFT_eSPI](https://github.com/Bodmer/TFT_eSPI) - Arduino and PlatformIO IDE compatible TFT library optimised for the Raspberry Pi Pico (RP2040), STM32, ESP8266 and ESP32 that supports different driver chips
* [openvenues/libpostal](https://github.com/openvenues/libpostal) - A C library for parsing/normalizing street addresses around the world. Powered by statistical NLP and open geo data.
* [ARMmbed/mbed-os](https://github.com/ARMmbed/mbed-os) - Arm Mbed OS is a platform operating system designed for the internet of things
* [jpmens/jo](https://github.com/jpmens/jo) - JSON output from a shell
* [cpq/bare-metal-programming-guide](https://github.com/cpq/bare-metal-programming-guide) - A bare metal programming guide (ARM microcontrollers)
* [NLnetLabs/unbound](https://github.com/NLnetLabs/unbound) - Unbound is a validating, recursive, and caching DNS resolver.
* [google/wuffs](https://github.com/google/wuffs) - Wrangling Untrusted File Formats Safely
* [koute/bytehound](https://github.com/koute/bytehound) - A memory profiler for Linux.
* [apache/age](https://github.com/apache/age) - Graph database optimized for fast analysis and real-time data processing. It is provided as an extension to PostgreSQL.
* [yshui/picom](https://github.com/yshui/picom) - A lightweight compositor for X11 with animation support
* [open-sdr/openwifi](https://github.com/open-sdr/openwifi) - open-source IEEE 802.11 WiFi baseband FPGA (chip) design: driver, software
* [X11Libre/xserver](https://github.com/X11Libre/xserver) - XLibre Xserver
* [foobnix/LibreraReader](https://github.com/foobnix/LibreraReader) - Book Reader for Android
* [86Box/86Box](https://github.com/86Box/86Box) - Emulator of x86-based machines.
* [microshow/RxFFmpeg](https://github.com/microshow/RxFFmpeg) - 🔥💥RxFFmpeg 是基于 ( FFmpeg 4.0 + X264 + mp3lame + fdk-aac + opencore-amr + openssl ) 编译的适用于 Android 平台的音视频编辑、视频剪辑的快速处理框架，包含以下功能：视频拼接，转码，压缩，裁剪，片头片尾，分离音视频，变速，添加静态贴纸和gif动态贴纸，添加字幕，添加滤镜，添加背景音乐，加速减速视频，倒放音视频，音频裁剪，变声，混音，图片合成视频，视频解码图片，抖音首页，视频播放器及支持 OpenSSL https 等主流特色功能
* [snesrev/zelda3](https://github.com/snesrev/zelda3)
* [microsoft/ProcMon-for-Linux](https://github.com/microsoft/ProcMon-for-Linux) - A Linux version of the Procmon Sysinternals tool
* [xroche/httrack](https://github.com/xroche/httrack) - HTTrack Website Copier, copy websites to your computer (Official repository)
* [TechUnRestricted/WinDiskWriter](https://github.com/TechUnRestricted/WinDiskWriter) - 🖥 Windows Bootable USB creator for macOS. 🛠 Patches Windows 11 to bypass TPM and Secure Boot requirements. 👾 UEFI & Legacy Support
* [termux/termux-x11](https://github.com/termux/termux-x11) - Termux X-server add-on.
* [TheWover/donut](https://github.com/TheWover/donut) - Generates x86, x64, or AMD64+x86 position-independent shellcode that loads .NET Assemblies, PE files, and other Windows payloads from memory and runs them with parameters
* [dankamongmen/notcurses](https://github.com/dankamongmen/notcurses) - blingful character graphics/TUI library. definitely not curses.
* [session-replay-tools/tcpcopy](https://github.com/session-replay-tools/tcpcopy) - An online request replication and TCP stream replay tool, ideal for real testing, performance testing, stability testing, stress testing, load testing, smoke testing, and more.
* [nanomsg/nng](https://github.com/nanomsg/nng) - nanomsg-next-generation -- light-weight brokerless messaging
* [giltene/wrk2](https://github.com/giltene/wrk2) - A constant throughput, correct latency recording variant of wrk
* [alibaba/AliOS-Things](https://github.com/alibaba/AliOS-Things) - 面向IoT领域的、高可伸缩的物联网操作系统，可去官网了解更多信息https://www.aliyun.com/product/aliosthings
* [google/security-research](https://github.com/google/security-research) - This project hosts security advisories and their accompanying proof-of-concepts related to research conducted at Google which impact non-Google owned code.
* [Qihoo360/Atlas](https://github.com/Qihoo360/Atlas) - A high-performance and stable proxy for MySQL, it is developed by Qihoo's DBA and infrastructure team
* [riscv-collab/riscv-gnu-toolchain](https://github.com/riscv-collab/riscv-gnu-toolchain) - GNU toolchain for RISC-V, including GCC
* [matz/streem](https://github.com/matz/streem) - prototype of stream based programming language
* [webui-dev/webui](https://github.com/webui-dev/webui) - Use any web browser or WebView as GUI, with your preferred language in the backend and modern web technologies in the frontend, all in a lightweight portable library.
* [ntop/nDPI](https://github.com/ntop/nDPI) - Open Source Deep Packet Inspection Software Toolkit
* [F5OEO/rpitx](https://github.com/F5OEO/rpitx) - RF transmitter for Raspberry Pi
* [jakehilborn/displayplacer](https://github.com/jakehilborn/displayplacer) - macOS command line utility to configure multi-display resolutions and arrangements. Essentially XRandR for macOS.
* [taviso/loadlibrary](https://github.com/taviso/loadlibrary) - Porting Windows Dynamic Link Libraries to Linux
* [openrazer/openrazer](https://github.com/openrazer/openrazer) - Open source driver and user-space daemon to control Razer lighting and other features on GNU/Linux
* [torvalds/AudioNoise](https://github.com/torvalds/AudioNoise) - Random digital audio effects
* [FreeRTOS/FreeRTOS-Kernel](https://github.com/FreeRTOS/FreeRTOS-Kernel) - FreeRTOS kernel files only, submoduled into https://github.com/FreeRTOS/FreeRTOS and various other repos.
* [Aleksoid1978/MPC-BE](https://github.com/Aleksoid1978/MPC-BE) - MPC-BE – универсальный проигрыватель аудио и видеофайлов для операционной системы Windows.
* [coolwanglu/vim.js](https://github.com/coolwanglu/vim.js) - JavaScript port of Vim *(archived)*
* [libjpeg-turbo/libjpeg-turbo](https://github.com/libjpeg-turbo/libjpeg-turbo) - Main libjpeg-turbo repository
* [jdah/minecraft-weekend](https://github.com/jdah/minecraft-weekend) - Minecraft, but I made it in 48 hours.
* [DPDK/dpdk](https://github.com/DPDK/dpdk) - Data Plane Development Kit
* [Mzzopublic/C](https://github.com/Mzzopublic/C) - C语言
* [p2r3/bareiron](https://github.com/p2r3/bareiron) - Minimalist Minecraft server for memory-restrictive embedded systems
* [lakinduakash/linux-wifi-hotspot](https://github.com/lakinduakash/linux-wifi-hotspot) - Feature-rich wifi hotspot creator for Linux which provides both GUI and command-line interface. It is also able to create a hotspot using the same wifi card which is connected to an AP already ( Similar to Windows 10).
* [canonical/dqlite](https://github.com/canonical/dqlite) - Embeddable, replicated and fault-tolerant SQL engine.
* [nalgeon/sqlean](https://github.com/nalgeon/sqlean) - The ultimate set of SQLite extensions
* [libffi/libffi](https://github.com/libffi/libffi) - A portable foreign-function interface library.
* [pgbackrest/pgbackrest](https://github.com/pgbackrest/pgbackrest) - Reliable PostgreSQL Backup & Restore
* [antirez/linenoise](https://github.com/antirez/linenoise) - A small self-contained alternative to readline and libedit
* [iqiyi/xHook](https://github.com/iqiyi/xHook) - 🔥 A PLT hook library for Android native ELF.
* [pgbouncer/pgbouncer](https://github.com/pgbouncer/pgbouncer) - lightweight connection pooler for PostgreSQL
* [cboxdoerfer/fsearch](https://github.com/cboxdoerfer/fsearch) - A fast file search utility for Unix-like systems based on GTK3
* [albfan/miraclecast](https://github.com/albfan/miraclecast) - Connect external monitors to your system via Wifi-Display specification also known as Miracast
* [cmusphinx/pocketsphinx](https://github.com/cmusphinx/pocketsphinx) - A small speech recognizer
* [Gnucash/gnucash](https://github.com/Gnucash/gnucash) - GnuCash Double-Entry Accounting Program.
* [networkupstools/nut](https://github.com/networkupstools/nut) - The Network UPS Tools repository. UPS management protocol Informational RFC 9271 published by IETF at https://www.rfc-editor.org/info/rfc9271 Please star NUT on GitHub, this helps with sponsorships!
* [SchedMD/slurm](https://github.com/SchedMD/slurm) - Slurm: A Highly Scalable Workload Manager
* [ufrisk/MemProcFS](https://github.com/ufrisk/MemProcFS) - MemProcFS
* [kohler/gifsicle](https://github.com/kohler/gifsicle) - Create, manipulate, and optimize GIF images and animations
* [cnlohr/rawdrawandroid](https://github.com/cnlohr/rawdrawandroid) - Build android apps without any java, entirely in C and Make
* [dorianborian/sesame-robot](https://github.com/dorianborian/sesame-robot) - An open and affordable mini quadruped robot based on ESP32.
* [zsh-users/zsh](https://github.com/zsh-users/zsh) - Mirror of the Z shell source code repository.
* [blinker-iot/blinker-esp-idf](https://github.com/blinker-iot/blinker-esp-idf) - An IoT Solution,Blinker library for embedded hardware. Works with ESP8266, ESP32 (idf)
* [FRRouting/frr](https://github.com/FRRouting/frr) - The FRRouting Protocol Suite
* [eunomia-bpf/bpf-developer-tutorial](https://github.com/eunomia-bpf/bpf-developer-tutorial) - eBPF Developer Tutorial: Learning eBPF Step by Step with Examples
* [rfjakob/earlyoom](https://github.com/rfjakob/earlyoom) - earlyoom - Early OOM Daemon for Linux
* [OnionUI/Onion](https://github.com/OnionUI/Onion) - OS overhaul for Miyoo Mini and Mini+
* [cloudius-systems/osv](https://github.com/cloudius-systems/osv) - OSv, a new operating system for the cloud.
* [F-Stack/f-stack](https://github.com/F-Stack/f-stack) - F-Stack is an user space network development kit with high performance based on DPDK, FreeBSD TCP/IP stack and coroutine API.
* [NixOS/patchelf](https://github.com/NixOS/patchelf) - A small utility to modify the dynamic linker and RPATH of ELF executables
* [zmkfirmware/zmk](https://github.com/zmkfirmware/zmk) - ZMK Firmware Repository
* [v4l2loopback/v4l2loopback](https://github.com/v4l2loopback/v4l2loopback) - v4l2-loopback device
* [blinker-iot/blinker-nRF52](https://github.com/blinker-iot/blinker-nRF52) - Base nordic nrf5 SDK V16.0.0 and nrf5 mesh SDK V4.0.0
* [gali8/Tesseract-OCR-iOS](https://github.com/gali8/Tesseract-OCR-iOS) - Tesseract OCR iOS is a Framework for iOS7+, compiled also for armv7s and arm64.
* [iNavFlight/inav](https://github.com/iNavFlight/inav) - INAV: Navigation-enabled flight control software
* [fw876/helloworld](https://github.com/fw876/helloworld)
* [google/AFL](https://github.com/google/AFL) - american fuzzy lop - a security-oriented fuzzer *(archived)*
* [orioledb/orioledb](https://github.com/orioledb/orioledb) - OrioleDB – building a modern cloud-native storage engine (... and solving some PostgreSQL wicked problems)
* [zserge/jsmn](https://github.com/zserge/jsmn) - Jsmn is a world fastest JSON parser/tokenizer. This is the official repo replacing the old one at Bitbucket
* [isec-tugraz/meltdown](https://github.com/isec-tugraz/meltdown) - This repository contains several applications, demonstrating the Meltdown bug. *(archived)*
* [wine-mirror/wine](https://github.com/wine-mirror/wine)
* [huntergregal/mimipenguin](https://github.com/huntergregal/mimipenguin) - A tool to dump the login password from the current linux user
* [BasedHardware/OpenGlass](https://github.com/BasedHardware/OpenGlass) - Turn any glasses into AI-powered smart glasses
* [samyk/magspoof](https://github.com/samyk/magspoof) - A portable device that can spoof/emulate any magnetic stripe, credit card or hotel card "wirelessly", even on standard magstripe (non-NFC/RFID) readers. It can disable Chip&PIN and predict AMEX card numbers with 100% accuracy.
* [tanersener/mobile-ffmpeg](https://github.com/tanersener/mobile-ffmpeg) - FFmpeg for Android, iOS and tvOS. Not maintained anymore. Superseded by FFmpegKit. *(archived)*
* [tmk/tmk_keyboard](https://github.com/tmk/tmk_keyboard) - Keyboard firmwares for Atmel AVR and Cortex-M
* [xemu-project/xemu](https://github.com/xemu-project/xemu) - Original Xbox Emulator for Windows, macOS, and Linux (Active Development)
* [geohot/qira](https://github.com/geohot/qira) - QEMU Interactive Runtime Analyser
* [apache/httpd](https://github.com/apache/httpd) - Mirror of Apache HTTP Server. Issues: http://issues.apache.org
* [armory3d/armorpaint](https://github.com/armory3d/armorpaint) - Graphics Creation Tools
* [varnishcache/varnish-cache](https://github.com/varnishcache/varnish-cache) - Varnish Cache source code repository *(archived)*
* [dekuNukem/daytripper](https://github.com/dekuNukem/daytripper) - Hide-My-Windows Laser Tripwire
* [HyperDbg/HyperDbg](https://github.com/HyperDbg/HyperDbg) - State-of-the-art native debugging tools
* [zhaojh329/rtty](https://github.com/zhaojh329/rtty) - 🐛 Access your device from anywhere via the web.
* [apache/nuttx](https://github.com/apache/nuttx) - Apache NuttX is a mature, real-time embedded operating system (RTOS)
* [icholy/ttygif](https://github.com/icholy/ttygif) - Convert terminal recordings to animated gifs
* [openvswitch/ovs](https://github.com/openvswitch/ovs) - Open vSwitch
* [surge-synthesizer/surge](https://github.com/surge-synthesizer/surge) - Synthesizer plug-in (previously released as Vember Audio Surge)
* [schwabe/ics-openvpn](https://github.com/schwabe/ics-openvpn) - OpenVPN for Android
* [timescale/pg_textsearch](https://github.com/timescale/pg_textsearch) - PostgreSQL extension for BM25 relevance-ranked full-text search. Postgres OSS licensed.
* [a0rtega/pafish](https://github.com/a0rtega/pafish) - Pafish is a testing tool that uses different techniques to detect virtual machines and malware analysis environments in the same way that malware families do *(archived)*
* [samyk/pwnat](https://github.com/samyk/pwnat) - The only tool/technique to punch holes through firewalls/NATs where multiple clients & server can be behind separate NATs without any 3rd party involvement. Pwnat is a newly developed technique, exploiting a property of NAT translation tables, with no 3rd party, port forwarding, DMZ, DNS, router admin requirements, STUN/TURN/UPnP/ICE, or spoofing.
* [ming1016/study](https://github.com/ming1016/study) - 学习记录
* [raspberrypi/pico-examples](https://github.com/raspberrypi/pico-examples)
* [PerformanC/ReZygisk](https://github.com/PerformanC/ReZygisk) - Transparent implementation of Zygisk.
* [citusdata/pg_cron](https://github.com/citusdata/pg_cron) - Run periodic jobs in PostgreSQL
* [openbsd/src](https://github.com/openbsd/src) - Read-only git conversion of OpenBSD's official CVS src repository. Pull requests not accepted - send diffs to the tech@ mailing list.
* [rizinorg/rizin](https://github.com/rizinorg/rizin) - UNIX-like reverse engineering framework and command-line toolset.
* [acidanthera/Lilu](https://github.com/acidanthera/Lilu) - Arbitrary kext and process patching on macOS
* [jordansissel/xdotool](https://github.com/jordansissel/xdotool) - fake keyboard/mouse input, window management, and more
* [unikraft/unikraft](https://github.com/unikraft/unikraft) - A next-generation cloud native kernel designed to unlock best-in-class performance, security primitives and efficiency savings.
* [OpenKinect/libfreenect](https://github.com/OpenKinect/libfreenect) - Drivers and libraries for the Xbox Kinect device on Windows, Linux, and OS X
* [cilium/pwru](https://github.com/cilium/pwru) - Packet, where are you? -- eBPF-based Linux kernel networking debugger
* [winscp/winscp](https://github.com/winscp/winscp) - WinSCP is a popular free file manager for Windows supporting SFTP, FTP, FTPS, SCP, S3, WebDAV and local-to-local file transfers. A powerful tool to enhance your productivity with a user-friendly interface and automation options like .NET assembly.
* [ptitSeb/box86](https://github.com/ptitSeb/box86) - Box86 - Linux Userspace x86 Emulator with a twist, targeted at ARM Linux devices
* [FelixKratz/JankyBorders](https://github.com/FelixKratz/JankyBorders) - A lightweight window border system for macOS
* [dekuNukem/Nintendo_Switch_Reverse_Engineering](https://github.com/dekuNukem/Nintendo_Switch_Reverse_Engineering) - A look at inner workings of Joycon and Nintendo Switch
* [StuckAtPrototype/Racer](https://github.com/StuckAtPrototype/Racer)
* [sypstraw/rpi4-osdev](https://github.com/sypstraw/rpi4-osdev) - Tutorial: Writing a "bare metal" operating system for Raspberry Pi 4
* [rmtheis/tess-two](https://github.com/rmtheis/tess-two) - Fork of Tesseract Tools for Android *(archived)*
* [axboe/liburing](https://github.com/axboe/liburing) - Library providing helpers for the Linux kernel io_uring support
* [Chikage0o0/Linux-NetSpeed](https://github.com/Chikage0o0/Linux-NetSpeed) - 将Linux现常用的网络加速集成在一起 *(archived)*
* [DavidXanatos/TaskExplorer](https://github.com/DavidXanatos/TaskExplorer) - Power full Task Manager
* [fastos/fastsocket](https://github.com/fastos/fastsocket) - Fastsocket is a highly scalable socket and its underlying networking implementation of Linux kernel. With the straight linear scalability, Fastsocket can provide extremely good performance in multicore machines. In addition, it is very easy to use and maintain. As a result, it has been deployed in the production environment of SINA.
* [moby/hyperkit](https://github.com/moby/hyperkit) - A toolkit for embedding hypervisor capabilities in your application
* [joncampbell123/dosbox-x](https://github.com/joncampbell123/dosbox-x) - DOSBox-X fork of the DOSBox project
* [quickjs-ng/quickjs](https://github.com/quickjs-ng/quickjs) - QuickJS, the Next Generation: a mighty JavaScript engine
* [linw7/Skill-Tree](https://github.com/linw7/Skill-Tree) - 🐼 准备秋招，欢迎来树上取果实
* [geany/geany](https://github.com/geany/geany) - A fast and lightweight IDE
* [Limine-Bootloader/Limine](https://github.com/Limine-Bootloader/Limine) - Modern, secure, portable, multiprotocol bootloader and boot manager.
* [littlekernel/lk](https://github.com/littlekernel/lk) - LK embedded kernel
* [Lienol/openwrt](https://github.com/Lienol/openwrt) - Lienol's Modified OpenWrt source
* [spdk/spdk](https://github.com/spdk/spdk) - Storage Performance Development Kit
* [psycopg/psycopg2](https://github.com/psycopg/psycopg2) - PostgreSQL database adapter for the Python programming language
* [AlexAltea/orbital](https://github.com/AlexAltea/orbital) - Experimental PlayStation 4 emulator
* [libopencm3/libopencm3](https://github.com/libopencm3/libopencm3) - Open source ARM Cortex-M microcontroller library
* [blechschmidt/massdns](https://github.com/blechschmidt/massdns) - A high-performance DNS stub resolver for bulk lookups and reconnaissance (subdomain enumeration)
* [sandboxie/sandboxie](https://github.com/sandboxie/sandboxie) - The Sandboxie application
* [nuta/operating-system-in-1000-lines](https://github.com/nuta/operating-system-in-1000-lines) - Writing an OS in 1,000 lines.
* [darkk/redsocks](https://github.com/darkk/redsocks) - transparent TCP-to-proxy redirector
* [libarchive/libarchive](https://github.com/libarchive/libarchive) - Multi-format archive and compression library
* [yhzhang0128/egos-2000](https://github.com/yhzhang0128/egos-2000) - Envision a future where everyone can read all the code of an educational operating system.
* [wishstudio/flinux](https://github.com/wishstudio/flinux) - Foreign LINUX - Run unmodified Linux applications inside Windows.
* [mangowm/mango](https://github.com/mangowm/mango) - Practical and Powerful wayland compositor (dwm but wayland)
* [nmap/npcap](https://github.com/nmap/npcap) - Nmap Project's Windows packet capture and transmission library
* [openai/retro](https://github.com/openai/retro) - Retro Games in Gym *(archived)*
* [apple-oss-distributions/xnu](https://github.com/apple-oss-distributions/xnu)
* [espressif/ESP8266_RTOS_SDK](https://github.com/espressif/ESP8266_RTOS_SDK) - Latest ESP8266 SDK based on FreeRTOS, esp-idf style.
* [bryanthaboi/gen1recomp](https://github.com/bryanthaboi/gen1recomp) - Gen1Recomp - A native Lua / LÖVE2D recreation of Gen 1 and 2 Poke
* [microsoft/ebpf-for-windows](https://github.com/microsoft/ebpf-for-windows) - eBPF implementation that runs on top of Windows
* [34736384/genshin-fps-unlock](https://github.com/34736384/genshin-fps-unlock) - unlocks the 60 fps cap
* [yarrick/pingfs](https://github.com/yarrick/pingfs) - Stores your data in ICMP ping packets
* [unbit/uwsgi](https://github.com/unbit/uwsgi) - uWSGI application server container
* [Proxmark/proxmark3](https://github.com/Proxmark/proxmark3) - Proxmark 3
* [vanhoefm/krackattacks-scripts](https://github.com/vanhoefm/krackattacks-scripts)
* [eclipse-threadx/threadx](https://github.com/eclipse-threadx/threadx) - Eclipse ThreadX is an advanced real-time operating system (RTOS) designed specifically for deeply embedded applications.
* [gtworek/PSBits](https://github.com/gtworek/PSBits) - Simple (relatively) things allowing you to dig a bit deeper than usual.
* [ireader/media-server](https://github.com/ireader/media-server) - RTSP/RTP/RTMP/FLV/HLS/MPEG-TS/MPEG-PS/MPEG-DASH/MP4/fMP4/MKV/WebM
* [Stichting-MINIX-Research-Foundation/minix](https://github.com/Stichting-MINIX-Research-Foundation/minix) - Official MINIX sources - Automatically replicated from gerrit.minix3.org
* [GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator](https://github.com/GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator) - Easy to integrate Vulkan memory allocation library
* [answer-huang/dSYMTools](https://github.com/answer-huang/dSYMTools) - dSYM analyze
* [leafo/moonscript](https://github.com/leafo/moonscript) - :crescent_moon: A language that compiles to Lua
* [osqzss/gps-sdr-sim](https://github.com/osqzss/gps-sdr-sim) - Software-Defined GPS Signal Simulator *(archived)*
* [mabeijianxi/small-video-record](https://github.com/mabeijianxi/small-video-record) - 利用FFmpeg视频录制微信小视频与其压缩处理
* [krakjoe/pthreads](https://github.com/krakjoe/pthreads) - Threading for PHP - Share Nothing, Do Everything :) *(archived)*
* [documentdb/documentdb](https://github.com/documentdb/documentdb) - MongoDB-compatible database engine for cloud-native and open-source workloads. Built for scalability, performance, and developer productivity.
* [jp9000/OBS](https://github.com/jp9000/OBS) - Open Broadcaster Software (Deprecated: See OBS Studio repository instead)
* [zigzap/zap](https://github.com/zigzap/zap) - blazingly fast backends in zig
* [emojicode/emojicode](https://github.com/emojicode/emojicode) - 😀😜🔂 World’s only programming language that’s bursting with emojis
* [vedderb/bldc](https://github.com/vedderb/bldc) - The VESC motor control firmware
* [otya128/winevdm](https://github.com/otya128/winevdm) - 16-bit Windows (Windows 1.x, 2.x, 3.0, 3.1, etc.) on 64-bit Windows
* [axel-download-accelerator/axel](https://github.com/axel-download-accelerator/axel) - Lightweight CLI download accelerator
* [hufrea/byedpi](https://github.com/hufrea/byedpi) - Bypass DPI
* [AltraMayor/f3](https://github.com/AltraMayor/f3) - F3 - Fight Flash Fraud
* [bvschaik/julius](https://github.com/bvschaik/julius) - An open source re-implementation of Caesar III
* [libAudioFlux/audioFlux](https://github.com/libAudioFlux/audioFlux) - A library for audio and music analysis, feature extraction.
* [cuber/ngx_http_google_filter_module](https://github.com/cuber/ngx_http_google_filter_module) - Nginx Module for Google Mirror
* [stephenfewer/ReflectiveDLLInjection](https://github.com/stephenfewer/ReflectiveDLLInjection) - Reflective DLL injection is a library injection technique in which the concept of reflective programming is employed to perform the loading of a library from memory into a host process.
* [ZSWatch/ZSWatch](https://github.com/ZSWatch/ZSWatch) - ZSWatch - the Open Source Zephyr™ based Smartwatch, including both HW and FW.
* [hanwckf/rt-n56u](https://github.com/hanwckf/rt-n56u) - Padavan
* [atc1441/ATC_MiThermometer](https://github.com/atc1441/ATC_MiThermometer) - Custom firmware for the Xiaomi Thermometer LYWSD03MMC and Telink Flasher via USB to Serial converter
* [airockchip/rknn-toolkit2](https://github.com/airockchip/rknn-toolkit2)
* [johnfanv2/LenovoLegionLinux](https://github.com/johnfanv2/LenovoLegionLinux) - Driver and tools for controlling Lenovo Legion laptops in Linux including fan control and power mode.
* [traviscross/mtr](https://github.com/traviscross/mtr) - Official repository for mtr, a network diagnostic tool
* [id-Software/Quake-2](https://github.com/id-Software/Quake-2) - Quake 2 GPL Source Release
* [WiringPi/WiringPi](https://github.com/WiringPi/WiringPi) - The arguably fastest GPIO Library for the Raspberry Pi
* [mtoyoda/sl](https://github.com/mtoyoda/sl) - SL(1): Cure your bad habit of mistyping
* [zlgopen/awtk](https://github.com/zlgopen/awtk) - AWTK = Toolkit AnyWhere(a cross-platform embedded GUI)
* [intel/haxm](https://github.com/intel/haxm) - Intel® Hardware Accelerated Execution Manager (Intel® HAXM) *(archived)*
* [GStreamer/gstreamer](https://github.com/GStreamer/gstreamer) - GStreamer open-source multimedia framework
* [gpac/gpac](https://github.com/gpac/gpac) - GPAC Ultramedia OSS for Video Streaming & Next-Gen Multimedia Transcoding, Packaging & Delivery
* [EasyHook/EasyHook](https://github.com/EasyHook/EasyHook) - EasyHook - The reinvention of Windows API Hooking
* [basil00/WinDivert](https://github.com/basil00/WinDivert) - WinDivert: Windows Packet Divert
* [pwmt/zathura](https://github.com/pwmt/zathura) - Document viewer
* [lsalzman/enet](https://github.com/lsalzman/enet) - ENet reliable UDP networking library
* [Legrandin/pycryptodome](https://github.com/Legrandin/pycryptodome) - A self-contained cryptographic library for Python
* [DhavalKapil/icmptunnel](https://github.com/DhavalKapil/icmptunnel) - Transparently tunnel your IP traffic through ICMP echo and reply packets.
* [jacksonliam/mjpg-streamer](https://github.com/jacksonliam/mjpg-streamer) - Fork of http://sourceforge.net/projects/mjpg-streamer/
* [emersion/mako](https://github.com/emersion/mako) - A lightweight Wayland notification daemon
* [iqiyi/dpvs](https://github.com/iqiyi/dpvs) - DPVS is a high performance Layer-4 load balancer based on DPDK.
* [joyent/libuv](https://github.com/joyent/libuv) - Go to *(archived)*
* [the-tcpdump-group/tcpdump](https://github.com/the-tcpdump-group/tcpdump) - the TCPdump network dissector
* [util-linux/util-linux](https://github.com/util-linux/util-linux)
* [mydumper/mydumper](https://github.com/mydumper/mydumper) - Official MyDumper Project
* [riscv-software-src/riscv-isa-sim](https://github.com/riscv-software-src/riscv-isa-sim) - Spike, a RISC-V ISA Simulator
* [saki4510t/UVCCamera](https://github.com/saki4510t/UVCCamera) - library and sample to access to UVC web camera on non-rooted Android device
* [SynoCommunity/spksrc](https://github.com/SynoCommunity/spksrc) - Cross compilation framework to create native packages for the Synology's NAS
* [polardb/PolarDB-for-PostgreSQL](https://github.com/polardb/PolarDB-for-PostgreSQL) - A cloud-native database based on PostgreSQL developed by Alibaba Cloud.
* [Ascotbe/Kernelhub](https://github.com/Ascotbe/Kernelhub) - :palm_tree:Linux、macOS、Windows Kernel privilege escalation vulnerability collection, with compilation environment, demo GIF map, vulnerability details, executable file (提权漏洞合集)
* [mintty/wsltty](https://github.com/mintty/wsltty) - Mintty as a terminal for Bash on Ubuntu on Windows / WSL
* [nanovms/nanos](https://github.com/nanovms/nanos) - A kernel designed to run one and only one application in a virtualized environment
* [kn007/silk-v3-decoder](https://github.com/kn007/silk-v3-decoder) - [Skype Silk Codec SDK]Decode silk v3 audio files (like wechat amr, aud files, qq slk files) and convert to other format (like mp3). Batch conversion support.
* [vmware/photon](https://github.com/vmware/photon) - Minimal Linux container host
* [facebook/openzl](https://github.com/facebook/openzl) - A novel take on lossless data compression
* [the-tcpdump-group/libpcap](https://github.com/the-tcpdump-group/libpcap) - the LIBpcap interface to various kernel packet capture mechanism
* [fancycode/MemoryModule](https://github.com/fancycode/MemoryModule) - Library to load a DLL from memory.
* [DynamoRIO/dynamorio](https://github.com/DynamoRIO/dynamorio) - Dynamic Instrumentation Tool Platform
* [tio/tio](https://github.com/tio/tio) - A serial device I/O tool
* [landley/toybox](https://github.com/landley/toybox) - toybox
* [sleuthkit/sleuthkit](https://github.com/sleuthkit/sleuthkit) - The Sleuth Kit® (TSK) is a library and collection of command line digital forensics tools that allow you to investigate volume and file system data. The library can be incorporated into larger digital forensics tools and the command line tools can be directly used to find evidence.
* [saghul/txiki.js](https://github.com/saghul/txiki.js) - A tiny JavaScript runtime
* [irssi/irssi](https://github.com/irssi/irssi) - The client of the future
* [saminiir/level-ip](https://github.com/saminiir/level-ip) - A hacker's userspace TCP/IP stack
* [hanslub42/rlwrap](https://github.com/hanslub42/rlwrap) - A readline wrapper
* [leahneukirchen/nq](https://github.com/leahneukirchen/nq) - Unix command line queue utility
* [vvaltchev/tilck](https://github.com/vvaltchev/tilck) - A Tiny Linux-Compatible Kernel
* [tomojitakasu/RTKLIB](https://github.com/tomojitakasu/RTKLIB)
* [wolfcw/libfaketime](https://github.com/wolfcw/libfaketime) - libfaketime modifies the system time for a single application
* [FFTW/fftw3](https://github.com/FFTW/fftw3) - DO NOT CHECK OUT THESE FILES FROM GITHUB UNLESS YOU KNOW WHAT YOU ARE DOING. (See below.)
* [HeyWillow/willow](https://github.com/HeyWillow/willow) - Open source, local, and self-hosted Amazon Echo/Google Home competitive Voice Assistant alternative
* [simd-everywhere/simde](https://github.com/simd-everywhere/simde) - Implementations of SIMD instruction sets for systems which don't natively support them.
* [rubinius/rubinius](https://github.com/rubinius/rubinius) - The Rubinius Language Platform
* [shellinabox/shellinabox](https://github.com/shellinabox/shellinabox) - Official-ish Fork of Shell In A Box
* [google/eddystone](https://github.com/google/eddystone) - Specification for Eddystone, an open beacon format from Google *(archived)*
* [hacksysteam/HackSysExtremeVulnerableDriver](https://github.com/hacksysteam/HackSysExtremeVulnerableDriver) - HackSys Extreme Vulnerable Driver (HEVD) - Windows & Linux
* [microsoft/ProcDump-for-Linux](https://github.com/microsoft/ProcDump-for-Linux) - A Linux version of the ProcDump Sysinternals tool
* [starrtc/starrtc-server](https://github.com/starrtc/starrtc-server) - 免费IM系统，IM即时通信消息系统(含一对一文字聊天，群聊，聊天室)，免费一对一voip实时通话，录屏，webrtc服务端，免费直播连麦，互动直播，视频直播，RTSP拉流，RTMP推流，语音对讲，免费在线会议，视频会议等服务端程序，支持物联网平台，✨万水千山总是情，来个star行不行✨
* [bb-qq/r8152](https://github.com/bb-qq/r8152) - Synology DSM driver for Realtek RTL8152/RTL8153/RTL8156 based adapters
* [slact/nchan](https://github.com/slact/nchan) - Fast, horizontally scalable, multiprocess pub/sub queuing server and proxy for HTTP, long-polling, Websockets and EventSource (SSE), powered by Nginx.
* [risinek/esp32-wifi-penetration-tool](https://github.com/risinek/esp32-wifi-penetration-tool) - Exploring possibilities of ESP32 platform to attack on nearby Wi-Fi networks.
* [mpaland/printf](https://github.com/mpaland/printf) - Tiny, fast, non-dependent and fully loaded printf implementation for embedded systems. Extensive test suite passing.
* [bztsrc/raspi3-tutorial](https://github.com/bztsrc/raspi3-tutorial) - Bare metal Raspberry Pi 3 tutorials
* [LMDB/lmdb](https://github.com/LMDB/lmdb) - Read-only mirror of official repo on openldap.org. Issues and pull requests here are ignored. Use OpenLDAP ITS for issues.
* [ps2homebrew/Open-PS2-Loader](https://github.com/ps2homebrew/Open-PS2-Loader) - Game and app loader for Sony PlayStation 2
* [stefanesser/dumpdecrypted](https://github.com/stefanesser/dumpdecrypted) - Dumps decrypted mach-o files from encrypted iPhone applications from memory to disk. This tool is necessary for security researchers to be able to look under the hood of encryption.
* [XorTroll/Goldleaf](https://github.com/XorTroll/Goldleaf) - 🍂 Multipurpose homebrew tool for Nintendo Switch
* [fukuchi/libqrencode](https://github.com/fukuchi/libqrencode) - A fast and compact QR Code encoding library
* [ravachol/kew](https://github.com/ravachol/kew) - Music for the Shell. kew is an immersive and fast music player that allows you to listen to music with privacy.
* [adrianlopezroche/fdupes](https://github.com/adrianlopezroche/fdupes) - FDUPES is a program for identifying or deleting duplicate files residing within specified directories.
* [jeelabs/esp-link](https://github.com/jeelabs/esp-link) - esp8266 wifi-serial bridge, outbound TCP, and arduino/AVR/LPC/NXP programmer
* [espruino/Espruino](https://github.com/espruino/Espruino) - The Espruino JavaScript interpreter - Official Repo
* [ntop/PF_RING](https://github.com/ntop/PF_RING) - High-speed packet processing framework
* [xdp-project/xdp-tutorial](https://github.com/xdp-project/xdp-tutorial) - XDP tutorial
* [madler/pigz](https://github.com/madler/pigz) - A parallel implementation of gzip for modern multi-processor, multi-core machines.
* [nicolasff/webdis](https://github.com/nicolasff/webdis) - A Redis HTTP interface with JSON output
* [strongswan/strongswan](https://github.com/strongswan/strongswan) - strongSwan - IPsec-based VPN
* [phoboslab/wipeout-rewrite](https://github.com/phoboslab/wipeout-rewrite)
* [baskerville/sxhkd](https://github.com/baskerville/sxhkd) - Simple X hotkey daemon
* [ArtifexSoftware/mupdf](https://github.com/ArtifexSoftware/mupdf) - mupdf mirror
* [mstorsjo/llvm-mingw](https://github.com/mstorsjo/llvm-mingw) - An LLVM/Clang/LLD based mingw-w64 toolchain
* [ImVexed/muon](https://github.com/ImVexed/muon) - GPU based Electron on a diet
* [HansKristian-Work/vkd3d-proton](https://github.com/HansKristian-Work/vkd3d-proton) - Fork of VKD3D. Development branches for Proton's Direct3D 12 implementation.
* [antirez/dump1090](https://github.com/antirez/dump1090) - Dump1090 is a simple Mode S decoder for RTLSDR devices
* [kamailio/kamailio](https://github.com/kamailio/kamailio) - Kamailio - The Open Source SIP Server for large VoIP and real-time communication platforms, focusing on flexibility, security and scalability
* [winshining/nginx-http-flv-module](https://github.com/winshining/nginx-http-flv-module) - A media streaming server based on nginx-rtmp-module. In addtion to the features nginx-rtmp-module provides, HTTP-FLV, GOP cache, VHosts (one IP for multi domain names) and JSON style statistics are supported now.
* [wolfSSL/wolfssl](https://github.com/wolfSSL/wolfssl) - The wolfSSL library is a small, fast, portable implementation of TLS/SSL for embedded devices to the cloud. wolfSSL supports up to TLS 1.3 and DTLS 1.3! Update to wolfSSL 5.9.1 for the latest CVE fixes.
* [openctp/openctp](https://github.com/openctp/openctp) - openctp提供CTP股票期权、中泰证券XTP、华鑫证券奇点TORA、东方证券OST、东方财富证券EMT、盈透证券TWS、易盛TAP、量投QDP等各通道的CTPAPI兼容接口，CTP程序可以无缝对接各股票柜台。openctp也提供了一套基于TTS交易系统的模拟环境，同样提供了CTPAPI兼容接口，不仅支持国内期货与期权全品种，也支持A股股票、基金、债券以及股票期权模拟交易，可以替代Simnow，为CTP量化交易开发者提供7x24可用的模拟环境。
* [inspektor-gadget/inspektor-gadget](https://github.com/inspektor-gadget/inspektor-gadget) - Inspektor Gadget is a set of tools and framework for data collection and system inspection on Kubernetes clusters and Linux hosts using eBPF
* [gatieme/LDD-LinuxDeviceDrivers](https://github.com/gatieme/LDD-LinuxDeviceDrivers) - Linux内核学习笔记
* [langhuihui/jessibuca](https://github.com/langhuihui/jessibuca) - Jessibuca是一款开源的纯H5直播流播放器
* [mofarrell/p2pvc](https://github.com/mofarrell/p2pvc) - A point to point color terminal video chat.
* [huggingface/neuralcoref](https://github.com/huggingface/neuralcoref) - ✨Fast Coreference Resolution in spaCy with Neural Networks
* [but0n/Avem](https://github.com/but0n/Avem) - 🚁 轻量级无人机飞控-[Drone]-[STM32]-[PID]-[BLDC]
* [gdbinit/MachOView](https://github.com/gdbinit/MachOView) - MachOView fork
* [tostercx/GTAO_Booster_PoC](https://github.com/tostercx/GTAO_Booster_PoC) - *(archived)*
* [earlephilhower/arduino-pico](https://github.com/earlephilhower/arduino-pico) - Raspberry Pi Pico Arduino core, for all RP2040 and RP2350 boards
* [openmv/openmv](https://github.com/openmv/openmv) - OpenMV Camera Module
* [mrexodia/TitanHide](https://github.com/mrexodia/TitanHide) - Hiding kernel-driver for x86/x64.
* [htacg/tidy-html5](https://github.com/htacg/tidy-html5) - The granddaddy of HTML tools, with support for modern standards
* [saitoha/libsixel](https://github.com/saitoha/libsixel) - A SIXEL encoder/decoder implementation derived from kmiya's sixel (https://github.com/saitoha/sixel).
* [armink/FlashDB](https://github.com/armink/FlashDB) - An ultra-lightweight database that supports key-value and time series data | 一款支持 KV 数据和时序数据的超轻量级数据库
* [adafruit/Adafruit-GFX-Library](https://github.com/adafruit/Adafruit-GFX-Library) - Adafruit GFX graphics core Arduino library, this is the 'core' class that all our other graphics libraries derive from
* [destan19/OpenAppFilter](https://github.com/destan19/OpenAppFilter) - OAF(OpenAppFilter) is a parental control software based on OpenWrt. It supports popular applications across gaming, video streaming, instant messaging, such as TikTok, YouTube, Facebook. Currently, it supports hundreds of different applications.
* [seclab-ucr/INTANG](https://github.com/seclab-ucr/INTANG)
* [jedisct1/minisign](https://github.com/jedisct1/minisign) - A dead simple tool to sign files and verify digital signatures.
* [sqfmi/Watchy](https://github.com/sqfmi/Watchy) - Watchy - An Open Source E-Ink Smartwatch
* [mbebenita/Broadway](https://github.com/mbebenita/Broadway) - A JavaScript H.264 decoder.
* [ARMmbed/DAPLink](https://github.com/ARMmbed/DAPLink)
* [minoca/os](https://github.com/minoca/os) - Minoca operating system
* [EZLippi/WebBench](https://github.com/EZLippi/WebBench) - Webbench是Radim Kolar在1997年写的一个在linux下使用的非常简单的网站压测工具。它使用fork()模拟多个客户端同时访问我们设定的URL，测试网站在压力下工作的性能，最多可以模拟3万个并发连接去测试网站的负载能力。官网地址:http://home.tiscali.cz/~cz210552/webbench.html
* [IoLanguage/io](https://github.com/IoLanguage/io) - Io programming language. Inspired by Self, Smalltalk and LISP.
* [BitMaker-hub/NerdMiner_v2](https://github.com/BitMaker-hub/NerdMiner_v2) - Improved version of first ESP32 NerdMiner
* [viabtc/viabtc_exchange_server](https://github.com/viabtc/viabtc_exchange_server) - A trading engine with high-speed performance and real-time notification
* [Ettercap/ettercap](https://github.com/Ettercap/ettercap) - Ettercap Project
* [espressif/esp32-camera](https://github.com/espressif/esp32-camera)
* [zodiacon/WindowsInternals](https://github.com/zodiacon/WindowsInternals) - Windows Internals Book 7th edition Tools
* [panda-re/panda](https://github.com/panda-re/panda) - Platform for Architecture-Neutral Dynamic Analysis
* [Entware/Entware](https://github.com/Entware/Entware) - Ultimate repo for embedded devices
* [ShadowsocksR-Live/shadowsocksr-native](https://github.com/ShadowsocksR-Live/shadowsocksr-native) - 翻墙 从容穿越党国敏感日 ShadowsocksR (SSRoT) native implementation for all platforms, GFW terminator
* [haampie/libtree](https://github.com/haampie/libtree) - ldd as a tree
* [labwc/labwc](https://github.com/labwc/labwc) - A Wayland window-stacking compositor
* [FWGS/xash3d-fwgs](https://github.com/FWGS/xash3d-fwgs) - Xash3D FWGS engine
* [jiangdongguo/AndroidUSBCamera](https://github.com/jiangdongguo/AndroidUSBCamera) - 🔥🔥🔥Flexible and useful UVC camera engine on Android platform, supporting multi-road cameras!
* [rewardone/OSCPRepo](https://github.com/rewardone/OSCPRepo) - A list of commands, scripts, resources, and more that I have gathered and attempted to consolidate for use as OSCP (and more) study material. Commands in 'Usefulcommands' Keepnote. Bookmarks and reading material in 'BookmarkList' CherryTree. Reconscan Py2 and Py3. Custom ISO building.
* [atar-axis/xpadneo](https://github.com/atar-axis/xpadneo) - Advanced Linux Driver for Xbox One Wireless Controller (shipped with Xbox One S)
* [libbpf/libbpf](https://github.com/libbpf/libbpf) - Automated upstream mirror for libbpf stand-alone build.
* [checkra1n/PongoOS](https://github.com/checkra1n/PongoOS) - pongoOS
* [DynamoRIO/drmemory](https://github.com/DynamoRIO/drmemory) - Memory Debugger for Windows, Linux, Mac, and Android
* [airockchip/rknn_model_zoo](https://github.com/airockchip/rknn_model_zoo)
* [f0rb1dd3n/Reptile](https://github.com/f0rb1dd3n/Reptile) - LKM Linux rootkit
* [eth-brownie/brownie](https://github.com/eth-brownie/brownie) - A Python-based development and testing framework for smart contracts targeting the Ethereum Virtual Machine.
* [dlundquist/sniproxy](https://github.com/dlundquist/sniproxy) - Proxies incoming HTTP and TLS connections based on the hostname contained in the initial request of the TCP session.
* [jfernandez/bpftop](https://github.com/jfernandez/bpftop) - bpftop provides a dynamic real-time view of running eBPF programs. It displays the average runtime, events per second, and estimated total CPU % for each program.
* [PureDarwin/PureDarwin](https://github.com/PureDarwin/PureDarwin) - Darwin is the Open Source core of macOS, and PureDarwin is a community project to extend Darwin into a complete, usable operating system.
* [strace/strace](https://github.com/strace/strace) - strace is a diagnostic, debugging and instructional userspace utility for Linux
* [buaazp/zimg](https://github.com/buaazp/zimg) - A lightweight and high performance image storage and processing system.
* [flame/blis](https://github.com/flame/blis) - BLAS-like Library Instantiation Software Framework
* [rogerclarkmelbourne/Arduino_STM32](https://github.com/rogerclarkmelbourne/Arduino_STM32) - Arduino STM32. Hardware files to support STM32 boards, on Arduino IDE 1.8.x including LeafLabs Maple and other generic STM32F103 boards
* [pjsip/pjproject](https://github.com/pjsip/pjproject) - PJSIP project
* [espressif/esp-iot-solution](https://github.com/espressif/esp-iot-solution) - Espressif IoT Library. IoT Device Drivers, Documentations and Solutions.
* [pipelinedb/pipelinedb](https://github.com/pipelinedb/pipelinedb) - High-performance time-series aggregation for PostgreSQL
* [vmware/open-vm-tools](https://github.com/vmware/open-vm-tools) - Official repository of VMware open-vm-tools project
* [WizTeam/WizQTClient](https://github.com/WizTeam/WizQTClient) - 为知笔记跨平台客户端
* [SinaKarvandi/Hypervisor-From-Scratch](https://github.com/SinaKarvandi/Hypervisor-From-Scratch) - Source code of a multiple series of tutorials about the hypervisor. Available at: https://rayanfam.com/tutorials
* [cundong/SmartAppUpdates](https://github.com/cundong/SmartAppUpdates) - APK delta generation and reconstruction for Android
* [TryQuiet/quiet](https://github.com/TryQuiet/quiet) - A private, p2p alternative to Slack and Discord built on Tor & IPFS
* [NoiseByNorthwest/php-spx](https://github.com/NoiseByNorthwest/php-spx) - A simple & straight-to-the-point PHP profiling extension with its built-in web UI
* [Sunzxyong/Tiny](https://github.com/Sunzxyong/Tiny) - an image compression framework.（一个高保真、高压缩比的图片压缩框架）
* [d0k3/GodMode9](https://github.com/d0k3/GodMode9) - GodMode9 Explorer - A full access file browser for the Nintendo 3DS console :godmode:
* [apple/HomeKitADK](https://github.com/apple/HomeKitADK) - *(archived)*
* [rbsec/sslscan](https://github.com/rbsec/sslscan) - sslscan tests SSL/TLS enabled services to discover supported cipher suites
* [xoreaxeaxeax/rosenbridge](https://github.com/xoreaxeaxeax/rosenbridge) - Hardware backdoors in x86 CPUs
* [danielfrg/word2vec](https://github.com/danielfrg/word2vec) - Python interface to Google word2vec *(archived)*
* [BandarHL/BHTwitter](https://github.com/BandarHL/BHTwitter) - Awesome tweak for Twitter
* [googleprojectzero/winafl](https://github.com/googleprojectzero/winafl) - A fork of AFL for fuzzing Windows binaries
* [McNopper/OpenGL](https://github.com/McNopper/OpenGL) - OpenGL 3 and 4 examples using GLSL
* [nanomq/nanomq](https://github.com/nanomq/nanomq) - An ultra-lightweight and blazing-fast Messaging Bus/MQTT Broker for Edge & SDV
* [martinezjavier/ldd3](https://github.com/martinezjavier/ldd3) - Linux Device Drivers 3 examples updated to work in recent kernels
* [jerryscript-project/iotjs](https://github.com/jerryscript-project/iotjs) - Platform for Internet of Things with JavaScript http://www.iotjs.net
* [mas-bandwidth/netcode](https://github.com/mas-bandwidth/netcode) - Secure client/server protocol for multiplayer games built on top of UDP
* [bjornbytes/lovr](https://github.com/bjornbytes/lovr) - Lua Virtual Reality Framework
* [FreeRADIUS/freeradius-server](https://github.com/FreeRADIUS/freeradius-server) - FreeRADIUS - A multi-protocol policy server.
* [bytedance/bhook](https://github.com/bytedance/bhook) - 通用的Android PLT hook库，支持armeabi-v7a，arm64-v8a，x86，x86_64
* [cgsecurity/testdisk](https://github.com/cgsecurity/testdisk) - TestDisk & PhotoRec
* [libratbag/libratbag](https://github.com/libratbag/libratbag) - A DBus daemon to configure input devices, mainly high-end and gaming mice
* [hmgle/graftcp](https://github.com/hmgle/graftcp) - A flexible tool for redirecting a program's TCP, UDP, and DNS traffic to SOCKS5 or HTTP proxies.
* [Modos-Labs/Glider](https://github.com/Modos-Labs/Glider) - Open-source E-ink monitor. Mirror of https://gitlab.com/zephray/glider
* [NicoHood/HID](https://github.com/NicoHood/HID) - Bring enhanced HID functions to your Arduino!
* [webserver-llc/angie](https://github.com/webserver-llc/angie) - Angie - drop-in replacement for nginx
* [amadvance/snapraid](https://github.com/amadvance/snapraid) - A backup program for disk arrays. It stores parity information of your data and it recovers from up to six disk failures
* [s0lst1c3/eaphammer](https://github.com/s0lst1c3/eaphammer) - Targeted evil twin attacks against WPA2-Enterprise networks. Indirect wireless pivots using hostile portal attacks.
* [iliasam/OpenSimpleLidar](https://github.com/iliasam/OpenSimpleLidar) - Open Source scanning laser rangefinder
* [dayanch96/YTMusicUltimate](https://github.com/dayanch96/YTMusicUltimate) - The best tweak for YouTube Music iOS.
* [FreeRDP/Remmina](https://github.com/FreeRDP/Remmina) - Mirror of https://gitlab.com/Remmina/Remmina The GTK+ Remmina Remote Desktop Client
* [ZBar/ZBar](https://github.com/ZBar/ZBar) - Clone of the mercurial repository http://zbar.hg.sourceforge.net:8000/hgroot/zbar/zbar
* [signal11/hidapi](https://github.com/signal11/hidapi) - A Simple library for communicating with USB and Bluetooth HID devices on Linux, Mac, and Windows.
* [johnxnguyen/Down](https://github.com/johnxnguyen/Down) - Blazing fast Markdown / CommonMark rendering in Swift, built upon cmark.
* [aws/amazon-freertos](https://github.com/aws/amazon-freertos) - DEPRECATED - See README.md *(archived)*
* [carlini/printf-tac-toe](https://github.com/carlini/printf-tac-toe) - tic-tac-toe in a single call to printf
* [r4j0x00/exploits](https://github.com/r4j0x00/exploits)
* [gen2brain/raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for raylib, a simple and easy-to-use library to enjoy videogames programming.
* [riba2534/TCP-IP-NetworkNote](https://github.com/riba2534/TCP-IP-NetworkNote) - 📘《TCP/IP网络编程》(韩-尹圣雨)学习笔记
* [CTurt/FreeDVDBoot](https://github.com/CTurt/FreeDVDBoot) - PlayStation 2 DVD Player Exploit
* [MaJerle/stm32f429](https://github.com/MaJerle/stm32f429) - Keil projects and libraries for STM32F4xx devices
* [tidwall/pogocache](https://github.com/tidwall/pogocache) - Fast caching software with a focus on low latency and cpu efficiency.
* [nkolban/esp32-snippets](https://github.com/nkolban/esp32-snippets) - Sample ESP32 snippets and code fragments
* [yangjie10930/EpMedia](https://github.com/yangjie10930/EpMedia) - Android上基于FFmpeg开发的视频处理框架，简单易用，体积小，帮助使用者快速实现视频处理功能。包含以下功能：剪辑，裁剪，旋转，镜像，合并，分离，变速，添加LOGO，添加滤镜，添加背景音乐，加速减速视频，倒放音视频。 The video processing framework based on FFmpeg developed on Android is simple, easy to use, and small in size, helping users quickly realize video processing functions. Contains the following functions: editing, cropping, rotating, mirroring, merging, separating, variable speed, adding LOGO, adding filters, adding background music, accelerating and decelerating video, rewinding audio and video.
* [strongtz/i915-sriov-dkms](https://github.com/strongtz/i915-sriov-dkms) - dkms module of Linux i915 driver with SR-IOV support
* [AprilRobotics/apriltag](https://github.com/AprilRobotics/apriltag) - AprilTag is a visual fiducial system popular for robotics research.
* [medusalix/xone](https://github.com/medusalix/xone) - Linux kernel driver for Xbox One and Xbox Series X|S accessories
* [wiseman/py-webrtcvad](https://github.com/wiseman/py-webrtcvad) - Python interface to the WebRTC Voice Activity Detector
* [p-gen/smenu](https://github.com/p-gen/smenu) - smenu started as a lightweight and flexible terminal menu generator, but quickly evolved into a powerful and versatile CLI selection tool for interactive or scripting use.
* [alibaba/tsar](https://github.com/alibaba/tsar) - Taobao System Activity Reporter
* [FluidSynth/fluidsynth](https://github.com/FluidSynth/fluidsynth) - Software synthesizer based on the SoundFont 2 specifications
* [vivien/i3blocks](https://github.com/vivien/i3blocks) - The hacker-friendly status_command for Sway and i3
* [damonkohler/sl4a](https://github.com/damonkohler/sl4a) - SL4A brings scripting languages to Android by allowing you to edit and execute scripts and interactive interpreters directly on the Android device. *(archived)*
* [FIX94/Nintendont](https://github.com/FIX94/Nintendont) - A Wii Homebrew Project to play GC Games on Wii and vWii on Wii U
* [No-Chicken/OV-Watch](https://github.com/No-Chicken/OV-Watch) - A powerful Smart Watch based on STM32, FreeRTOS, LVGL.
* [cokemine/ServerStatus-Hotaru](https://github.com/cokemine/ServerStatus-Hotaru) - 云探针、多服务器探针、云监控、多服务器云监控
* [0015/ThatProject](https://github.com/0015/ThatProject) - *That Project's project repository
* [EtchedPixels/FUZIX](https://github.com/EtchedPixels/FUZIX) - FuzixOS: Because Small Is Beautiful *(archived)*
* [abrasive/shairport](https://github.com/abrasive/shairport) - Airtunes emulator! Shairport is no longer maintained.
* [github/glb-director](https://github.com/github/glb-director) - GitHub Load Balancer Director and supporting tooling.
* [conorpp/u2f-zero](https://github.com/conorpp/u2f-zero) - U2F USB token optimized for physical security, affordability, and style
* [maharmstone/quibble](https://github.com/maharmstone/quibble) - Quibble - the custom Windows bootloader
* [google/XNNPACK](https://github.com/google/XNNPACK) - High-efficiency floating-point neural network inference operators for mobile, server, and Web
* [rbaron/b-parasite](https://github.com/rbaron/b-parasite) - 🌱💧 An open source DIY soil moisture sensor
* [wiredtiger/wiredtiger](https://github.com/wiredtiger/wiredtiger) - WiredTiger's source tree
* [GBALATRO/balatro-gba](https://github.com/GBALATRO/balatro-gba) - A demake of Balatro for the GBA
* [phoboslab/jsmpeg-vnc](https://github.com/phoboslab/jsmpeg-vnc) - A low latency, high framerate screen sharing server for Windows and client for browsers
* [robotmedia/RMStore](https://github.com/robotmedia/RMStore) - A lightweight iOS library for In-App Purchases
* [hasherezade/hollows_hunter](https://github.com/hasherezade/hollows_hunter) - Scans all running processes. Recognizes and dumps a variety of potentially malicious implants (replaced/implanted PEs, shellcodes, hooks, in-memory patches).
* [FlyGoat/RyzenAdj](https://github.com/FlyGoat/RyzenAdj) - Adjust power management settings for Ryzen APUs
* [ChrisJohnsen/tmux-MacOSX-pasteboard](https://github.com/ChrisJohnsen/tmux-MacOSX-pasteboard) - Notes and workarounds for accessing the Mac OS X pasteboard in tmux sessions. Note: The pu branch (“Proposed Updates”) may be rewound without notice.
* [earlephilhower/ESP8266Audio](https://github.com/earlephilhower/ESP8266Audio) - Arduino library to play MOD, WAV, FLAC, MIDI, RTTTL, OGG/Opus, MP3, and AAC files on I2S DACs or with a software emulated delta-sigma DAC on the ESP8266 and ESP32 and Pico
* [mkj/dropbear](https://github.com/mkj/dropbear) - Dropbear SSH
* [webmproject/libwebp](https://github.com/webmproject/libwebp) - Mirror only. Please do not send pull requests. See https://chromium.googlesource.com/webm/libwebp/+/HEAD/CONTRIBUTING.md.
* [bytedance/android-inline-hook](https://github.com/bytedance/android-inline-hook) - 通用的Android inline hook库，支持thumb，arm32，arm64
* [bootleg/ret-sync](https://github.com/bootleg/ret-sync) - ret-sync is a set of plugins that helps to synchronize a debugging session (WinDbg/GDB/LLDB/OllyDbg2/x64dbg) with IDA/Ghidra/Binary Ninja disassemblers.
* [solokeys/solo1](https://github.com/solokeys/solo1) - Solo 1 firmware in C
* [pschatzmann/arduino-audio-tools](https://github.com/pschatzmann/arduino-audio-tools) - Audio Tools (a powerful Audio library for Arduino, PlatformIO, IDF)
* [viest/php-ext-xlswriter](https://github.com/viest/php-ext-xlswriter) - 🚀 PHP Extension for creating and reader XLSX files.
* [shadowsocks/simple-obfs](https://github.com/shadowsocks/simple-obfs) - A simple obfuscating tool (Deprecated)
* [0x1abin/MultiButton](https://github.com/0x1abin/MultiButton) - Button driver for embedded system
* [armink/EasyFlash](https://github.com/armink/EasyFlash) - Lightweight IoT device information storage solution: KV/IAP/LOG. | 轻量级物联网设备信息存储方案：参数存储、在线升级及日志存储 ，全新一代版本请移步至 https://github.com/armink/FlashDB
* [taviso/ctypes.sh](https://github.com/taviso/ctypes.sh) - A foreign function interface for bash.
* [h2o/picohttpparser](https://github.com/h2o/picohttpparser) - tiny HTTP parser written in C (used in HTTP::Parser::XS et al.)
* [lexbor/lexbor](https://github.com/lexbor/lexbor) - Lexbor is development of an open source HTML Renderer library. https://lexbor.com
* [aixed/WeChat-Hook](https://github.com/aixed/WeChat-Hook) - 微信 收发消息功能/ PC微信3.9.10.16 & 4.1.10.27接口 微信Hook 微信机器人 微信Hook源码 PC微信协议 PC微信协议算法
* [symisc/sod](https://github.com/symisc/sod) - An Embedded Computer Vision & Machine Learning Library (CPU Optimized & IoT Capable)
* [nvim-telescope/telescope-fzf-native.nvim](https://github.com/nvim-telescope/telescope-fzf-native.nvim) - FZF sorter for telescope written in c
* [antirez/voxtral.c](https://github.com/antirez/voxtral.c) - Pure C inference of Mistral Voxtral Realtime 4B speech to text model
* [lexborisov/myhtml](https://github.com/lexborisov/myhtml) - Fast C/C++ HTML 5 Parser. Using threads.
* [TA-Lib/ta-lib](https://github.com/TA-Lib/ta-lib) - Official TA-Lib Core
* [taf2/curb](https://github.com/taf2/curb) - Ruby bindings for libcurl
* [sist2app/sist2](https://github.com/sist2app/sist2) - Lightning-fast file system indexer and search tool
* [brandur/redis-cell](https://github.com/brandur/redis-cell) - A Redis module that provides rate limiting in Redis as a single command.
* [WebSpiderUtils/verification_code](https://github.com/WebSpiderUtils/verification_code) - 验证码研究破解心得记录。包含网易易盾，阿里云验证码，极验验证码，通用汉字识别，梦幻西游验证等主流验证码破解。包含点按验证码、点选验证、语序点选等等。已更新极验验证码、企业公示网/工商/文书采集系统、极验打码接口。
* [chentao0707/QrCodeScan](https://github.com/chentao0707/QrCodeScan) - Android手机客户端二维码扫描
* [PriesiaMioShirakana/DragonianVoice](https://github.com/PriesiaMioShirakana/DragonianVoice) - 多个SVC/TTS的C++推理库
* [OpenIDC/mod_auth_openidc](https://github.com/OpenIDC/mod_auth_openidc) - OpenID Certified™ OpenID Connect and FAPI 2 Relying Party module for Apache HTTPd
* [Yangyuanxin/Embedded-Product-Collect](https://github.com/Yangyuanxin/Embedded-Product-Collect) - 嵌入式产品级项目收集
* [RedisLabs/redis-cluster-proxy](https://github.com/RedisLabs/redis-cluster-proxy) - A proxy for Redis clusters.
* [confluentinc/librdkafka](https://github.com/confluentinc/librdkafka) - The Apache Kafka C/C++ library
* [TulipCharts/tulipindicators](https://github.com/TulipCharts/tulipindicators) - Technical Analysis Indicator Function Library in C
* [fcambus/telize](https://github.com/fcambus/telize) - High performance JSON IP and GeoIP REST API (IP Geolocation)
* [groonga/groonga](https://github.com/groonga/groonga) - An embeddable fulltext search engine. Groonga is the successor project to Senna.
* [deanmao/node-chimera](https://github.com/deanmao/node-chimera) - A new kind of headless webkit integration for nodejs; a great alternative to phantomjs.
* [antirez/botlib](https://github.com/antirez/botlib) - C Telegram bot framework
* [usrbinnc/netcat-cpi-kernel-module](https://github.com/usrbinnc/netcat-cpi-kernel-module) - Kernel module edition of the Cycles Per Instruction (2014) album.
* [laruence/yac](https://github.com/laruence/yac) - A fast, lock-free, shared memory user data cache for PHP
* [eleme/corvus](https://github.com/eleme/corvus) - A fast and lightweight Redis Cluster Proxy for Redis 3.0
* [lexborisov/Modest](https://github.com/lexborisov/Modest) - Modest is a fast HTML renderer implemented as a pure C99 library with no outside dependencies.
* [Yubico/yubico-pam](https://github.com/Yubico/yubico-pam) - Yubico Pluggable Authentication Module (PAM) *(archived)*
* [gustavogenovese/curl-android-ios](https://github.com/gustavogenovese/curl-android-ios) - Static libcurl to be used in Android and iOS apps. Build scripts included. No Android source required
* [nativeformat/NFHTTP](https://github.com/nativeformat/NFHTTP) - A cross platform C++ HTTP library that interfaces natively to other platforms.
* [triaquae/CrazyEye](https://github.com/triaquae/CrazyEye) - OpenSource IT Automation Software
* [eclipse-embed-cdt/eclipse-plugins](https://github.com/eclipse-embed-cdt/eclipse-plugins) - The Eclipse Embedded CDT plug-ins for Arm & RISC-V C/C++ developers (formerly known as the GNU MCU Eclipse plug-ins). Includes the archive of previous plug-ins versions, as Releases.


## 🌐 Web Resources & Interactive Index
- [OBBY MODES ONLINE MINI GAMES](https://ilearnworldpt.pages.dev/obby-modes-online-mini-games.html)
- [TRAVEL WITH ME ASMR EDITION](https://thelearnquesters.pages.dev/travel-with-me-asmr-edition.html)
- [MATCH DREAM GARDEN](https://themindplaying.web.app/match-dream-garden.html)
- [MOTO STUNT BIKER](https://thelearnquesters.pages.dev/moto-stunt-biker.html)
- [MY KITTIES CATWORLD](https://thelearnquesters.pages.dev/my-kitties-catworld.html)
- [ACCURATE 2D](https://thelearnquesters.pages.dev/accurate-2d.html)
- [PENGUIN ADVENTURE](https://themindplays.pages.dev/penguin-adventure.html)
- [WIPE INSIGHT MASTER](https://themindplaying.web.app/wipe-insight-master.html)
- [THE ROAD HOME GRANNY ESCAPE](https://thelearnquesters.pages.dev/the-road-home-granny-escape.html)
- [CATEGORY OBBY](https://iskillquest.pages.dev/category-obby.html)
- [RIDE SHOOTER](https://theskillquest.pages.dev/ride-shooter.html)
- [FOOD TOWER DEFENSE](https://thelearnquesters.pages.dev/food-tower-defense.html)
- [CATEGORY FLASH 2](https://skillplay.github.io/category-flash-2.html)
- [STRATEGY OF WAR TANKS AND HELICOPTERS](https://themindplays.pages.dev/strategy-of-war-tanks-and-helicopters.html)
- [MERGE 3D MATCH 3 BALLOONS](https://theskillquest.pages.dev/merge-3d-match-3-balloons.html)
- [FUNNY FRUITS MERGE AND GATHER WATERMELON](https://theskillquest.pages.dev/funny-fruits-merge-and-gather-watermelon.html)
- [BLOCK PUZZLE KING](https://themindplaying.web.app/block-puzzle-king.html)
- [DEVIL DUCK NOT A TROLL GAME](https://themindplays.pages.dev/devil-duck-not-a-troll-game.html)
- [HYDRO RACING 3D](https://theskillquest.pages.dev/hydro-racing-3d.html)
- [FUN TOWN PARKING](https://theskillquest.pages.dev/fun-town-parking.html)
- [WAR ROBOTS BATTLES](https://theskillquest.pages.dev/war-robots-battles.html)
- [GATE HEROES BATTLE](https://thelearnquesters.pages.dev/gate-heroes-battle.html)
- [BRIDGE WARS](https://themindplaying.web.app/bridge-wars.html)
- [CATEGORY TOWER DEFENSE118](https://themindplays.pages.dev/category-tower-defense118.html)
- [MISSION SANTA DELIVER THE GIFTS](https://thelearnquesters.pages.dev/mission-santa-deliver-the-gifts.html)
- [BLOCK COMBO BLAST](https://thelearnquesters.pages.dev/block-combo-blast.html)
- [THE HARDEST PUZZLE EVER](https://theskillquest.pages.dev/the-hardest-puzzle-ever.html)
- [ZEN SOLITAIRE](https://theskillquest.pages.dev/zen-solitaire.html)
- [ELEMENTAL GLOVES MAGIC POWER](https://thelearnquesters.pages.dev/elemental-gloves-magic-power.html)
- [CATEGORY TITANIUMNETWORK PROXIES](https://themindplays.pages.dev/category-titaniumnetwork-proxies.html)
- [COIN EMPIRE](https://themindplaying.web.app/coin-empire.html)
- [CATEGORY MINING](https://themindplaying.web.app/category-mining.html)
- [CATEGORY QUIZ](https://themindplaying.web.app/category-quiz.html)
- [ARMY COMMANDER CRAFT](https://themindplays.pages.dev/army-commander-craft.html)
- [CATEGORY MATCH 3](https://thelearnquesters.pages.dev/category-match-3.html)
- [RESTAURANT SIMULATOR BURGERS PIZZA](https://themindplays.pages.dev/restaurant-simulator-burgers-pizza.html)
- [CATEGORY INCREMENTAL388](https://themindplays.pages.dev/category-incremental388.html)
- [BUBBLE SHOOTER BLAST](https://thelearnquesters.pages.dev/bubble-shooter-blast.html)
- [SOLITAIRE QUEST](https://theskillquest.pages.dev/solitaire-quest.html)
- [INDEX19](https://themindplaying.web.app/index19.html)
- [INDEX36](https://thequizzone.pages.dev/index36.html)
- [CATEGORY PIXEL313](https://themindplays.pages.dev/category-pixel313.html)
- [AGE OF ZOMBIES](https://theskillquest.pages.dev/age-of-zombies.html)
- [HUMAN LEAP EVOLUTION](https://theskillquest.pages.dev/human-leap-evolution.html)
- [CATEGORY CASUAL 13](https://thequizzone.pages.dev/category-casual-13.html)
- [SNAKEMAXX](https://thelearnquesters.pages.dev/snakemaxx.html)
- [CATEGORY THINKY 3](https://thelearnquesters.pages.dev/category-thinky-3.html)
- [CUBE DROP PUZZLE](https://themindplaying.web.app/cube-drop-puzzle.html)
- [CATEGORY ART32](https://themindplays.pages.dev/category-art32.html)
- [CATEGORY THINKY 3](https://themindplays.pages.dev/category-thinky-3.html)
- [MERGE SHOOTER](https://themindplaying.web.app/merge-shooter.html)
- [MAGIC AND WIZARDS MAHJONG](https://themindplaying.web.app/magic-and-wizards-mahjong.html)
- [MAHJONG GARDEN](https://theskillquest.pages.dev/mahjong-garden.html)
- [CAPYBARA BLOCK BLAST](https://themindplay.pages.dev/capybara-block-blast.html)
- [CATEGORY UNBLOCKEDGAMES](https://themindplays.pages.dev/category-unblockedgames.html)
- [ROMANTIC MATCH TACTICS](https://theskillquest.pages.dev/romantic-match-tactics.html)
- [CUBES 2048IO](https://themindplays.pages.dev/cubes-2048io.html)
- [MINI SCRAPBOOK PAPER](https://thelearnquesters.pages.dev/mini-scrapbook-paper.html)
- [SUPER CLONER 3D](https://themindplays.pages.dev/super-cloner-3d.html)
- [ESCAPE OR DIE TROLL DEVIL LEVELS](https://themindplays.pages.dev/escape-or-die-troll-devil-levels.html)
- [ARCHERY MASTER BOW AND ARROW](https://thelearnquesters.pages.dev/archery-master-bow-and-arrow.html)
- [CATEGORY OBBY56](https://themindplays.pages.dev/category-obby56.html)
- [MOTO STUNT BIKER](https://themindplays.pages.dev/moto-stunt-biker.html)
- [CATEGORY STICKMAN175](https://themindplays.pages.dev/category-stickman175.html)
- [CATEGORY GUN238](https://thelearnquesters.pages.dev/category-gun238.html)
- [CARS VS ZOMBIES](https://themindplaying.web.app/cars-vs-zombies.html)
- [ANIMERGE](https://themindplay.pages.dev/animerge.html)
- [CAT PANCAKE DINER](https://theskillquest.pages.dev/cat-pancake-diner.html)
- [CATEGORY CASUAL](https://themindplays.pages.dev/category-casual.html)
- [QUEEN OF MAHJONG](https://thelearnquesters.pages.dev/queen-of-mahjong.html)
- [CATEGORY MOUSE1 697](https://themindplaying.web.app/category-mouse1-697.html)
- [SPRING TILE MASTER](https://theskillquest.pages.dev/spring-tile-master.html)
- [MONEY FACTORY EARN A BILLION](https://thelearnquesters.pages.dev/money-factory-earn-a-billion.html)
- [FIND HIDDEN SECRETS](https://thelearnquesters.pages.dev/find-hidden-secrets.html)
- [TICTOC BRAIDED HAIRSTYLES](https://theskillquest.pages.dev/tictoc-braided-hairstyles.html)
- [BEACH SOCCER](https://theskillquest.pages.dev/beach-soccer.html)
- [CATEGORY MOBILE2 112](https://themindplaying.web.app/category-mobile2-112.html)
- [CATEGORY SANDBOX40](https://themindplays.pages.dev/category-sandbox40.html)
- [ICE CUBE](https://themindplays.pages.dev/ice-cube.html)
- [CATEGORY AVOID295](https://thequizzone.pages.dev/category-avoid295.html)
- [SUPER SWING](https://theskillquest.pages.dev/super-swing.html)
- [STUMBLE GUYS](https://theskillquest.pages.dev/stumble-guys.html)
- [MARBLE RUN ULTIMATE RACE](https://theskillquest.pages.dev/marble-run-ultimate-race.html)
- [CATEGORY IDLE445](https://themindplays.pages.dev/category-idle445.html)
- [TONY ARCHER](https://themindplay.pages.dev/tony-archer.html)
- [NUTS STACK SORT NUTS BOLTS](https://themindplays.pages.dev/nuts-stack-sort-nuts-bolts.html)
- [CATEGORY COLOR195](https://skillplay.github.io/category-color195.html)
- [BLACKRIVER MYSTERY HIDDEN OBJECTS](https://themindplaying.web.app/blackriver-mystery-hidden-objects.html)
- [SLINGSHOT CHICKEN](https://themindplays.pages.dev/slingshot-chicken.html)
- [REVERSI](https://theskillquest.pages.dev/reversi.html)
- [CATEGORY CAR 2](https://thequizzone.pages.dev/category-car-2.html)
- [BRAINROT MERGE](https://themindplay.pages.dev/brainrot-merge.html)
- [KIRKA IO](https://thelearnquesters.pages.dev/kirka-io.html)
- [TRIVIA NATION](https://themindplays.pages.dev/trivia-nation.html)
- [PUT THE FRUIT TOGETHER](https://themindplay.pages.dev/put-the-fruit-together.html)
- [MAGIC BOTTLES](https://themindplays.pages.dev/magic-bottles.html)
- [BLOCK DROPPING MERGE](https://themindplaying.web.app/block-dropping-merge.html)
- [CATEGORY WATER39](https://themindplays.pages.dev/category-water39.html)
- [OFFICE ESCAPE TO DATE](https://theskillquest.pages.dev/office-escape-to-date.html)
- [IDLE LUNCH](https://thelearnquesters.pages.dev/idle-lunch.html)
- [LOLLIPOP STACK RUN](https://thelearnquesters.pages.dev/lollipop-stack-run.html)
- [ASMR TATTOO TREATMENT](https://theskillquest.pages.dev/asmr-tattoo-treatment.html)
- [BATTLESHIP](https://themindplay.pages.dev/battleship.html)
- [INDEX40](https://thequizzone.pages.dev/index40.html)
- [CATEGORY 3D1 371](https://thequizzone.pages.dev/category-3d1-371.html)
- [OFFROAD MUDDY TRUCKS](https://theskillquest.pages.dev/offroad-muddy-trucks.html)
- [UNCLE BULLET 007](https://themindplays.pages.dev/uncle-bullet-007.html)
- [ROYAL JEWELS MATCH](https://themindplaying.web.app/royal-jewels-match.html)
- [CATEGORY THINKY](https://themindplay.github.io/category-thinky.html)
- [HERO FIGHT CLASH](https://themindplay.pages.dev/hero-fight-clash.html)
- [GUN FEST](https://theskillquest.pages.dev/gun-fest.html)
- [HOOP RIVALS](https://themindplays.pages.dev/hoop-rivals.html)
- [CATEGORY BATTLE 3](https://thequizzone.pages.dev/category-battle-3.html)
- [CATEGORY CRASH32](https://themindplays.pages.dev/category-crash32.html)
- [CATEGORY TETRIS36](https://themindplays.pages.dev/category-tetris36.html)
- [TILE GURU](https://thelearnquesters.pages.dev/tile-guru.html)
- [TEXAS HOLDEM POKER](https://themindplay.pages.dev/texas-holdem-poker.html)
- [STICKMAN PUNISHMENT](https://iskillquest.pages.dev/stickman-punishment.html)
- [THUMBPINBALL](https://themindplays.pages.dev/thumbpinball.html)
- [MINECRAFT PIXEL WARFARE](https://thelearnquesters.pages.dev/minecraft-pixel-warfare.html)
- [LABUBU ADVENTURE](https://theskillquest.pages.dev/labubu-adventure.html)
- [CATEGORY 204828](https://thequizzone.pages.dev/category-204828.html)
- [SHAPE SHIFT](https://themindplays.pages.dev/shape-shift.html)
- [RESCUE HERO](https://thelearnquesters.pages.dev/rescue-hero.html)
- [HARD ROCK ZOMBIE TRUCK](https://themindplay.pages.dev/hard-rock-zombie-truck.html)
- [TIKTOK STREET STYLE](https://themindplays.pages.dev/tiktok-street-style.html)
- [MEMORY WARS](https://iskillquest.pages.dev/memory-wars.html)
- [SPIDER ROPE HERO CITY FIGHT](https://themindplay.github.io/spider-rope-hero-city-fight.html)
- [CATEGORY COOKING](https://themindplay.github.io/category-cooking.html)
- [SCP 173 ESCAPE](https://themindplay.github.io/scp-173-escape.html)
