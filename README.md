![image](https://github.com/user-attachments/assets/1d8f6b19-2685-49e2-8fed-86e107a09929)

# This function mimics the behavior of the printf function.

## my ft_printf can do the following conversions:

• %c Prints a single character.

• %s Prints a string (as defined by the common C convention).

• %p The void * pointer argument has to be printed in hexadecimal format.

• %d Prints a decimal (base 10) number.

• %i Prints an integer in base 10.

• %u Prints an unsigned decimal (base 10) number.

• %x Prints a number in hexadecimal (base 16) lowercase format.

• %X Prints a number in hexadecimal (base 16) uppercase format.

• %% Prints a percent sign.

## manages any combination of the following flags:

  •'-';
  
  •'0';
  
  •'.';
  
  •The field minimum width under all conversions;
  
  •'#';
  
  •'+';
  
  •' '.

# 🛠️ Usage


**1. Compiling the library**

To compile, go to the library path and run:

```shell
$ make
```

**2. Using it in your code**

To use the library functions in your code, simply include its header:

```C
#include "ft_printf.h"
```

