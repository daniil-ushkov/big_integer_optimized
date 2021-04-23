# big_integer_optimized

## Overview

Optimized C++ library implementing long arithmetic.

`big_integger` provides next constructors, functions and operators: 
- `int`, `uint_64t` and copy implicit
  constructors, as well as explicit string constructor;
- `swap` and `to_string` functions;
- Overloaded unary operators (`+`, `-`, and `~`);
- Overloaded increments and decrements (pre and post);
- Overloaded boolean operators (`==`, `!=`, `<`, `>`, `<=` and `>=`);
- Overloaded arithmetic binary operators (`+`, `-`, `/`, `*` and `%`);
- Overloaded bitwise binary operators (`&`, `|` and `^`) and bitwise shifts (`<<` and `>>`);


Division based on algorithm described in [article](https://surface.syr.edu/cgi/viewcontent.cgi?referer=&httpsredir=1&article=1162&context=eecs_techreports).

In `big_integer` implemented copy-on-write and small object optimizations.

## Testing
Where are 75 tests using `gtest` framework and  `mpz` module of `gmp` library.