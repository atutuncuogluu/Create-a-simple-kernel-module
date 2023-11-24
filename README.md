# Create a kernel module

In this project we can simply implement a kernel module 

*We have 3 basic steps*

### Step 1:
create a module file (in this project our file is hello.c)

### Step 2:
compile the module file with Makefile (also we have Makefile you can check)

### Step 3:
Implement the module file:
after compiling we have some files endswith .ko (E.g  hello.ko)

use this command implement the module
`` sudo insmod hello.ko``


## Remove kernel module

simply you can use ``sudo rmmod hello ``

## List kernel modules

``sudo lsmod ``
