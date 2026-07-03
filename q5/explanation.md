# Q5 Explanation

- `lsblk` showed the available block devices and their partitions, while `mount` displayed the filesystems attached to the environment.
- `df -h` and `df -i` reported disk capacity and inode availability, helping assess whether the current storage layout was healthy.
- The reported values showed that the environment still had ample free space and inode capacity for the current workload.
- A small amount of cleanup and routine monitoring would help preserve storage health as the environment grows.
