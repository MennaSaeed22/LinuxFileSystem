# File System Implementation in Linux

## Overview
This project involves the implementation of a file system using a hierarchical structure similar to that of Linux. The file system organizes files and directories, providing functionalities for storage, organization, manipulation, and retrieval of data. This readme provides an overview of the implemented file system and its functionalities.

## File System Structure
The file system is structured as a single hierarchy of files with one top-level root directory, similar to the file system in Linux. Under the root directory, files and subdirectories are organized in a tree-like structure, allowing for an almost limitless depth of nesting.

## Types of Files
The implemented file system supports the following attributes and actions for files:

### Attributes
- **Name**: Human-readable name of the file.
- **Identifier**: Unique number identifying the file within the file system.
- **Location**: Logical path where the file is stored.
- **Type**: Type of the file (e.g., Document File).
- **Size**: Current size of the file.
- **Blocks**: Number of blocks occupied by the file.
- **Protection**: Access rights for reading, writing, and executing the file.
- **Creation Time**: Timestamp indicating when the file was created.
- **Modification Time**: Timestamp indicating when the file content was last modified.
- **Access Time**: Timestamp indicating when the file was last accessed.
- **Content**: Content of the file, stored as a string of characters.

### Actions and Functions
- Create File
- Read from File
- Write to File
- Copy File
- Move/Rename File
- Delete File
- Get File Information
- Change File Permissions

## Directory Structure
Directories in the file system are files with the directory type, which may contain children (files and subdirectories). The following attributes and actions are supported for directories:

### Attributes
- A directory is a file with the directory type.
- May have children (files and subdirectories).

### Actions and Functions
- Create a Directory (Folder)
- Delete a Directory
- List Directory Contents
- Get Directory Information
- Change Directory Permissions
- Search in Directory

## Root Node (Partition)
The root node represents the top-level partition in the file system. It includes the following attributes:

### Attributes
- Partition Label/Name
- UUID (Universally Unique Identifier)
- Size
- Used Space
- Free Space
- Block Size

## Implementation Details
The file system is implemented in Linux, utilizing system calls and data structures to manage files, directories, and partitions. It follows the hierarchical structure of Linux file systems, providing functionalities for file and directory management, as well as partition management.

## Contributors
This project was made possible through the contributions of the following individuals:
- **Menna Allah Saed**
- **Aya Ahmed**
- **Retaj Ayman**
- **Ahmed Salah**
