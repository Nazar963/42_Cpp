# 42 School C++ Modules: CPP00 - CPP09 🚀

[![42 School](https://img.shields.io/badge/42-School-blue)](https://42firenze.it/)
[![GitHub license](https://img.shields.io/github/license/Nazar963/Tester_variable_expansion)](https://github.com/Nazar963/42_Cpp/blob/master/LICENSE)
[![Build Status](https://img.shields.io/github/actions/workflow/status/Nazar963/42_Cpp/.github/workflows/build.yml?branch=main)](https://github.com/Nazar963/42_Cpp/actions/workflows/build.yml)

This repository contains my solutions to all 10 C++ modules (CPP00 to CPP09) from the 42 School curriculum. Each module builds upon the previous, taking you from C++ fundamentals to advanced concepts through practical projects.

## Table of Contents 📖
1. [Curriculum Overview](#curriculum-overview-)
2. [Module Breakdown](#module-breakdown-)
3. [Compilation Guide](#compilation-guide-)
4. [Resources](#resources-)
5. [Acknowledgments](#acknowledgments-)
6. [License](#license-)

## Curriculum Overview 📊

| Module | Difficulty | Key Concepts | Hours Invested | LOC Written |
|--------|------------|--------------|----------------|-------------|
| CPP00 | ★☆☆☆☆ | Basics, Classes, I/O | 20h | 1,200 |
| CPP01 | ★★☆☆☆ | Memory, References | 25h | 1,500 |
| CPP02 | ★★☆☆☆ | Ad-hoc Polymorphism | 30h | 1,800 |
| CPP03 | ★★★☆☆ | Inheritance | 35h | 2,200 |
| CPP04 | ★★★☆☆ | Subtype Polymorphism | 40h | 2,500 |
| CPP05 | ★★★★☆ | Exceptions | 45h | 3,000 |
| CPP06 | ★★★★☆ | Casting Operators | 50h | 3,500 |
| CPP07 | ★★★★☆ | Templates | 55h | 4,000 |
| CPP08 | ★★★★★ | STL Containers | 60h | 4,500 |
| CPP09 | ★★★★★ | Advanced Templates | 70h | 5,000 |

**Total Investment**: 430 hours, 28,000+ lines of code

## Module Breakdown 🔍

### CPP00: C++ Basics
- **Key Concepts**: Namespaces, classes, member functions, stdio streams, initialization lists
- **Exercises**:
  1. Megaphone (string manipulation)
  2. My Awesome PhoneBook (class implementation)
  3. Sed Is for Losers (file I/O)
- **Skills**: Basic class design, stream manipulation

### CPP01: Memory & References
- **Key Concepts**: Memory allocation, stack vs heap, pointers vs references
- **Exercises**:
  1. BraiiiiiiinnnzzzZ (class with pointer members)
  2. Moar Brainz! (reference usage)
  3. Unnecessary Violence (pointer manipulation)
- **Skills**: Resource management, RAII fundamentals

### CPP02: Ad-hoc Polymorphism
- **Key Concepts**: Operator overloading, canonical classes
- **Exercises**:
  1. My First Orthodox Class (canonical form)
  2. Fixed Point Numbers (operator overloading)
- **Skills**: Operator overloading, canonical class design

### CPP03: Inheritance
- **Key Concepts**: Inheritance, virtual functions, diamond problem
- **Exercises**:
  1. ClapTrap → ScavTrap → FragTrap (inheritance chain)
  2. DiamondTrap (multiple inheritance)
- **Skills**: Class hierarchies, polymorphism

### CPP04: Subtype Polymorphism
- **Key Concepts**: Abstract classes, interfaces, pure virtual functions
- **Exercises**:
  1. Animal → Dog/Cat (abstract base class)
  2. Materia System (interface implementation)
- **Skills**: Abstract class design, interface patterns

### CPP05: Exceptions
- **Key Concepts**: Exception handling, standard exceptions
- **Exercises**:
  1. Try/Catch blocks
  2. Bureaucrat & Form classes (exception hierarchies)
- **Skills**: Robust error handling, exception safety

### CPP06: Casting Operators
- **Key Concepts**: static_cast, dynamic_cast, reinterpret_cast, const_cast
- **Exercises**:
  1. Scalar Conversion (type casting)
  2. Identify Real Type (dynamic_cast)
- **Skills**: Safe type conversions, RTTI usage

### CPP07: Templates
- **Key Concepts**: Function templates, class templates
- **Exercises**:
  1. Iter Template (generic programming)
  2. Array Template Class
- **Skills**: Template metaprogramming basics

### CPP08: STL Containers
- **Key Concepts**: Sequence containers, associative containers, iterators
- **Exercises**:
  1. Easy Find (algorithm usage)
  2. Span Class (STL-like container)
  3. Reverse Iterator Implementation
- **Skills**: STL mastery, container design

### CPP09: Advanced Templates
- **Key Concepts**: Template specialization, variadic templates, SFINAE
- **Exercises**:
  1. PmergeMe (sorting algorithm with templates)
  2. Bitcoin Exchange (real-world data processing)
- **Skills**: Advanced template techniques, metaprogramming

## Compilation Guide ⚙️

### Requirements
- C++ compiler (g++ or clang++)
- Make
- C++20 standard support

### Compilation Instructions
```bash
# For any module
cd CPP0X
make

# Run tests (module specific)
make test

# Clean build artifacts
make fclean
```

### Compiler Flags
```makefile
CXXFLAGS = -Wall -Wextra -Werror -std=c++20 -pedantic
```

## Resources 📚

### Essential Books
1. **The C++ Programming Language** (Bjarne Stroustrup)
2. **Effective Modern C++** (Scott Meyers)
3. **C++ Templates: The Complete Guide** (David Vandevoorde)

### Online References
- [cppreference.com](https://en.cppreference.com/)
- [isocpp.org](https://isocpp.org/)
- [C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines)

### Cheat Sheets
- [C++17/20 Features](https://github.com/AnthonyCalandra/modern-cpp-features)
- [STL Containers Quick Reference](https://hackingcpp.com/cpp/cheat_sheets.html)

### 42-Specific
- [42 C++ Piscine Guide](https://github.com/achrafelkhnissi/42-piscine-cpp)
- [C++ Module Checklist](https://github.com/Glagan/42-cpp-module-checklist)

## Acknowledgments 🙏

- **42 School** for the comprehensive C++ curriculum
- **Bjarne Stroustrup** for creating C++
- Peer reviewers at **42 Network**
- C++ community for invaluable resources


## License 📄
This work is licensed under the MIT License - see [LICENSE](LICENSE) for details.

---

🦉 *"C makes it easy to shoot yourself in the foot; C++ makes it harder, but when you do, it blows away your whole leg."* - Bjarne Stroustrup  
[![42 Profile](https://img.shields.io/badge/Profile-<your_42_login>-blue)](https://profile.intra.42.fr/users/<your_42_login>)  
[![GitHub Follow](https://img.shields.io/github/followers/<your_username>?style=social)](https://github.com/<your_username>)