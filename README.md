# Duplicate Files Remover for Google Drive
### Overview
This Python script is designed to help users manage duplicate images in a Google Drive folder. It automatically scans a specified folder, identifies images that have been uploaded multiple times (e.g., files with names that include (1), (2), etc.), and deletes those duplicates, keeping only the original files.

### Prerequisites
1. Google Colab environment
2. Access to Google Drive
3. Required libraries: os, re

### Usage
Mount your Google Drive in the Colab environment.
Specify the folder path where the images are stored.
Run the script. 
It will:
- List all files in the specified folder.
- Check each file name for duplicates based on the presence of numbers in parentheses.
- Delete any identified duplicate files.
#### Example
To use the script, replace the "folder_path" variable with the path to your desired Google Drive folder containing duplicate files. The script will automatically handle the rest.

### Note
Please ensure that the original files' names do not have parentheses with numbers, as these are used to identify duplicates.

### License
[MIT License]
