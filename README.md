# DZZE
Double Zero Zero Eight - Recreational Programming Language made from JavaScript named after my birthyear.
It's originally named `2008` but added another name (DZZE) for valid JavaScript function name.

```
// Double - 2
// Zero - 0
// Zero - 0
// Eight - 8

DZZE("220200082200202822022008220220082202222");
// hello
```

# Getting Started
Download the [file](2008.js) or use [cdn](https://cdn.jsdelivr.net/gh/dlvdls18/DZZE@main/2008.js).
You can also [Try it Online](#).

# Documentation
DZZE is a binary recreational programming language which obviously used binary.
To write your DZZE Code. Use the function `DZZE`.
```js
DZZE("220200082200202822022008220220082202222");
// hello
```

Every byte is splitted by number 8.
```
...8...8...8 -> [..., ..., ...]
```

To write your byte, just write a normal byte but replace `1` with `2`.
```
220200082200202822022008220220082202222
```

Each byte is converted to integer and converted to ASCII character.
```
2200202 -> e
```

***

To convert String to 2008, use `DZZE.valueOf`.
```js
DZZE.valueOf("hello");
// 220200082200202822022008220220082202222
```
