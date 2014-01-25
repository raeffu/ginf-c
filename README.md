### CPU folder

Simulate a CPU (central processing unit) in C. Some assembler
functions like LDA are implemented

To play around, execute:
```
> cd cpu/
> make graphic-main
> ./graphic-main
```

To test alu, execute
```
> ./graphic-main --memory/sipiu-codebase/test/*.mem
```

### ALU folder

Simulate a ALU (arithmetic logic unit) in C.

To play around, execute:
```
> cd alu/
> make alu-main
> ./alu-main
```

To test alu, execute
```
> alu/test.sh
```

### Strings folder

Functions to learn how to cope with strings in C. To test, execute:
```
> cd strings/
> make
> ./strings
```

### Pointers folder

Functions to learn how to cope with pointers in C. To test, execute:
```
> cd pointers/
> make
> ./ptr
```

### Test folder

To test random things in C:
```
> cd test/
> make
> ./test
```
