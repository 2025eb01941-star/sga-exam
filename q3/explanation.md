# Q3 Explanation

- The hard link and original file shared the same inode, which showed that they were two names for the same underlying file.
- The symbolic link had a different inode and stored a path to the target file instead of sharing the file contents directly.
- Deleting the original file left the hard link intact, while the symbolic link broke because its target path no longer existed.
- This experiment demonstrates the difference between hard links and symbolic links in Linux.
