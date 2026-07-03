# Q4 Explanation

- The shell opened the log file as a file descriptor, which allowed it to be accessed through the process without repeating the file path in every command.
- Standard output, standard error, and combined redirection were demonstrated using `>`, `2>`, and `2>&1` to show how Linux routes stream data.
- The `/proc/$$/fd` listing confirmed which file descriptors were active for the current shell process.
- The `ulimit` output showed the shell’s resource limits, including the high limit for open files.
