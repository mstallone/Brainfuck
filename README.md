# Brainfuck
A simple Brainfuck JS Interpreter 

#### What is Brainfuck?
"Brainfuck is an esoteric programming language noted for its extreme minimalism. The language consists of only eight simple commands and an instruction pointer. Nevertheless, it was shown to be Turing-complete. It is designed to challenge and amuse programmers, and was not made to be suitable for practical use. It was created in 1993 by Urban Müller. The language's name is a reference to the vulgar term "brain fuck", which refers to things so complicated or unusual that they exceed the limits of one's understanding" ([Wikipedia](http://en.wikipedia.org/wiki/Brainfuck)).

#### What are the commands?
| Brainfuck   | C                  |
|:-----------:|--------------------|
| `>`         | ++ptr;             |
| `<`         | --ptr;             |
| `+`         | ++*ptr;            |
| `-`         | --*ptr;            |
| `[`         | while (*ptr) {     |
| `]`         | }                  |
| `.`         | putchar(*ptr);     |
| `,`         | *ptr = getchar();  |
