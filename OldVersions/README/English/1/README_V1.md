
***

![/TinyOS_Logo.jpeg](/TinyOS_Logo.jpeg)

### Learning nesC

I am not too experienced with the nesC programming language at the moment. This document will go over my knowledge of the nesC language so far.

This document used version ? of the nesC programming language. The version will be listed with each example.

#### Comments in nesC

Comments in nesC are similar to languages lika C, C++, C#, Java, JavaScript, Google Go, etc.,

```nesc
// This is a single line comment
/* This is
a multi-line
comment */
```

This example works with every version of nesC.

#### Break keyword in nesC

nesC supports the `break` keyword:

```nesc
break
```

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

#### Hello World in nesC

A hello world program in nesC is similar to a C hello world program, as nesC intends to be an improved clone of C,

```nesc
interface hw() {
	printf("Hello World\n");
}
```

This example works with every version of nesC.

_/!\ This example has not been tested yet, and may not work_

#### Interface keyword in nesC

nesC commonly uses the `interface` keyword. It is similar to using `int main` and is used like so:

```nesc
interface nescinterface() {
	printf("Welcome to my nesC program!\n");
	break
}
```

This example works with every version of nesC.

_/!\ This example has not been tested yet, and may not work_

#### Return keyword in nesC

nesC supports the `return` keyword. It is used like so:

```nesc
interface returntoSender() {
	printf("Return to Sender\n");
	break
}
return returntoSender();
break;
```

This example works with every version of nesC.

_/!\ This example has not been tested yet, and may not work_

#### Read keyword in nesC

nesC supports the `read` keyword. I think it is used for reading files, but I am not sure. I feel that is what `#include` is for.

Here is how I have been using it:

```nesc
read(main.nc)
```

This example works with every version of nesC.

_/!\ This example has not been tested yet, and may not work_

#### Include keyword in nesC

nesC, like C, supports including header files. It is used like so:

```nesc
#include <header.h>
#include <header.nc>
```

This example works with every version of nesC.

_/!\ This example has not been tested yet, and may not work_

#### Char keyword in nesC

nesC supports the `char` keyword for defining characters. Here is how I have been using it:

```nesc
char("String character");
char("UTF-8");
```

This example works with every version of nesC.

_/!\ This example has not been tested yet, and may not work_

#### Int keyword in nesC

nesC supports the `int` keyword for defining integers. Here is how I have been using it:

```nesc
int y = 10;
printf(y);
```

This example works with every version of nesC.

_/!\ This example has not been tested yet, and may not work_

#### If and else statements in nesC

Like most programming languages, nesC supports `if` and `else` statements, and they are used like so:

```nesc
// If/Else statements in nesC
char s = "x is greater than y";
char t = "y is greater than x";
int x = 7;
int y = 10;
if x > y
	return s()
else
	return t()
```

This example works with every version of Elm.

_/!\ This example has not been tested yet, and may not work_


#### Source

The majority of my nesC knowledge comes from self-experimentation, and Wikipedia. Self experimentation didn't go far, and unfortunately the majority of knowledge currently comes from Wikipedia. I wanted to make source code more original, but there isn't any other way I would have written it.

#### Other knowledge of nesC

1. nesC is a curly bracket and semicolon language

2. nesC is a C-like programming language designed for the TinyOS operating system

3. nesC uses the `*.nc` file extension

4. nesC is spelled with all lowercase, except for the last letter. It is not to be spelled in any way other than this, even at the start of a sentence, or in an ALL CAPS RANT.

5. nesC is a language recognized by GitHub

6. nesC is an open source programming language.

7. No other knowledge of nesC at the moment.

***

**File version:** `1 (2022, Tuesday, April 19th at 3:25 pm PST)`

***
