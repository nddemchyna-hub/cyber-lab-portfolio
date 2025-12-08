\# Basic Linux Commands



This file contains essential Linux commands for everyday administration, navigation, and troubleshooting.



---



\## \*\*1. Navigation\*\*



| Command        | Description                          |

|----------------|--------------------------------------|

| `pwd`          | Show current directory               |

| `ls`           | List files and directories           |

| `ls -la`       | List all files, including hidden, with details |

| `cd <dir>`     | Change directory                     |

| `cd ..`        | Go up one directory                  |

| `cd ~`         | Go to home directory                  |



---



\## \*\*2. File Operations\*\*



| Command                        | Description                         |

|--------------------------------|-------------------------------------|

| `touch <file>`                  | Create an empty file                 |

| `mkdir <dir>`                   | Create a new directory               |

| `cp <source> <destination>`     | Copy file or directory               |

| `mv <source> <destination>`     | Move or rename file or directory     |

| `rm <file>`                     | Remove a file                        |

| `rm -r <dir>`                   | Remove a directory recursively       |

| `cat <file>`                    | Display file content                 |

| `less <file>`                   | View file content page by page       |

| `head <file>`                   | Show first 10 lines of a file       |

| `tail <file>`                   | Show last 10 lines of a file        |



---



\## \*\*3. Permissions \& Ownership\*\*



| Command                            | Description                          |

|------------------------------------|--------------------------------------|

| `chmod <permissions> <file>`       | Change file/directory permissions    |

| `chown <user>:<group> <file>`     | Change owner and group of a file     |

| `ls -l`                            | View file permissions and ownership |



---



\## \*\*4. Process \& System Info\*\*



| Command                | Description                         |

|------------------------|-------------------------------------|

| `ps aux`               | Show all running processes           |

| `top`                  | Interactive process viewer           |

| `df -h`                | Show disk space usage in human-readable format |

| `free -h`              | Show memory usage in human-readable format |

| `uptime`               | Show system uptime                   |



---



\## \*\*5. Networking\*\*



| Command                       | Description                          |

|--------------------------------|--------------------------------------|

| `ifconfig` / `ip a`           | Show network interfaces              |

| `ping <host>`                  | Check connectivity to a host         |

| `netstat -tuln` / `ss -tuln`  | Show listening ports                 |

| `curl <url>`                   | Make HTTP requests from command line |



---



\## \*\*6. Package Management (Debian/Ubuntu)\*\*



| Command                        | Description                          |

|--------------------------------|--------------------------------------|

| `sudo apt update`               | Update package list                   |

| `sudo apt upgrade`              | Upgrade installed packages            |

| `sudo apt install <package>`    | Install a new package                 |

| `sudo apt remove <package>`     | Remove a package                      |

| `sudo apt autoremove`           | Remove unused packages                |



