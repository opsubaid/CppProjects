# CppProjects

![Language](https://img.shields.io/badge/Language-C%2B%2B-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

> A curated collection of C++ logic and systems engineering projects, archiving academic and personal growth in low-level programming - from Semester 1 fundamentals through advanced OOP implementation.

---

## 📑 Table of Contents

- [About This Repository](#-about-this-repository)
- [Projects Overview](#-projects-overview)
- [Repository Structure](#-repository-structure)
- [How to Navigate](#-how-to-navigate)
- [License](#-license)

---

## 🗂 About This Repository

This repository documents my C++ learning journey, semester by semester. Each project is a standalone program that targets a specific set of concepts - arrays, functions, OOP, memory management, and algorithmic thinking. The projects aren't polished products; they're honest snapshots of where my understanding was at each stage, progressively becoming more structured and complete.

The repo is intended to show growth over time - not just the ability to write code, but the discipline to organize, document, and revisit it.

---

## 🚀 Projects Overview

| #   | Project          | Semester   | Stack | Key Concepts                               | Folder                                                   |
| --- | ---------------- | ---------- | ----- | ------------------------------------------ | -------------------------------------------------------- |
| 1   | Tic-Tac-Toe Game | Semester 1 | C++   | Arrays, Functions, Input Validation, Loops | [`Semester-01_Tic-Tac-Toe/`](./Semester-01_Tic-Tac-Toe/) |
| 2   | Quiz Master      | Semester 2 | C++   | OOP, Classes, Structs, Vectors, STL        | [`Semester-02_Quiz-Master/`](./Semester-02_Quiz-Master/) |

---

## 📁 Repository Structure

```
CppProjects/
│
├── Semester-01_Tic-Tac-Toe/
│   ├── main.cpp          ← Two-player terminal game with score tracking
│   └── README.md
│
├── Semester-02_Quiz-Master/
│   ├── main.cpp          ← 30-question OOP quiz with registration & certificate
│   └── README.md
│
├── LICENSE
└── README.md             ← You are here
```

---

## 🔧 How to Navigate

Each project lives in its own subfolder and is fully self-contained - one `main.cpp` file per project.

**Clone the repository:**

```bash
git clone https://github.com/YOUR_USERNAME/CppProjects.git
cd CppProjects
```

**Compile any project individually:**

```bash
# Tic-Tac-Toe
g++ Semester-01_Tic-Tac-Toe/main.cpp -o tictactoe && ./tictactoe

# Quiz Master
g++ Semester-02_Quiz-Master/main.cpp -o quizmaster && ./quizmaster
```

Each project folder has its own `README.md` with full details on concepts covered, how to run it, and any known limitations.

---

## 📄 License

This repository is licensed under the [MIT License](./LICENSE). Feel free to reference or learn from the code.
