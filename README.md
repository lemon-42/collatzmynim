## What is the collatz conjecture ?

The `collatz conjecture` is a unresolved problem in mathematics. It involves a simple sequence of numbers that starts with any positive integer. The sequence is generated by repeatedly applying the following rules:

- If the number is even, divide it by 2.
- If the number is odd, multiply it by 3 and add 1.

The conjecture states that no matter what positive integer you start with, the sequence will always eventually reach 1.

## Features

- Calculates Collatz sequences for a given range of numbers.
- Identification of the number with the longest Collatz sequence.
- Real-time display of maximum value updates.

## Run the program

1. Download and install [Nim](https://nim-lang.org/)
2. Clone the project 
```sh
git clone https://github.com/lemon-42/collatzmynim
```
3. Compile and run the program (or use [Nimble](https://github.com/nim-lang/nimble))
```sh
nim c -r src/collatzme.nim
```

- With [Nimble](https://github.com/nim-lang/nimble) : 
```sh
nimble run
```
