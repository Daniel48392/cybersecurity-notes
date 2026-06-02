## What I learned:
- Kernel - central part of the operating system, it manages hardware and system resources for all running programs
- Windows Operating System GUI Fundamentals
- All linux configurational files are stored in the `/etc` directory you can then use `cat` to read the information from those files in the CLI
- System administrator - root on linux systems, administrator on windows systems, theses accounts have unrestricted access to the system


## Commands
### Linux
- `pwd` - print working directory
- `ls -1` - works like ls but with more information about the files
- `ls -al` - shows all files including hidden files with all information
- `~` - home directory symbol
- `find <starting_point> -name <filename>` example: `find ~ -name notes.txt` returns full file path to notes.txt from home directory
- `cat textfile.txt` - displays the contents of the file on the terminal
- `whoami` - displays your current username of the account your logged into
- `uname -a` - displays details about the OS, kernel version and architecture
- `uname` - displays only OS name
- `df` - shows available space on discs
- `df -h` - shows disc usage however adds G, K prefixes to make it more readable
- `history` - displays the history of commands used by the user
- `su - username` - switches user on the system
### Windows
- `dir` - shows all files in your current directory
- `dir /a` - shows all files including hidden
- `dir /s filename.txt` - locates the file and outputs the path, `/s` - searches all sub-folders from you current directory
- `type filename.txt` - prints the contents of the file to the command line
- `whoami` - displays your current username of the account your logged into
- `hostname` - displays windows machine name
- `systemInfo` - displays system info
- `ipconfig` - shows basic network information
- `ssh username@ipaddress` - used to get secure remote access to a computer
