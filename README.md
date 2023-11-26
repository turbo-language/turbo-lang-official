# Introduction:
Turbo is a compiled programming language developled as a quick method of testing the complementary memory management system. It uses the [LLVM compiler infrastructure](https://llvm.org/).

turbo provides low level memory control while contiaining a simplistic syntax.

_turbo_:
```python
def my_fun() -> int {
  let x = 1;
  let my_str = "Hello World";

  if (x == 1 or my_str.len() == 10) {
      return 0;
  }
}
```

_Python_:
```python
def my_fun():
  x = 1
  my_str = "Hello World"

  if x == 1 or len(my_str) == 10:
    return 0
```

_C++_:
```c++
int main(){
  int x = 1;
  string myStr = "Hello World";

  if !(x == 1 || myStr.size() == 10) {
      return -1;
  }
  return 0;
}
```

# Use-Cases
The language's compiler is to be open-sourced, alongside the memory management system. 

A few use-cases of the simplistic language are:
- Basic language learning
- Debugging and testing algorithms
- A Template for building a language compiler


# Compiling turbo code
Run the rust project to get started.
```
cargo run turbo {main.turbo} <-- Your turbo file.
```

