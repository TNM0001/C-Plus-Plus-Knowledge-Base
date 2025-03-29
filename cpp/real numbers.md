---
title: "Real numbers"
layout: default
---

In C++, **real numbers** are typically represented using two main data types: `float` and `double`.

`float` is used to store numbers with a decimal point. For example:

```cpp
float price = 99.99f;
```

The 'f' (or 'F') at the end of a decimal number is called a literal suffix, and it explicitly tells the compiler that this number should be treated as a float.

`double` is used to store numbers with a decimal point, but with double precision. float typically has 7 decimal digits of precision whereas double typically has 15-17 decimal digits of precision. For example:

```cpp
float f = 3.14159265359;
double d = 3.14159265359;
cout << f << endl; // Might print: 3.14159
cout << d << endl; // Might print: 3.14159265359
```
