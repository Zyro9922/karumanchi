# karumanchi

DS Problems from karumanchi

## Known Issues

- Tower of Hanoi [Chapter 2]
- SLL Header File [Chapter 3] - **causes entire chapter 3 and some of chapter 4 problems to fail.**

## Latest Update

- Implemented Expression Tree algorithm in C++.
- Update BST ADT with optimised `remove()` method.

### Guide to run C++ Algos

- Clone this repo
- Install MinGW on Windows and g++ on macOS & Unix-like.
- Compile and run using:

```sh
$ g++ <FILENAME.cpp> -o <OUTPUT-BINARY-NAME>
$ "OUTPUT-BINARY-NAME" # on windows cmd
$ ./OUTPUT-BINARY-NAME # on macOS and Unix-like
```

Adding following flags in optional and depends on the users thugh are sugegsted to be used while developing-compiling locally:

- `-g` - turn on debugging (so GDB gives more friendly output)
- `-Wall` - turns on most warnings
- `-O or -O2` - turn on optimizations
- `-o <name>` - name of the output file
- `-c` - output an object file (.o)
- `-I<include path>` - specify an include directory
- `-L<library path>` - specify a lib directory
- `-l<library>` - link with library lib<library>.a

However, it is suggested that you use **_first, second and fourth_** (while compiling source files) for best results and local development.

### Guide to run JS Algos

- Install Node
- Clone this repo
- Open the `package.json` file to find the appropriate command under **scripts tag**.
- Run in a terminal in following fashion:

```sh
$ npm run <TAG-NAME-INSIDE-SCRIPTS>

# ex: to run stack.js in chapter 4
$ npm run stack

# OR, run directly via node
$ node ch4-stacks/stack.js
```

**NOTE:** Langauge formatting done automatically using VS Code IntelliSense. Better suggestions are welcome!

### License

© 2018 Sambhav Jain under GPL-v3.0