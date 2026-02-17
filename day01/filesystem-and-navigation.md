# Linux Filesystem & Navigation

## Overview
Linux uses a single-root filesystem starting from `/`. Everything in the system is represented as a file or directory.

## Important Directories
- `/` – Root of the filesystem
- `/etc` – Configuration files
- `/var` – Variable data such as logs
- `/var/log` – Application and system logs
- `/home` – User home directories
- `/tmp` – Temporary files
- `/opt` – Optional / third-party applications

## Navigation Commands
### pwd
Prints the current working directory.

### cd
Used to change directories.

Examples:

- cd /  -> Root path
- cd /etc -> Config files directory
- cd /var/log  -> App & system logs
- cd ~  -> user's home directory
- cd -   -> pervious directory


### ls
used to list contents in a dir

- ls -> list the contents 
- ls -l -> long format
- ls -a  -> hidden files
- ls -h  -> human readable sizes


