# Bash: Exercise 2

Write a bash script to make a simple filter over a text file.

## Preparation

Find in this directory a file named 'january.txt'. This files contains two columns with names ("Ana" o "Lisa") and cities.

## Task

Write a bash script named "where\_is.sh" to do the following:
   - Read via command line two input arguments:
      - A name ("Ana" o "Lisa")
      - The name of the text file to be filtered.
   - Print out with the help of the command 'grep' every line of the chosen text file fulfilling the next two conditions:
      - The name given by the first input argument is in the line.
      - The word "Budapest" is not in the line.
   - Make the script executable.

The script has to be executed in the terminal as follows in the working directory:

```bash
./where_is.sh Ana january.txt
```

Returning:
```bash
Ana	Madrid
Ana	Estocolmo
Ana	Ciudad de México
```
