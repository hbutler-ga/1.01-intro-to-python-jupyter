# Command Line Basics

## 🧭 Overview

This guide covers the essential command line tools you’ll use to navigate your system and manage files.

---

## ⚠️ Windows Users

If you're on Windows, install **Git Bash** before continuing:

* It provides a Unix-like terminal experience similar to Mac/Linux
* Download: https://git-scm.com/downloads

---

## 📂 Navigation Commands

### `pwd` (Print Working Directory)

Shows your current location in the file system.

```bash
pwd
```

---

### `ls` (List)

Lists files and folders in your current directory.

```bash
ls
```

Common flags:

```bash
ls -la   # shows hidden files and detailed view
```

---

### `cd` (Change Directory)

Move between directories.

```bash
cd folder_name
```

Examples:

```bash
cd ..        # move up one directory
cd ~         # go to home directory
cd /         # go to root directory
```

---

## 📁 File & Directory Management

### `mkdir` (Make Directory)

Creates a new folder.

```bash
mkdir my_folder
```

---

### `touch`

Creates a new file.

```bash
touch file.txt
```

---

### `rm` (Remove)

Deletes files or directories.

```bash
rm file.txt
rm -r folder_name
```

⚠️ Be careful — this is permanent.

---

### `cp` (Copy)

Copies files or directories.

```bash
cp file.txt copy.txt
cp -r folder_name folder_copy
```

---

### `mv` (Move / Rename)

Moves or renames files.

```bash
mv file.txt new_name.txt
mv file.txt /path/to/location
```

---

## 🔍 Helpful Commands

### `clear`

Clears your terminal screen.

```bash
clear
```

---

### `open` (Mac only)

Opens a file or folder.

```bash
open .
```

---

### `history`

Shows previous commands.

```bash
history
```

---

## 💡 Pro Tips

* Use `Tab` to autocomplete file/folder names
* Use ↑ / ↓ arrows to cycle through previous commands
* Keep your directory structure organized

---

## 🧭 Summary

| Command | Purpose                |
| ------- | ---------------------- |
| `pwd`   | Show current directory |
| `ls`    | List files             |
| `cd`    | Navigate directories   |
| `mkdir` | Create folder          |
| `touch` | Create file            |
| `rm`    | Delete                 |
| `cp`    | Copy                   |
| `mv`    | Move / rename          |

---

This is all you need to be productive in the terminal.
