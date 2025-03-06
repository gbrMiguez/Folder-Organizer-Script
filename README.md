# Folder-Organizer-Script
The Folder Organizer Script is a Python script designed to automatically organize files in a specified directory (default: Downloads folder). It categorizes files based on their extensions, moves them into corresponding folders, and removes duplicate files.
Features

Automatically organizes files into predefined categories: Images, Documents, Videos, Archives, and Others.

Cleans up filenames by removing special characters and spaces.

Prevents duplicate files by deleting copies in the source folder.

Handles unknown file types by placing them in an "Others" folder.

Installation

Requirements

Ensure you have Python installed on your system. This script runs on Python 3.

Setup

Clone or download this repository.

Navigate to the script's directory.

Ensure all dependencies are installed (no external dependencies required for this script).

Usage

Save the script as organizer.py.

Open a terminal or command prompt.

Run the script using:

python organizer.py

By default, it organizes files from the Downloads folder. To specify a different directory, modify the downloads_folder variable in the script.

File Categories

The script organizes files into the following folders based on their extensions:

Category

Extensions

Images

.jpg, .jpeg, .png, .gif, .bmp

Documents

.pdf, .docx, .doc, .txt, .xlsx, .pptx

Videos

.mp4, .mkv, .mov, .avi

Archives

.zip, .rar, .tar, .gz

Others

Any unknown file types

Customization

You can customize the script by:

Adding or modifying file extensions in the file_categories dictionary.

Changing the source folder by modifying downloads_folder.

Enhancing duplicate handling to rename instead of deleting duplicates.
