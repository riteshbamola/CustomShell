# 🐚 MyCustomShell

A simple custom shell implemented in C, designed for Linux-based systems as part of our **Project Based Learning** curriculum.

---

## 💡 Project Overview

**MyCustomShell** is a lightweight, command-line interpreter built from scratch in C. It replicates core functionalities of standard Unix/Linux shells by accepting user input, parsing commands, and executing system calls or custom logic. This project is intended to provide hands-on experience with low-level system programming, process management, and Linux internals.

---

## 🚀 Key Features

- ✅ Execute standard Linux shell commands (like `ls`, `pwd`, `cd`, etc.)
- 🔧 Custom built-in commands:
  - `quit` – Exit the shell gracefully
  - `Ritesh` – Display a personalized developer message
- 🧠 Command parsing using `strtok` and `execvp`
- 👨‍💻 Custom command prompt: `@RITESHBAMOLA:~>`
- 👥 Child process creation using `fork()`
- 📂 Easy-to-read and extend source code

---

## 🛠️ Compilation & Execution

### 🔧 Requirements

- GCC Compiler (tested with `gcc 11+`)
- Linux-based environment (Ubuntu, WSL, Debian, Arch, etc.)

### 🧪 Compile and Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/YourUsername/MyCustomShell.git
   cd MyCustomShell
   gcc shell.c -o myshell
   ./myshell

   @RITESHBAMOLA:~> ls
   Desktop  Documents  Downloads

   @RITESHBAMOLA:~> Ritesh
   Custom Shell implemented By Ritesh...

   @RITESHBAMOLA:~> quit
   Exiting MyCustomShell...

   ```

2. **Run the shell**

   Run the compiled shell executable in your terminal. You can interact with it by typing commands, and
   observe the output. The custom commands (`quit` and `Ritesh`) are implemented within th
   shell.c file.

3. **Customize the shell**

   You can extend the functionality of the shell by adding more custom commands or modifying the existing ones. Th
   shell.c file is well-structured and easy to read, making it a great starting point for your
   custom shell development.
