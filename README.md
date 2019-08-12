---
---

# Awesome Modern C++

A collection of resources on modern C++.

The goal is to collect a list of resources to help people learn about
and leverage modern C++11 and beyond.

## Contributing

To add, remove or change things on the list:
[please submit a pull request to the GitHub repository](https://github.com/rigtorp/awesome-modern-cpp).

## Best Practices

- Consider the [C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines).
- Never manually format code, use [clang-format](http://clang.llvm.org/docs/ClangFormat.html).
- Build your code using [CMake](https://cmake.org/).
- Test your code using [Catch](https://github.com/catchorg/Catch2).
- Also test using sanitized builds: [AddressSanitizer, ThreadSanitizer and MemorySanitizer](https://github.com/google/sanitizers).
- Use a fuzzer to test untrusted input: [afl](http://lcamtuf.coredump.cx/afl/), [libFuzzer](http://llvm.org/docs/LibFuzzer.html), [KLEE](http://klee.github.io/).

## Books

* [A Tour of C++](https://www.amazon.com/Tour-2nd-Depth-Bjarne-Stroustrup/dp/0134997832/) (Bjarne Stroustrup) [C++11/17/20]
* [The C++ Programming Language](http://www.amazon.com/dp/0321958322) (Bjarne Stroustrup) [C++11]
* [Effective Modern C++](http://www.amazon.com/dp/1491903996) (Scott Meyers) [C++11/14]
* [Overview of the New C++](http://www.artima.com/shop/overview_of_the_new_cpp) (Scott Meyers) [C++11/14]
* [C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines) (Bjarne Stroustrup, Herb Sutter) [C++11/14/17] - Guidelines for using modern C++.
* [C++ Concurrency in Action](http://www.cplusplusconcurrencyinaction.com) (Anthony Williams) [C++11/14/17] - Using the C++ Concurrency Library
* [C++ Annotations](http://www.icce.rug.nl/documents/cplusplus/) (Frank B. Brokken) [C++11/14/17]
* [C++17 - The Complete Guide](http://www.cppstd17.com/) (Nicolai M. Josuttis) [C++17] - Giving guidance on how to use Language and Library Features of C++17
* [Professional CMake](https://crascit.com/professional-cmake/) (Craig Scott)

For a comprehensive guide to C++ books see the
[Stackoverflow Definitive C++ Book Guide and List](http://stackoverflow.com/questions/388242/the-definitive-c-book-guide-and-list).

## Community

### Conferences

* [ACCU](http://accu.org/index.php/conferences) - The Conference for Developers.
* [C++ CoreHard](http://conference.corehard.by/) (Minsk 🇧🇾, [Telegram](https://t.me/corehard_by)) - conference dedicated to C++ and related hardcore technologies. 
* [C++ Now](http://cppnow.org/) (Aspen, Colorado 🇺🇸, [YouTube](https://www.youtube.com/channel/UC5e__RG9K3cHrPotPABnrwg), [Twitter](https://twitter.com/cppnow)) - A gathering of C++ experts and enthusiasts.
* [C++ on Sea](https://cpponsea.uk/) (Folkestone, Kent 🇬🇧, [YouTube](https://www.youtube.com/channel/UCAczr0j6ZuiVaiGFZ4qxApw), [Twitter](https://twitter.com/cpponsea)) - The international C++ conference in the UK, by the sea.
* [Core C++](https://corecpp.org/) (Tel-Aviv 🇮🇱)
* [CppCon](http://cppcon.org/) (Aurora, Colorado 🇺🇸, [YouTube](https://www.youtube.com/channel/UCMlGfpWw-RUdWX_JbLCukXg), [Twitter](https://twitter.com/cppcon)) - The C++ Conference.
* [Meeting C++](http://meetingcpp.com/) (Berlin 🇩🇪, [YouTube](https://www.youtube.com/c/MeetingCPP), [Twitter](https://twitter.com/meetingcpp)) - A independent C++ Conference.

### Talks

TODO curate list of good talks on how to simplify code using C++11/17/20 features

* [CppCon Talks](https://www.youtube.com/user/CppCon/videos) - Talks from the C++ Conference.
* [CppCon 2014: Bjarne Stroustrup "Make Simple Tasks Simple!"](https://www.youtube.com/watch?v=nesCaocNjtQ)
* [CppCon 2014: Herb Sutter "Lock-Free Programming (or, Juggling Razor Blades), Part I"](https://www.youtube.com/watch?v=c1gO9aB9nbs)
* [CppCon 2014: Herb Sutter "Lock-Free Programming (or, Juggling Razor Blades), Part II"](https://www.youtube.com/watch?v=CmxkPChOcv)
* [CppCon 2014: Scott Meyers "Type Deduction and Why You Care"](https://www.youtube.com/watch?v=wQxj20X-tIU)
* [CppCon 2015: Bjarne Stroustrup "Writing Good C++14"](https://www.youtube.com/watch?v=1OEu9C51K2A)
* [CppCon 2015: Herb Sutter "Writing Good C++14... By Default"](https://www.youtube.com/watch?v=hEx5DNLWGgA)
* [CppCon 2016: Chandler Carruth “Garbage In, Garbage Out: Arguing about Undefined Behavior..."](https://youtu.be/yG1OZ69H_-o)
* [CppCon 2016: Herb Sutter "Leak-Freedom in C++... By Default."](https://youtu.be/JfmTagWcqoE)
* [CppCon 2017: Jason Turner "Practical C++17"](https://www.youtube.com/watch?v=nnY4e4faNp0)
* [code::dive conference 2014 - Scott Meyers: Cpu Caches and Why You Care](https://www.youtube.com/watch?v=WDIkqP4JbkE) ([slides](http://www.aristeia.com/TalkNotes/codedive-CPUCachesHandouts.pdf))
* [code::dive conference 2015 - Andrei Alexandrescu - Writing Fast Code I](https://www.youtube.com/watch?v=vrfYLlR8X8k) ([slides](http://codedive.pl/wp-content/uploads/2016/01/FastCode-handouts.pdf))
* [code::dive conference 2015 - Andrei Alexandrescu - Writing Fast Code II](https://www.youtube.com/watch?v=9tvbz8CSI8M) ([slides](http://codedive.pl/wp-content/uploads/2016/01/FastCode-handouts.pdf))
* [C++Now Talks](https://www.youtube.com/user/BoostCon/playlists) - Talks from the C++Now conference.
* [Going Native 2012: Variadic Templates are Funadic](https://www.youtube.com/watch?v=_zgq6_zFNGY)
* [Going Native 2013: Stephan T Lavavej - "Don't Help the Compiler"](https://www.youtube.com/watch?v=AKtHxKJRwp4)

### Blogs

* [Andrzej's C++ blog](https://akrzemi1.wordpress.com/) - Guidelines and thoughts about C++.
* [Anthony Williams' blog](https://www.justsoftwaresolutions.co.uk/blog/)
* [C++ Hints](http://cpphints.com/) - Common mistakes and their solutions.
* [Embedded in Academia](http://blog.regehr.org/) - John Regehr, Professor of Computer Science, University of Utah, USA.
* [Eric Niebler](http://ericniebler.com/)
* [Fluent C++](https://www.fluentcpp.com/) - Expressive Code in C++.
* [Guru of the Week (new posts)](http://herbsutter.com/gotw/) - A regular series of C++ programming problems created and written by Herb Sutter.
* [Guru of the Week (older posts)](http://www.gotw.ca/gotw/) - Older Guru of the Week posts.
* [Marshall's C++ Musings](https://cplusplusmusings.wordpress.com/)
* [Paul Fultz II's Blog](http://pfultz2.com/blog/)
* [Preshing on Programming](http://preshing.com/)
* [Simplify C++](http://arne-mertz.de/) - Write clean and maintainable C++.
* [Sticky Bits](https://blog.feabhas.com/) - A blog looking at developing software for real-time and embedded systems.
* [Sutter's Mill](http://herbsutter.com/) - Herb Sutter on software development.
* [The View from Aristeia](http://scottmeyers.blogspot.com/) -Scott Meyers' Professional Activities and Interests.
* [Visual C++ Team Blog](https://blogs.msdn.microsoft.com/vcblog/)
* [Why is a raven like a writing desk?](http://www.elbeno.com/blog/)

### Podcasts

* [CppCast](http://cppcast.com/) ([YouTube](https://www.youtube.com/channel/UCuCjADS4u3uJDTqUaG0H9dA), [Twitter](https://twitter.com/cppcast)) - The first podcast by C++ developers for C++ developers!
* [Cpp.chat](http://slashslash.info/cppchat/) ([YouTube](https://www.youtube.com/channel/UCsefcSZGxO9lTBqFbsV3sJg/featured), [Twitter](https://twitter.com/cppchat)) - Comments on c++ and issues of interest to c++ programmers.
* [C++ Weekly](https://www.youtube.com/c/JasonTurner-lefticus) - Educational videos by Jason Turner.

### Websites

* [C++ Best Practices](https://lefticus.gitbooks.io/cpp-best-practices/content/) - Collaborative Collection of C++ Best Practices.
* [C++ Patterns](https://cpppatterns.com/) - A repository of modern C++ patterns.
* [C++ Questions Subreddit](https://www.reddit.com/r/cpp_questions) - A great place to get help.
* [C++ reference](https://en.cppreference.com/w/)🔥 - C++ reference.
* [C++ Subreddit](https://www.reddit.com/r/cpp)🌟 - Discussions, articles, and news about the C++ programming language.
* [C++ Super-FAQ](https://isocpp.org/faq) - The C++ Super-FAQ.
* [C++11 FAQ](http://www.stroustrup.com/C++11FAQ.html)
* [Stackoverflow C++](https://stackoverflow.com/questions/tagged/c%2b%2b) / [C++11](https://stackoverflow.com/questions/tagged/c%2b%2b11) / [C++14](https://stackoverflow.com/questions/tagged/c%2b%2b14) / [C++17](https://stackoverflow.com/questions/tagged/c%2b%2b17) / [C++20](https://stackoverflow.com/questions/tagged/c%2b%2b20) - Stackoverflow questions about C++.
* [The C++ Programming Language](https://isocpp.org/) - News, Status & Discussion about Standard C++.

## Libraries

This is not supposed to be a comprehensive list of all C and C++
libraries. It is a list of high-quality modern libraries with general
applicability (serialization, database, testing, etc) or high-quality
libraries with novel use of new C++ features.

  
### Kitchensink / Framework

* [abseil](https://abseil.io/) - Abseil is an open-source collection of C++ code (compliant to C++11) designed to augment the C++ standard library.
* [Boost](http://www.boost.org/) - Collection of C++ libraries.
* [Folly](https://github.com/facebook/folly) - Facebook Open-source Library.
* [POCO](https://pocoproject.org/) - The POCO C++ Libraries are powerful cross-platform C++ libraries for building network- and internet-based applications that run on desktop, server, mobile, IoT, and embedded systems.
* [nonstd-lite](https://github.com/martinmoene/nonstd-lite) - Parent of *-lite repositories, a migration path to post-C++11 features for pre-C++11 environments

### Testing

* [Approval Tests for C++](https://github.com/approvals/ApprovalTests.cpp) - Native ApprovalTests for C++ on Linux, Mac and Windows.
* [autocheck](https://github.com/thejohnfreeman/autocheck) - QuickCheck and SmallCheck clones for C++.
* [Bandit](http://banditcpp.github.io/bandit/) - A header-only framework for C++11 that wants to make working with unit tests a pleasant experience.
* [Boost.Test](https://www.boost.org/doc/libs/1_70_0/libs/test/doc/html/index.html) - Boost testing framework.
* [Catch](https://github.com/catchorg/Catch2) 🔥 - A modern, C++-native, header-only, framework for unit-tests, TDD and BDD.
* [doctest](https://github.com/onqtam/doctest) 🚀 - The fastest feature-rich C++11/14/17/20 single-header testing framework for unit tests and TDD.
* [Fakeit](https://github.com/eranpeer/FakeIt) - A C++11 based simple mocking framework.
* [Googletest](https://github.com/google/googletest) - Google Testing and Mocking Framework.
* [rapidcheck](https://github.com/emil-e/rapidcheck) - QuickCheck clone for C++.

### Benchmarking

Libraries and frameworks for creating micro-benchmarks.

* [Celero](https://github.com/DigitalInBlue/Celero) - 
C++ Benchmark Authoring Library/Framework.
* [Google Benchmark](https://github.com/google/benchmark) 🌟 - A microbenchmark support library.
* [hayai](https://github.com/nickbruun/hayai) - the C++ benchmarking framework.
* [Nonius](https://nonius.io/) - A C++ micro-benchmarking framework.
C++ Benchmark Authoring Library/Framework.

### Logging

* [spdlog](https://github.com/gabime/spdlog) - Fast C++ logging library.

### Threading

* [concurrentqueue](https://github.com/cameron314/concurrentqueue) - A fast multi-producer, multi-consumer lock-free concurrent queue for C++11.
* [Cpp-Taskflow](https://github.com/cpp-taskflow/cpp-taskflow) - Modern C++ Parallel Task Programming Library
* [Junction](https://github.com/preshing/junction) - Concurrent data structures in C++.
* [MPMCQueue](https://github.com/rigtorp/MPMCQueue) - A bounded multi-producer multi-consumer lock-free queue written in C++11.
* [SPSCQueue](https://github.com/rigtorp/SPSCQueue) - A bounded single-producer single-consumer wait-free and lock-free queue written in C++11.
* [Threading Building Blocks](https://www.threadingbuildingblocks.org/) - Threading Building Blocks (TBB) is a C++ template library developed by Intel for parallel programming on multi-core processors. Using TBB, a computation is broken down into tasks that can run in parallel. The library manages and schedules threads to execute these tasks.

### Serialization

* [json](https://github.com/nlohmann/json) - JSON for Modern C++.
* [jsoncpp](https://github.com/open-source-parsers/jsoncpp) - A C++ library for interacting with JSON.
* [tinytoml](https://github.com/mayah/tinytoml) -A header only C++11 library for parsing TOML.
* [yaml-cpp](https://github.com/jbeder/yaml-cpp) - A YAML parser and emitter in C++.
* [cpptoml](https://github.com/skystrife/cpptoml) - A header-only library for parsing TOML configuration files.
* [cereal](https://github.com/USCiLab/cereal) - A C++11 library for serialization.

### String formatting & templating

* [{fmt}](https://fmtlib.net) - Small, safe and fast formatting library.
* [Inja](https://github.com/pantor/inja) - A Template Engine for Modern C++.
* [Mustache](https://github.com/kainjow/Mustache) - Mustache text templates in C++11.
* [tinyformat.h](https://github.com/c42f/tinyformat) - Minimal, type safe printf replacement library for C++.

### Scripting

* [sol2](https://github.com/ThePhD/sol2) - C++ library binding to Lua.
* [ChaiScript](http://chaiscript.com/) - An easy to use embedded scripting language for C++.
* [pybind11](https://github.com/pybind/pybind11) - Seamless operability between C++11 and Python.

### Web / HTTP

* [Beast](https://github.com/boostorg/beast) - HTTP and WebSocket built on Boost.Asio in C++11.
* [cpprestsdk](https://github.com/Microsoft/cpprestsdk) - The C++ REST SDK is a Microsoft project for cloud-based client-server communication in native code using a modern asynchronous C++ API design. This project aims to help C++ developers connect to and interact with services.
* [cpr](https://github.com/whoshuu/cpr) - C++ Requests: Curl for People, a spiritual port of Python Requests.
* [Drogon](https://github.com/an-tao/drogon) - A C++14/17 based, high-performance HTTP application framework
* [oat++](https://github.com/oatpp/oatpp) - High-performance Web framework (C++11, zero-dependency).
* [pistache](http://pistache.io/) - An elegant C++ REST framework.
* [restbed](https://github.com/Corvusoft/restbed) - Restbed framework brings asynchronous RESTful functionality to C++11 applications.

### Database

* [mongo-cxx-driver](https://github.com/mongodb/mongo-cxx-driver) - C++ Driver for MongoDB.
* [redox](https://github.com/hmartiro/redox) - Modern, asynchronous, and wicked fast C++11 client for Redis.
* [sqlite_orm](https://github.com/fnc12/sqlite_orm) - powerful header only SQLite3 ORM library for C++14.
* [sqlite3pp](https://github.com/iwongu/sqlite3pp) - C++ wrapper of SQLite3 API.
* [sqlpp11](https://github.com/rbock/sqlpp11) - A type safe SQL template library for C++.

### Misc

* [ASAP](https://github.com/mobius3/asap) - header-only library to parse, display, operate and iterate on dates.
* [BigIntegerCPP](https://github.com/ron4fun/BigIntegerCPP) - A C++11 large integer library with effective high performance, simplistic in nature and also clean in the eyes.
* [CAF](http://actor-framework.org/) - An Open Source Implementation of the Actor Model in C++.
* [Cinder](https://libcinder.org/) - Cinder is a free and open source library for professional-quality creative coding in C++.
* [Conduit](https://github.com/LoopPerfect/conduit) - High Performance Streams Based on Coroutine TS.
* [cppitertools](https://github.com/ryanhaining/cppitertools) - itertools (python) implementation for C++14
* [cxxopts](https://github.com/jarro2783/cxxopts) -  Lightweight C++ command line option parser.
* [date](https://github.com/HowardHinnant/date) - A date and time library based on the C++11/14/17 <chrono> header.
* [docopt.cpp](https://github.com/docopt/docopt.cpp) - docopt creates beautiful command-line interfaces.
* [EnTT](https://github.com/skypjack/entt) - A header-only, fast and, reliable entity-component system (ECS) for modern C++.
* [HashLib4CPP](https://github.com/ron4fun/HashLib4CPP) - C++11 library that provides an easy to use interface for computing hashes and checksums of strings, files, streams, bytearrays and untyped data to mention but a few. It also supports Incremental Hashing.
* [IntX](https://github.com/ron4fun/IntXLib4CPP) - A C++11 port of IntX arbitrary precision Integer library with speed, about O(N * log N) multiplication/division algorithms implementation.
* [iod](https://github.com/matt-42/iod) -  Meta programming utilities for C++14.
* [Magic Enum](https://github.com/Neargye/magic_enum) - Static reflection for enums (to string, from string, iteration) for modern C++, work with any enum type without any macro or boilerplate code.
* [Nameof](https://github.com/Neargye/nameof) - A header-only C++17 library provides nameof macros and functions to obtain the simple name of variable, type, function, macro, and enum.
* [PEGTL](https://github.com/taocpp/PEGTL) - Parsing Expression Grammar Template Library (C++11, header-only).
* [random](https://github.com/effolkronium/random) - A simple, convenient, header only Random for modern C++.
* [rang](https://github.com/agauniyal/rang) - A simple, modern & header only C++11 library for colors in your terminal.
* [range-v3](https://github.com/ericniebler/range-v3) - Experimental range library for C++11/14/17.
* [simple_match](https://github.com/jbandela/simple_match) - Simple header only pattern matching for c++14.
* [tweeny](https://github.com/mobius3/tweeny) - A header only interpolation library with 30+ easing functions.
* [Vireo](https://github.com/twitter/vireo) - A lightweight and versatile video processing library by Twitter.

## Tools

### Misc

* [clang-format](http://clang.llvm.org/docs/ClangFormat.html) 🌟 - A tool to format C++ code.
* [clangd](https://clang.llvm.org/extra/clangd/) - understands your C++ code and adds smart features to your editor: code completion, compile errors, go-to-definition and more.
* [Compiler Explorer](https://gcc.godbolt.org/) - Interactively explore the assembly output of your C++ code.
* [cquery](https://github.com/cquery-project/cquery) - C/C++ language server supporting multi-million line code base, powered by libclang. Emacs, Vim, VSCode, and others with language server protocol support. Cross references, completion, diagnostics, semantic highlighting and more
* [irony-mode](https://github.com/Sarcasm/irony-mode) -  A C/C++ minor mode for Emacs powered by libclang.
* [modern-cpp-font-lock-mode](https://github.com/ludwigpacifici/modern-cpp-font-lock) - Syntax highlighting support for Modern C++ with emacs
 
### [Dynamic analysis](https://en.wikipedia.org/wiki/Dynamic_program_analysis)

* [sanitizers](https://github.com/google/sanitizers) 🌟 - This project is the home for Sanitizers: AddressSanitizer, MemorySanitizer, ThreadSanitizer, LeakSanitizer, and more.
* [Valgrind](http://www.valgrind.org/) - is an instrumentation framework for building dynamic analysis tools. There are Valgrind tools that can automatically detect many memory management and threading bugs, and profile your programs in detail. You can also use Valgrind to build new tools.

### [Static analysis](https://en.wikipedia.org/wiki/Static_program_analysis)

* [cppcheck](http://cppcheck.sourceforge.net/) - is a static analysis tool for C/C++ code. It provides unique code analysis to detect bugs and focuses on detecting undefined behaviour and dangerous coding constructs. 
* [clang-tidy](http://clang.llvm.org/extra/clang-tidy/) 🌟 - is a clang-based C++ “linter” tool. Its purpose is to provide an extensible framework for diagnosing and fixing typical programming errors, like style violations, interface misuse, or bugs that can be deduced via static analysis. clang-tidy is modular and provides a convenient interface for writing new checks.
* [clang-analyzer](https://clang.llvm.org/docs/ClangStaticAnalyzer.html) - is a source code analysis tool that finds bugs in C, C++, and Objective-C programs. It implements path-sensitive, inter-procedural analysis based on symbolic execution technique.

### [Fuzzing](https://en.wikipedia.org/wiki/Fuzzing)

* [American fuzzy lop](http://lcamtuf.coredump.cx/afl/) - American fuzzy lop is a security-oriented fuzzer.
* [hongfuzz](http://honggfuzz.com/) - A security oriented, feedback-driven, evolutionary, easy-to-use fuzzer with interesting analysis options.
* [libFuzzer](https://llvm.org/docs/LibFuzzer.html) - A library for coverage-guided fuzz testing.

### [Build system](https://en.wikipedia.org/wiki/Build_automation)

* [build2](https://build2.org/) - is a cross-platform build toolchain for developing and packaging C and C++ code.
* [CMake](https://cmake.org/) 🌟 - Cross-platform family of tools designed to build, test and package software.
* [Meson](https://mesonbuild.com/) - is an open source build system meant to be both extremely fast, and, even more importantly, as user friendly as possible.

### [Package management](https://en.wikipedia.org/wiki/Package_manager)

* [Buckaroo](https://github.com/LoopPerfect/buckaroo) - Fully Decentralized Polyglot Package Manager for C++ and Friends
* [C++ Archive Network](https://cppan.org/) - CPPAN - Cross-platform C/C++ package manager.
* [cget](https://github.com/pfultz2/cget) - CMake package retrieval.
* [conan](https://www.conan.io/) - C/C++ package manager.
* [CPM](https://github.com/TheLartians/CPM) - A CMake script for setup-free cross-plattform dependency management.
* [Hunter](https://github.com/ruslo/hunter) - Cross-platform package manager for C++.
* [vcpkg](https://github.com/microsoft/vcpkg) - C++ Library Manager for Windows, Linux, and MacOS

## About

This list was compiled by **Erik Rigtorp** with help from the C++
community:

* [rigtorp.se](http://rigtorp.se)
* [erik@rigtorp.se](mailto:erik@rigtorp.se)
* [github.com/rigtorp](https://github.com/rigtorp)
* [twitter.com/rigtorp](https://twitter.com/rigtorp)
* [linkedin.com/in/rigtorp](https://www.linkedin.com/in/rigtorp)
