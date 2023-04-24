# ParaCL

ParaCL is a C-like programming language with an interpreter and a compiler. This language is designed to be simple and easy to learn, while also being powerful enough to express complex algorithms.

## Installation

To install ParaCL, you need to have Flex and Bison installed on your system. You also need LLVM for compiling ParaCL programs into machine code. Once you have these dependencies installed, you can clone this repository and build the interpreter and compiler using the following commands:

```
$ git clone https://github.com/vorontsov-amd/ParaCL.git
$ cd ParaCL
$ mkdir build && cd build
$ cmake .. && cmake --build .
```

This will build the interpreter and compiler and place them in the `bin` directory.

## Usage

### Interpreter

To use the interpreter, run the following command:

```
$ ./bin/paracl
```

This will start the interpreter in interactive mode, where you can enter ParaCL code directly and see the results immediately. You can also run a ParaCL script file using the following command:

```
$ ./bin/paracl script.pcl
```

This will run the script file and output the result to the console.

### Compiler

To compile a ParaCL program, use the following command:

```
$ ./bin/paraclc program.pcl -o program
```

This will compile the program and produce an executable file named `program`. You can then run the executable using the following command:

```
$ ./program
```

## Features

- Variables
- Arithmetic and logical expressions
- Control structures (if, while)
- Functions
- Arrays 
- Structures
- Input and output (console only)
- Error handling

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
