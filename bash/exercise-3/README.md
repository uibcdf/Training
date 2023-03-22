# Bash: Exercise 3

Write a bash script to make some algebra with the values found in the columns of a text file.

## Preparation

Find in this directory a file named 'january.txt'. This files contains rows with four values (space separated): person, item, price and unit.

## Task

Write a bash script named "get\_total.sh" to do the following:
   - The script takes two input arguments via command line:
      - the name of a person ("Ana" or "Lisa")
      - the name of a file ("january.txt")
   - With the help of the command 'awk' read 'january.txt' and write a new file with two columns:
      - First column: the name of the item where the first value is the input person name.
      - Second column: the total price (price x unit) where the first value is the input person name.
   - The new file has to be named with the prefix 'total\_XXX\_' before the name of the input file (where XXX is the input person name).

The script has to be executed in the terminal as follows in the working directory:

```bash
./get_total.sh Lisa january.txt
```

Returning a new file named 'total\_Lisa\_january.txt' with the following content:

```bash
Apple 40.0
Banana 160.0
Peach 48.0
```
