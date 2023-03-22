# Bash: Exercise 4

Write a bash script to kill an active process.

## Preparation

Find the script "my\_sleep.sh" in this directory and try to guess what it does.
Make it executable.

## Task

Write a bash script named "kill\_sleep.sh" to do the following:
   - The script checks with the help of the command 'ps' if process named 'my\_sleep.sh' is running.
   - If 'my\_sleep.sh' is running, get its PID and kill it with the help of the command 'kill'.
   - Make the script executable.

To check that your script works, open a new terminal and run 'my\_sleep.sh'.

```bash
./my_sleep.sh
```

Now, open a second new terminal and run 'kill\_sleep.sh'. Was the sleeping process killed?

Let's try to do it again but with a slight modification. Run 'my\sleep.sh' this way:

```bash
nohup ./my_sleep.sh > output.txt 2> errors.log &
```

Now, in the same terminal do:

```bash
./my_sleep.sh
```

## Questions

What's in the files 'output.txt' and 'errors.log'?
What's the stdin, stderr and stdout of a process in Linux?
What's the function of '>' and '2>'?
What's the function of the command 'nohup' when the character '&' is at the end of the line?

