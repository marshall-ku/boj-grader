# [BOJ](https://www.acmicpc.net/) Grader

A cli tool to test if your code prints expected output as a given input.

Requirements: g++, python3

## Usage

1. Run `./start.sh` and enter the id of the problem to solve.
    - You can pass the id just in command line like `./start.sh 1000`
    - It removes old test cases and creates new cases.
    - You can add test cases by adding `input/$FILE_NAME` and `output/$FILE_NAME`.
2. Write your solution in `solution.cpp` or `solution.py`.
3. Run `./test.sh` to test your code.
    - It tries to run C++ by default.
    - You can specify language with -l argument like `./test.sh -l cpp(or c++)` or `./test.sh -l py(or python)`

## Adding solution files

You can add your solution file written in supported languages in `solutions/**/$PROBLEM_ID`.
