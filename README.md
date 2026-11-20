# Object Oriented Programming Using C++ — Lab Works

A collection of the 13 experiments from my Object Oriented Programming Using C++ lab manual. This repository keeps the experiment source code organized in one place for reference and practice.

## Experiments

| No. | Experiment | Source |
|---:|---|---|
| 01 | University Management System using Encapsulation and Constructors/Destructors | [experiment_01.cpp](experiments/experiment_01.cpp) |
| 02 | Runtime Polymorphism using Virtual Functions and Abstract Classes | [experiment_02.cpp](experiments/experiment_02.cpp) |
| 03 | Matrix Operations using Operator Overloading | [experiment_03.cpp](experiments/experiment_03.cpp) |
| 04 | Generic Stack and Queue using C++ Templates and Performance Comparison | [experiment_04.cpp](experiments/experiment_04.cpp) |
| 05 | Student Grade Analyzer using STL Algorithms and Lambda Expressions | [experiment_05.cpp](experiments/experiment_05.cpp) |
| 06 | Smart Pointer Behaviour using RAII and Standard Smart Pointers | [experiment_06.cpp](experiments/experiment_06.cpp) |
| 07 | Exception Safety in a Bank Account System using Custom Exception Classes | [experiment_07.cpp](experiments/experiment_07.cpp) |
| 08 | Move Semantics and Perfect Forwarding for a Resource-Heavy String Class | [experiment_08.cpp](experiments/experiment_08.cpp) |
| 09 | Singleton, Factory, and Observer Design Patterns | [experiment_09.cpp](experiments/experiment_09.cpp) |
| 10 | Multi-Threaded Producer–Consumer System | [experiment_10.cpp](experiments/experiment_10.cpp) |
| 11 | Type-Safe Unit Conversion Library using Templates and constexpr | [experiment_11.cpp](experiments/experiment_11.cpp) |
| 12 | Mini File System Simulator using File I/O Streams and Binary Serialization | [experiment_12.cpp](experiments/experiment_12.cpp) |
| 13 | Generic Data Pipeline using C++20 Modules, Concepts, and Ranges | [experiment_13 folder](experiments/experiment_13/) |

## Repository Structure

```text
.
├── README.md
└── experiments/
    ├── experiment_01.cpp
    ├── experiment_02.cpp
    ├── ...
    ├── experiment_12.cpp
    └── experiment_13/
        ├── pipeline.cppm
        ├── main.cpp
        └── CMakeLists.txt
```

## Requirements

- A C++ compiler such as GCC (g++) or Clang.
- A terminal or IDE to compile and run the programs.
- Experiments 1–12 use standard C++ features; choose a compiler version that supports the features used in each program.
- Experiment 13 requires C++20 module, concepts, and ranges support. Module support and build commands vary by compiler.

## Compile and Run

For a regular .cpp experiment, open a terminal in the repository folder and run:

```bash
g++ -std=c++17 experiments/experiment_01.cpp -o experiment
./experiment
```

Replace experiment_01.cpp with the experiment file you want to run. On Windows, run the generated program with:

```powershell
.\experiment.exe
```

For Experiment 10, you may need the thread linker option:

```bash
g++ -std=c++17 -pthread experiments/experiment_10.cpp -o experiment
./experiment
```

Experiment 13 is provided as separate C++20 module, source, and CMake files. Build it with a compiler and CMake version that support the required C++20 module workflow; exact commands depend on your toolchain.

## Topics Covered

- Object-oriented programming: encapsulation and polymorphism
- Operator overloading
- Templates and Standard Template Library (STL)
- Lambda expressions and STL algorithms
- RAII and smart pointers
- Exception handling
- Move semantics and perfect forwarding
- Design patterns
- Multithreading and synchronization
- C++20 concepts, modules, and ranges

## Note

This repository contains the 13 lab-manual experiments and their source files. Compiler support and execution steps may differ depending on your system and C++ toolchain.

---
Language: C++  |  Course: Object Oriented Programming Using C++