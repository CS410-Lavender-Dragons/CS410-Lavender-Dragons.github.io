---
layout: sidebar
title: Data Types
---

## Precedence and Associativity of Oxide

|Operator|Prec. & Assoc.|
|--------|--------------|
|* /|Left to right|
|+ - |Left to right|
|== != < > <= >=|Require parentheses when chaining comparison operators|
|&&|Left to right|
|&#124;&#124;|Left to right|
|.. ..=|Require parentheses|
|=|Right to left|
|( )|Explicitly modify precedence of subexpressions. Inner grouped expressions first. Left to right|
