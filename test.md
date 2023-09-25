---
author: John Doe
date: January 1, 2020
geometry: margin=1in
title: Sample Markdown to LaTeX+PDF with Pandoc
header-includes:
  - \hypersetup{colorlinks=true}
---

# 1.

I really like computer architecture. I like computer 
architecture more than:

 - money
 - gold
 - cars
 - iPhones

## This is a subsection

The proper procedure for starting a new computer architecture
design involves:

1. Coming up with the high-level design sketch
2. Initsialising your code space with git VCS
3. Designing each module one by one
4. Commiting changes to git often
4. Always writing unit-tests or testbenches for your
code

# 2.
Open source isn't free - its often funded by institutions.

This is a table:

| Project      | Roots                      |
|--------------|----------------------------|
| Verilator    | DEC.                       |
| BSD Unix     | Berkeley                   |
| Clang        | Apple, Berkeley University |
| Clang        | Berkeley                   |
| Chisel       | Berkeley                   |
| R            | Berkeley                   |
| Berkeley Sockets | Berkeley               |
| GCC          | MIT                        |
| Xorg         | MIT                        |
| Bluespec     | MIT                        |
| MIPS         | Stanford                   |
| ROS          | Stanford                   |
| Theano       | University of Montreal     |
| Firefox      | Netscape, Google           |
| TypeScript   | Microsoft                  |
| Linux Kernel | RedHat, IBM, Google        |
| Chromium     | Google                     |
| Android      | Google                     |

# This is a Latex Code

$$
\begin{pmatrix}
  1 & 2 & 3 \\
  4 & 5 & 6 \\
  7 & 8 & 9 \\
\end{pmatrix}
$$


# This is a third section

## Python

Python is a great language for rapid prototyping
and unit-testing.

Although Python is itself slow, it is often
coupled with speedy C/C++ backends allowing
for the best of both worlds.

One example of such is Python numpy.

### Sub-subsection

Some python code

```python
def sum(a,b)
    return a+b
```