# An introduction to compilers

## Compilers and languages

A compiler is a program that translates a source language text into an equivalent
target language text.

E.g. for a C compiler, the source language is C while the target language may be
Sparc assembly language.

Of course, one expects a compiler to do a faithful translation, i.e. the meaning of
the translated text should be the same as the meaning of the source text.

```c
#include <stdio.h>

int
main(int,char**)
{
	int x = 34;
	x = x*24;
	printf("%d\n",x);
}
```

## resources
  - http://tinf2.vub.ac.be/~dvermeir/courses/compilers
