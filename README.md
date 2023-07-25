# Hangman C++ Project

This is a fun console cpp hangman game

## Prerequisites

Before running the program, you need to have the following installed on your system:

1. C++ Compiler (GCC or Clang)
2. Git (optional, for cloning the repository)

## Cloning the Repository (Optional)

If you haven't already, you can clone this repository using the following command:

```bash
git clone https://github.com/mitchmares/hangman_cpp.git
cd hangman_cpp
```

## Compiling the Program
To compile you can use the provided compile.sh shell script

```bash
chmod +x compile.sh
```
or 
```bash
g++ main.cpp getRandomWord.cpp giveInstructions.cpp game.cpp checkmatch.cpp gameover.cpp displayGuess.cpp -o hangman
```

## Runnning the Program

Once the exe has been generated run the program:

```bash
./hangman
```

## Add your own Words

- You can add your own words by adding a new word every line
- It does not have to be 5 letter words
- Be carefull not to add any spaces (this will mess the program)# hangman_cpp
