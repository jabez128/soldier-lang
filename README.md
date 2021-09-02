# soldier-lang
😀 a brianf**k-lang variant interpreter written with JavaScript

## Specification

soldier-lang is a fully turing complete language, it only accept 8 legal character:


|Character | Meaning|
|---|---|
|R|	Increment the data pointer (to point to the next cell to the right).|
|L|	Decrement the data pointer (to point to the next cell to the left).|
|A|	Increment (increase by one) the byte at the data pointer.|
|D|	Decrement (decrease by one) the byte at the data pointer.|
|O|	Output the byte at the data pointer.|
|I|	Accept one byte of input, storing its value in the byte at the data pointer.|
|S|	If the byte at the data pointer is zero, then instead of moving the instruction pointer forward to the next command, jump it forward to the command after the matching ] command.|
|E|	If the byte at the data pointer is nonzero, then instead of moving the instruction pointer forward to the next command, jump it back to the command after the matching [ command.|

------------------

> memory tricks:

> R for right

> L for Left

> A for Add

> D for Decrease

> O for output

> I for INput

> S for Start

> E for End

## Hello World Example

```
    AAAAAAAAAASRAAAAAAARAAAAAAAAAARAAARAAAALLLLDERAAORAOAAAAAAAOOAAAORRAAAAOLAAOLAAAAAAAAODDDDDDDDOAAAODDDDDDODDDDDDDDORAO
```

will output `Hello World`

