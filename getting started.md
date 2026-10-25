# 🚀 Getting Started with C Programming

Welcome to the C programming guide! This note covers everything you need to set up your environment, write your first C program, and compile it.

I have also included the link to a video which will guide you through the process.
https://youtu.be/mTCuN6HJXQ4

---

## 🛠️ Step 1: System Requirements & Setup

To write and run C programs on your computer, you need two main tools:
1. **A Text Editor / IDE:** Visual Studio Code (VS Code) is recommended.
2. **A C Compiler:** GCC (GNU Compiler Collection) translates your C code into machine code that your computer understands.

### Setting up GCC Compiler:
- **Windows:** Install **MinGW-w64** and add `C:\mingw64\bin` (or your installation path) to your system's Environment Variables.
- **Mac:** Open terminal and run `xcode-select --install` to get `clang`/`gcc`.
- **Linux:** Run `sudo apt update && sudo apt install build-essential` in your terminal.

---

## 💻 Step 2: VS Code Extensions

For the best experience in VS Code, install these extensions:
- **C/C++** (by Microsoft): Provides syntax highlighting, auto-completion, and debugging tools.
- **Code Runner**: Allows you to run C programs with a single click or keyboard shortcut.

---

## 📝 Step 3: Writing Your First C Program

Create a file named `hello.c` and paste the following code:

```c
#include <stdio.h>

int main() {
    // Print Hello, World! to the screen
    printf("Hello, World!\n");
    return 0;
}