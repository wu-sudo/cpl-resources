
# lectures

## History of C
- [C (programming language) @ wiki](https://en.wikipedia.org/wiki/C_(programming_language)#CITEREFKernighanRitchie1978)
- [ANSI C @ wiki](https://en.wikipedia.org/wiki/ANSI_C)

## Types
- [C data types @ wiki](https://en.wikipedia.org/wiki/C_data_types)
- [size_t vs int in C++ and/or C @ stackoverflow](https://stackoverflow.com/questions/994288/size-t-vs-int-in-c-and-or-c)
- [sizeof @ wiki](https://en.wikipedia.org/wiki/Sizeof)
- [sizeof operator in C @ geeksforgeeks](https://www.geeksforgeeks.org/sizeof-operator-c/#:~:text=Sizeof%20is%20a%20much%20used,the%20size%20of%20its%20operand.&text=sizeof%20can%20be%20applied%20to,such%20as%20Structure%2C%20union%20etc.)
- [6.11 Incomplete Types @ docs.oracle.com](https://docs.oracle.com/cd/E19205-01/819-5265/bjals/index.html)
- [Incomplete Types @ docs.microsoft.com](https://docs.microsoft.com/en-us/cpp/c-language/incomplete-types?view=msvc-160)

## Expressions
- [What are lvalue and rvalue in C? @ jameshfisher.com](https://jameshfisher.com/2017/01/21/c-lvalue-rvalue/#:~:text=TL%3BDR%3A%20%E2%80%9Clvalue%E2%80%9D,as%20%E2%80%9Call%20other%20expressions%E2%80%9D.)
- [Operators in C and C++ @ wiki](https://en.wikipedia.org/wiki/Operators_in_C_and_C%2B%2B)

## Pointers
- [Pointer (computer programming) @ wiki](https://en.wikipedia.org/wiki/Pointer_(computer_programming))
- [Essentials: Pointer Power @ Computerphile](https://youtu.be/t5NszbIerYc)
- [Why use pointers @ stackoverflow](https://stackoverflow.com/questions/162941/why-use-pointers#:~:text=Pointers%20allow%20you%20to%20refer,components%20in%20your%20data%20structures.)
- [Why to specify a pointer type @ stackoverflow](https://stackoverflow.com/questions/38822692/why-to-specify-a-pointer-type)

## Memory Management
- [What happens in the kernel during `malloc`? @ stackoverflow](https://stackoverflow.com/q/5716100/1833118)
- [Inside memory management](https://developer.ibm.com/tutorials/l-memory/)
  - With a simplified implementation
- [Difference between `malloc` and `calloc`? @ stackoverflow](https://stackoverflow.com/q/1538420/1833118)
- [Do I cast the result of `malloc`? @ stackoverflow](https://stackoverflow.com/q/605845/1833118)
- [Why does `calloc` exist?](https://vorpus.org/blog/why-does-calloc-exist/)
- [difference between `stdlib.h` and `malloc.h` @ wiki](https://stackoverflow.com/questions/12973311/difference-between-stdlib-h-and-malloc-h)

## Library
- [C standard library @ wiki](https://en.wikipedia.org/wiki/C_standard_library)
- [GNU C Library @ wiki](https://en.wikipedia.org/wiki/GNU_C_Library)
- [C POSIX library @ wiki](https://en.wikipedia.org/wiki/C_POSIX_library)
  - [POSIX @ wiki](https://en.wikipedia.org/wiki/POSIX)
  - [unistd.h @ wiki](https://en.wikipedia.org/wiki/Unistd.h)
  - [ioctl @ wiki](https://en.wikipedia.org/wiki/Ioctl)
- [ncurses](../ui/README.md)

## Preprocessing
- [Include directive @ wiki](https://en.wikipedia.org/wiki/Include_directive)
- [include guard @ wiki](https://en.wikipedia.org/wiki/Include_guard)
- [Include guard optimisation](https://web.archive.org/web/20100819052043/http://www.bobarcher.org/software/include/index.html)
- [Redundant Include Guards](http://wiki.c2.com/?RedundantIncludeGuards)
- [pragma once @ wiki](https://en.wikipedia.org/wiki/Pragma_once)

## Programming Styles
- [Elements of Programming Style - Brian Kernighan](https://youtu.be/8SUkrR7ZfTA)
- [Google Style Guides](https://google.github.io/styleguide/)
  - [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
  - [davidzchen/sample-google.c](https://gist.github.com/davidzchen/9187878)
- [Camel case @ wiki](https://en.wikipedia.org/wiki/Camel_case)
- Tabs vs. Spaces
  - [Developers Who Use Spaces Make More Money Than Those Who Use Tabs @ stackoverflow](https://stackoverflow.blog/2017/06/15/developers-use-spaces-make-money-use-tabs/)
  - [WHY PROGRAMMERS WHO USE SPACES INSTEAD OF TABS MAKE MORE MONEY](https://insanelab.com/blog/notes/spaces-vs-tabs/#:~:text=The%20analysis%20performed%20by%20the,than%20their%20tab%20using%20counterparts.)
  - [Spaces vs. Tabs: A 20-Year Debate Reignited by Google’s Golang @ thenewstack.io](https://thenewstack.io/spaces-vs-tabs-a-20-year-debate-and-now-this-what-the-hell-is-wrong-with-go/)
  - [Tabs vs. Spaces: A scientific approach to an endless debate](https://kennethreilly.medium.com/tabs-vs-spaces-3c24defa7c9e)

## Specifications
- [Undefined behavior @ wiki](https://en.wikipedia.org/wiki/Undefined_behavior)
## Tools

### Memory Management
- [Valgrind](https://valgrind.org/)
  - > Valgrind is an instrumentation framework for building dynamic analysis tools.
      There are Valgrind tools that can automatically detect many memory management and threading bugs, and profile your programs in detail.
      You can also use Valgrind to build new tools.