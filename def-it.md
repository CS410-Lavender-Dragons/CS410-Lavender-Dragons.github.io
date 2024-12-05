---
layout: sidebar
title: Data Types
---

# Definite Iteration of Oxide
Iteration is done through iterators. The for in construct can be used to iterate through the iterator.

Examples:
Range 1 inclusive to 100 exclusive
```
for n in 1..100 {
  if n % 15 == 0 {
    x = x + 2;
  } else {
    x = x + 3;
  }
}
```

Range 1 to 50 inclusive
```
for n in 1..=50 {
  if n % 5 == 0 {
    x = x + 1;
  } else {
    x = x - 1;
  }
}
```
