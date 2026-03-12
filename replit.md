# C Lab: Listas y Pilas (Lists and Stacks)

## Project Overview
A C programming lab assignment focused on implementing List (ArrayList) and Stack data structures. Students implement functions in `exercises.c` and verify their work using `bash test.sh`.

## Structure
- `exercises.c` — Student implementation file (only file students should modify)
- `test.c` — Test suite (should not be modified)
- `arraylist.h` / `arraylist.c` — ArrayList TDA implementation
- `stack.h` — Stack TDA header
- `test.sh` — Compilation and test runner script
- `log` — Auto-generated test run log

## Build & Run
- **Compile & Test:** `bash test.sh`
- **Manual compile:** `gcc -g test.c -Wall -o a.out`
- **Run tests:** `./a.out`
- **Compiler:** GCC 14.3.0 (via Nix)

## Workflow
- **Start application** — Compiles and runs the test suite (console output)

## Notes
- This is a student lab; only `exercises.c` should be modified
- Git commands are not permitted per lab instructions
- Tests run automatically when `exercises.c` changes
