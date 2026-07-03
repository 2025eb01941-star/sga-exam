# Q2 Explanation

- The secure workspace structure was created with separate directories for docs, source files, and logs to keep the project organized.
- The permissions were tightened from the default state so the owner and group had controlled access, while other users were restricted.
- The `umask` value of `0022` influenced the initial default permissions for newly created files and directories.
- The chmod command for the log file failed because the shell split the file path at the line break, leaving the final target incomplete; the report captures that observed behavior.
