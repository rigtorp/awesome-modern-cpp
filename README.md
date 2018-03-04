---
---

# Awesome Modern C++

A collection of resources on modern C++.

The goal is to collect a list of resouces to help people learn about
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

* [The C++ Programming Language](http://www.amazon.com/dp/0321958322) (Bjarne Stroustrup) [C++11]
* [Effective Modern C++](http://www.amazon.com/dp/1491903996) (Scott Meyers) [C++11/14]
* [Overview of the New C++](http://www.artima.com/shop/overview_of_the_new_cpp) (Scott Meyers) [C++11/14]
* [C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines) (Bjarne Stroustrup, Herb Sutter) [C++11/14/17] - Guidelines for using modern C++.
* [C++ Concurrency in Action](http://www.cplusplusconcurrencyinaction.com) (Anthony Williams) [C++11/14/17] - Using the C++ Concurrency Library

For a comprehensive guide to C++ books see the
[Stackoverflow Definitive C++ Book Guide and List](http://stackoverflow.com/questions/388242/the-definitive-c-book-guide-and-list).

## Blogs

* [Andrzej's C++ blog](https://akrzemi1.wordpress.com/) - Guidelines and thoughts about C++.
* [C++ Hints](http://cpphints.com/) - Common mistakes and their solutions.
* [Embedded in Academia](http://blog.regehr.org/) - John Regehr, Professor of Computer Science, University of Utah, USA.
* [Eric Niebler](http://ericniebler.com/)
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
* [Anthony Williams' blog](https://www.justsoftwaresolutions.co.uk/blog/)

## Conferences

* [ACCU](http://accu.org/index.php/conferences) - The Conference for Developers.
* [C++ Now](http://cppnow.org/) - A gathering of C++ experts and enthusiasts.
* [CppCon](http://cppcon.org/) - The C++ Conference.
* [Meeting C++](http://meetingcpp.com/) - A independent C++ Conference.

## Libraries

This is not supposed to be a comprehensive list of all C and C++
libraries. It is a list of high-quality modern libraries with general
applicability (serialization, database, testing, etc) or high-quality
libraries with novel use of new C++ features.

* [autocheck](https://github.com/thejohnfreeman/autocheck) - QuickCheck and SmallCheck clones for C++.
* [Bandit](https://github.com/banditcpp/bandit) - A header-only framework for C++11 that wants to make working with unit tests a pleasant experience.
* [Beast](https://github.com/boostorg/beast) - HTTP and WebSocket built on Boost.Asio in C++11
* [Boost.Hana](http://boostorg.github.io/hana/) - Your standard library for metaprogramming.
* [Boost](http://www.boost.org/) - Collection of C++ libraries.
* [C++ Format](https://github.com/cppformat/cppformat) - Small, safe and fast formatting library for C++.
* [CAF](http://actor-framework.org/) - An Open Source Implementation of the Actor Model in C++.
* [Catch](https://github.com/philsquared/Catch) - A modern, C++-native, header-only, framework for unit-tests, TDD and BDD.
* [doctest](https://github.com/onqtam/doctest) - The lightest feature rich C++ single header testing framework.
* [cereal](https://github.com/USCiLab/cereal) - A C++11 library for serialization.
* [ChaiScript](http://chaiscript.com/) - An easy to use embedded scripting language for C++.
* [Cinder](https://libcinder.org/) - Cinder is a free and open source library for professional-quality creative coding in C++.
* [cpptoml](https://github.com/skystrife/cpptoml) - A header-only library for parsing TOML configuration files.
* [cppitertools](https://github.com/ryanhaining/cppitertools) - itertools (python) implementation for C++14
* [cpr](https://github.com/whoshuu/cpr) - C++ Requests: Curl for People, a spiritual port of Python Requests.
* [Crow](https://github.com/ipkn/crow) - Crow is very fast and easy to use C++ micro web framework.
* [cxxopts](https://github.com/jarro2783/cxxopts) -  Lightweight C++ command line option parser.
* [docopt.cpp](https://github.com/docopt/docopt.cpp) - docopt creates beautiful command-line interfaces.
* [date](https://github.com/HowardHinnant/date) - A date and time library based on the C++11/14/17 <chrono> header 
* [fixed_size_function](https://github.com/pmed/fixed_size_function) - Fixed size function wrapper like std::function.
* [Folly](https://github.com/facebook/folly) - Facebook Open-source Library.
* [iod](https://github.com/matt-42/iod) -  Meta programming utilities for C++14.
* [json](https://github.com/nlohmann/json) - JSON for Modern C++.
* [jsoncpp](https://github.com/open-source-parsers/jsoncpp) - A C++ library for interacting with JSON.
* [Junction](https://github.com/preshing/junction) - Concurrent data structures in C++.
* [mongo-cxx-driver](https://github.com/mongodb/mongo-cxx-driver) - C++ Driver for MongoDB.
* [mstch](https://github.com/no1msd/mstch) -  A implementation of Mustache templates using modern C++.
* [Mustache](https://github.com/kainjow/Mustache) - Mustache text templates in C++11.
* [Nonius](https://nonius.io/) - A C++ micro-benchmarking framework.
* [PEGTL](https://github.com/taocpp/PEGTL) - Parsing Expression Grammar Template Library (C++11, header-only).
* [pistache](http://pistache.io/) - An elegant C++ REST framework.
* [pybind11](https://github.com/pybind/pybind11) - Seamless operability between C++11 and Python.
* [random](https://github.com/effolkronium/random) - A simple, convenient, header only Random for modern C++.
* [rang](https://github.com/agauniyal/rang) - A simple, modern & header only C++11 library for colors in your terminal.
* [range-v3](https://github.com/ericniebler/range-v3) - Experimental range library for C++11/14/17.
* [rapidcheck](https://github.com/emil-e/rapidcheck) - QuickCheck clone for C++.
* [redox](https://github.com/hmartiro/redox) - Modern, asynchronous, and wicked fast C++11 client for Redis.
* [simple_match](https://github.com/jbandela/simple_match) - Simple header only pattern matching for c++14.
* [sol2](https://github.com/ThePhD/sol2) - C++ library binding to Lua.
* [sqlite3pp](https://github.com/iwongu/sqlite3pp) - C++ wrapper of SQLite3 API.
* [sqlite_orm](https://github.com/fnc12/sqlite_orm) - powerful header only SQLite3 ORM library for C++14
* [sqlpp11](https://github.com/rbock/sqlpp11) - A type safe SQL template library for C++.
* [tinyformat.h](https://github.com/c42f/tinyformat) - Minimal, type safe printf replacement library for C++.
* [tinytoml](https://github.com/mayah/tinytoml) -A header only C++11 library for parsing TOML.
* [tweeny](https://github.com/mobius3/tweeny) - A header only interpolation library with 30+ easing functions.
* [Vireo](https://github.com/twitter/vireo) - A lightweight and versatile video processing library by Twitter.
* [yaml-cpp](https://github.com/jbeder/yaml-cpp) - A YAML parser and emitter in C++.
* [ASAP](https://github.com/mobius3/asap) - header-only library to parse, display, operate and iterate on dates.

## Websites

* [C++ Questions Subreddit](https://www.reddit.com/r/cpp_questions) - A great place to get help.
* [C++ Samples](http://www.cppsamples.com/) - A repository of modern C++ samples.
* [C++ Subreddit](https://www.reddit.com/r/cpp) - Discussions, articles, and news about the C++ programming language.
* [C++ Super-FAQ](https://isocpp.org/faq) - The C++ Super-FAQ.
* [C++ reference](http://en.cppreference.com/w/) - C++ reference.
* [C++11 FAQ](http://www.stroustrup.com/C++11FAQ.html)
* [CppCast](http://www.cppcast.com) - The only podcast for C++ developers by C++ developers.
* [Stackoverflow C++11](http://stackoverflow.com/questions/tagged/c%2b%2b11)
* [Stackoverflow C++14](http://stackoverflow.com/questions/tagged/c%2b%2b14)
* [Stackoverflow C++](http://stackoverflow.com/questions/tagged/c%2b%2b)
* [The C++ Programming Language](https://isocpp.org/) - News, Status & Discussion about Standard C++.

## Talks

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

## Tools

* [American fuzzy lop](http://lcamtuf.coredump.cx/afl/) - American fuzzy lop is a security-oriented fuzzer.
* [cget](https://github.com/pfultz2/cget) - CMake package retrieval.
* [clang-format](http://clang.llvm.org/docs/ClangFormat.html) - A tool to format C++ code.
* [clang-tidy](http://clang.llvm.org/extra/clang-tidy/) - A clang-based C++ "linter" and static analysis tool.
* [CMake](https://cmake.org/) - Cross-platform family of tools designed to build, test and package software.
* [Compiler Explorer](https://gcc.godbolt.org/) - Interactively explore the assembly output of your C++ code.
* [conan](https://www.conan.io/) - C/C++ package manager.
* [cppcheck](http://cppcheck.sourceforge.net/) - Static analysis of C/C++ code.
* [C++ Archive Network](https://cppan.org/) - CPPAN - Cross-platform C/C++ package manager.
* [Hunter](https://github.com/ruslo/hunter) - Cross-platform package manager for C++.
* [irony-mode](https://github.com/Sarcasm/irony-mode) -  A C/C++ minor mode for Emacs powered by libclang.
* [modern-cpp-font-lock-mode](https://github.com/ludwigpacifici/modern-cpp-font-lock) - Syntax highlighting support for Modern C++ with emacs

## About

This list was compiled by **Erik Rigtorp** with help from the C++
community:

* [rigtorp.se](http://rigtorp.se)
* [erik@rigtorp.se](mailto:erik@rigtorp.se)
* [github.com/rigtorp](https://github.com/rigtorp)
* [twitter.com/rigtorp](https://twitter.com/rigtorp)
* [linkedin.com/in/rigtorp](https://www.linkedin.com/in/rigtorp)
