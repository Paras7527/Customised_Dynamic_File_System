# 📁 Customised Virtual File System (CVFS)

## 1. Project Name
**Customised Virtual File System (CVFS)**

## 2. Technology Used
- **Programming Language:** C/C++
- **Libraries:**
  - `stdio.h`
  - `stdlib.h`
  - `iostream`
  - `string.h`
  - `unistd.h`

## 3. User Interface Used
- **Command-line interface (CLI)**

## 4. Platform Required
- **Operating System:** Linux/Unix-based systems (may run on Windows with minor modifications)
- **Compiler:** GCC/G++

## 5. Hardware Requirements
- **Processor:** Minimum 1 GHz
- **RAM:** Minimum 1 GB
- **Disk Space:** 50 MB free space

## 6. Project Description
This project simulates a virtual file system that allows users to perform basic file operations such as creating files, reading files, writing to files, deleting files, and more. It maintains a superblock and inode structure, mimicking the way real file systems manage data and metadata.

### Features:
- **Create New Files:**
  - Supports creating new files with specified permissions.
- **Open, Close, and List Files:**
  - Users can open and close files, as well as list all files in the virtual file system.
- **Read and Write Operations:**
  - Allows reading data from files and writing data to files.
- **Delete Files:**
  - Users can delete files and manage file descriptors effectively.
- **Truncation and Seek Operations:**
  - Implements file truncation to reduce file size.
  - Supports seeking within files to modify or read specific data.

---

This Customised Virtual File System is designed to provide a deeper understanding of how real-world file systems work by simulating core functionalities in a simplified manner.

Feel free to clone, modify, and experiment with this project to learn more about file system concepts!

---

**Note:** For best performance, it is recommended to run this project on a Linux/Unix environment.

