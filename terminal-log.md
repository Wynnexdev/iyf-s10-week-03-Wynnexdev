# Terminal Activity Log – Week 03

This file documents my experience using the **command line interface (CLI)** to complete the Week 03 assignment. The goal of this task was to understand how developers manage projects, navigate the file system, and perform file operations using terminal commands instead of graphical interfaces.

Through this exercise, I practiced navigating directories, creating and modifying files, searching for content, and managing project versions with Git.

---

## 1. Navigating the File System

To begin, I explored how to move between directories and inspect the current working environment using basic terminal commands.

Commands used:

- `pwd` – displays the current working directory
- `ls` – lists files and folders in the current directory
- `cd folder-name` – changes the current directory
- `cd ..` – moves one directory level up
- `cd ~` – returns to the home directory

These commands helped me understand how to move around the file system without using a graphical file explorer.

---

## 2. Creating Project Structure

I created the required project folder structure entirely using the terminal. This involved generating directories for source files, documentation, and tests.

Example commands used:

```bash
mkdir my-project
mkdir my-project/docs
mkdir my-project/tests
mkdir -p my-project/src/css
mkdir -p my-project/src/js
mkdir -p my-project/src/images