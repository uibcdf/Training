# Bash: Exercise 1

Write a bash script to automatically convert all jpg files in a directory to png.

## Preparation

Make manually a working directory with the required files following this instructions:
   - Make a new directory and get in to it.
   - Download with the command 'wget' the remote file https://upload.wikimedia.org/wikipedia/en/a/a9/Example.jpg
   - Rename the file as 'image.jpg'.
   - Copy 'image.jpg' as 'imaga.jpg' and 'imago.jpg' in the same working directory.
   - Create an empty text file named 'image.txt' with the help of the command 'touch' in the same working directory.

## Task

Write a bash script named "image\_conversion.sh" to do the following:
   - Convert all jpg files present in the same directory where the script is executed to png with the help of the command 'convert'.
   - Make the script executable.

The script has to be executed as follows in the working directory:

```bash
./image_conversion.sh
```

And the resulting action will produce the new files: 'image.png', 'imaga.png' and 'imago.png'.

**Note**: You probably need to install the linux package 'imagemagick' to use convert.
