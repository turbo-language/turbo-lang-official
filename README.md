# Introduction:
turbo (stylized with lower-case) is a compiled programming language developed as a substitute to Rust and C++.

turbo provides low-level memory control while bringing the python readable syntax to a more C-based syntax.

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
