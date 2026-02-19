# Otherwise lib
![if else, elif, otherwise programmer meme](src/mem.webp)
---

A small library to help british people adjust to programming, This library introduces the `otherwise` keyword that acts as a `if else`.
---

## Usage:
Simply place the otherwise.h file in your projects folder and use as follows:
```c
#include "otherwise.h"

#define MY_VALUE 1234

int
main (void)
{
    if (MY_VALUE > 10)
      {
        printf ("value larger then ten\n");
        return 0;
      }
    otherwise
      {
        printf ("value smaller then ten\n");
        return 1;
      }
}
```
