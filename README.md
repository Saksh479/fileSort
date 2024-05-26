# File Sorting Script
## Overview
This Python script is designed to sort files in a specified directory based on their file extensions. It moves files into subdirectories named after their respective file extensions.

## Usage
### Requirements:

> Python installed on your system.

> os and shutil modules are used in the script, which are part of Python's standard library.

## Instructions:
> Place the script in the directory containing the files you want to sort.

> Update the path variable to point to the directory you want to sort.

> Run the script.

## Behavior:
> The script iterates through all files in the specified directory.

> For each file, it extracts the file extension and checks if a corresponding subdirectory exists.

> If a subdirectory exists for the file extension, the file is moved into that subdirectory.

> If a subdirectory does not exist, it creates a new subdirectory for the file extension and moves the file into it.

Example
Suppose you have a directory D:\temp containing various files such as example.txt, image.jpg, document.pdf, etc. After running the script, the directory structure will be as follows:

D:\temp
│
├── txt
│   └── example.txt
│
├── jpg
│   └── image.jpg
│
└── pdf
    └── document.pdf

Notes
Empty files or files without extensions are skipped.
If a file with the same name already exists in the destination directory, it will be overwritten.
