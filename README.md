# 🎄 Advent of Code Template for Rust 🦀
Rust 🦀 project collection template **Advent of Code**! This template create new project in which you will be able to adding subprojects per day challenge.

## 🎁 What is Advent of Code?
Advent of Code is an annual coding event where participants solve daily programming puzzles throughout December. Each day brings a new challenge that tests your coding skills and problem-solving abilities.

## ❓Do you want to try it too?
If you want to get involved, check out the [adventofcode.com](https://adventofcode.com).

## 📌 To create new year project collection
You need to have installed [cargo-generate](https://github.com/cargo-generate/cargo-generate)
```bash
cargo install cargo-generate
```
After that you can create new year project collection by calling
Simply just call
```bash
cargo generate JKubovy/Advent-of-Code-Rust-Template --name aoc-2023
```

## 📌 To create new day project
Simply just call
```bash
cargo generate --path ./template --name dayXX
```

## 🎆 Day project
It has structure
 - `src/main.rs` self explanatory I guess
 - `inputs/input.txt` there you should copy your input text
 - `inputs/test.txt` there you should copy your test text

`main.rs` contains 4 tests (processing input and test file for first and second part of challenge). I've add test even for `input.txt` which you can use after solving the puzzle but it can be use to check code after refactoring.
You *just* need to implement functions `first_part` and `second_part` which take `&str` as parameter and returning u32 (which you need to change in some puzzles).
