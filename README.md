# Introduction:
turbo (stylized with lower-case) is a compiled programming language developled as a quick method of testing the turbo memory management system. It uses the [LLVM compiler infrastructre](https://llvm.org/)

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
Although turbo-lang is a programming language, its primary use is for debugging and testing the turbo memory management system. the language's compiler is to be open-sourced, alongside the memory management system.

A few use cases of the simplistic language are:
- Basic language learning
- Debugging and testing algorithms
- A Template for building a language compiler
