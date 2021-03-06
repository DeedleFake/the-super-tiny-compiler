# The Super Tiny Compiler

You may have recently come across [The Super Tiny Compiler][1] project. I read
the code a handful of times back-to-back and decided to see if I could write a
compiler myself, in Go. This project essentially just a port of the original
one, which is written in JavaScript. With comments, it's around 1000 lines.

### Usage

```
$ git clone git@github.com:hazbo/the-super-tiny-compiler.git
$ cd the-super-tiny-compiler && go build -o tiny
$ ./tiny
```

Input: `(add 2 (subtract 10 5))`

Output: `add(2, subtract(10, 5));`

You can find the input towards the bottom of compiler.go.

---

[![cc-by-4.0](https://licensebuttons.net/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

[1]: https://github.com/thejameskyle/the-super-tiny-compiler
