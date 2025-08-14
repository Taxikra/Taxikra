
basic linux 
+ inux is open-source, which means that its source code is freely 
available for anyone to view, modify, or distribute. This makes it 
easier for users to customize the operating system to their specific 
needs and allows developers to work together to improve its security 
and performance
+Top 50 Linux Commands You Must Know as a Regular User
  -ls : The most   frequently used command in Linux to list directories
  -pwd : Print working directory command in Linux
  -cd : Linux command to change directories
  -mkdir : Command used to create directories in Linux
  -mv : Move or rename files in Linux
  -cp : Similar usage as mv but for copying files in Linux
  -rm : Delete files or directories
  -touch : Create blank/empty files
  -ln : Create symbolic links (shortcuts) to other files
  -clear : Clear the terminal display
  -cat : Display file contents on the terminal
  -echo : Print any text that follows the command
  -less : Linux command to display paged outputs in the terminal
  -man : Access manual pages for all Linux commands
  -uname : Linux command to get basic information about the OS
  -whoami : Get the active username
  -tar : Command to extract and compress files in linux
  -grep : Search for a string within an output
  -head : Return the specified number of lines from the top
  -tail : Return the specified number of lines from the bottom
  -diff : Find the difference between two files
  -cmp : Allows you to check if two files are identical
  -comm : Combines the functionality of diff and cmp
  -sort : Linux command to sort the content of a file while outputting
  -export : Export environment variables in Linux
  -zip : Zip files in Linux
  -unzip : Unzip files in Linux
  -ssh : Secure Shell command in Linux
  -service : Linux command to start and stop services
  -ps : Display active processes
  -kill and killall : Kill active processes by process ID or name
  -df : Display disk filesystem information
  -mount : Mount file systems in Linux
  -chmod : Command to change file permissions
  -chown : Command for granting ownership of files or folders
  -ifconfig : Display network interfaces and IP addresses
  -traceroute : Trace all the network hops to reach the destination
  -wget : Direct download files from the internet
  -ufw : Firewall command
  -iptables : Base firewall for all other firewall utilities to interface with
  -apt, pacman, yum, rpm : Package managers depending on the distribution
  -sudo : Command to escalate privileges in Linux
  -cal : View a command-line calendar
  -alias : Create custom shortcuts for your regularly used commands
  -dd : Majorly used for creating bootable USB sticks
  -whereis : Locate the binary, source, and manual pages for a command
  -whatis : Find what a command is used for
  -top : View active processes live with their system usage
  -useradd and usermod : Add a new user or change existing user data
  -passwd : Create or update passwords for existing users
+function of command in linux :
  - ls : is command use lists files and directories in your system
    -R : lists all the files in the subdirectories.
    -a : shows all files, including hidden ones.
    -lh : converts sizes to readable formats, such as MB, GB, and TB.
    -latr : 
    
  - pwd : is command prints your current working directory’s path, like /home/directory/path
    -It supports two options. The -L or –-logical option prints environment variable content,
    including symbolic links. Meanwhile, -P or –physical outputs the current directory’s actual path
  
  - mkdir : is command to create one or multiple directories and set their permissions. 
      Ensure you are authorized to make a new folder in the parent directory
    -p — creates a directory between two existing folders. For example,
      mkdir -p Music/2023/Songs creates a new 2023 directory.
    -m — sets the folder permissions. For instance, enter mkdir -m777
      directory to create a directory with read, write, and execute permissions for all users.
    -v — prints a message for each created directory.

- rm : In the previous section, we deleted the Sample-Copy file. The rm command is used to delete files 
    and folders and is one of the important Linux commands you must know.
      
  - cp and mv : commands are equivalent to the copy-paste and cut-paste commands in Windows. 
        But since Linux doesn’t really have a command for renaming files, we also use the mv command 
        to rename files and folders.
        ex : we used cp 
        sample -> sample sample-copy
        ex : we used mv 
        sample changed sample-copy
  - touch : command in Linux creates an empty file or updates the timestamp of an existing file.
  - ln : To create a link to another file, we use the ln command. This is one of the most important
      Linux commands that you should know if you’re planning to work as a Linux administrator
  - clear : command in Linux clears the terminal screen. It removes all the text and output 
      currently displayed on the terminal and gives you a clean slate to work with.
  - The uname and whoami commands allow you to access some basic information that comes in handy 
      when you work on multiple systems.
    + The uname command in Linux displays information about the system’s kernel, 
      including the kernel name, hostname, kernel release, kernel version, and machine hardware name.
      Note: Some important flags you can use with the uname command.
        Use uname -s to display the kernel name.
        Use uname -n to display the hostname.
        Use uname -r to display the kernel release.
        Use uname -v to display the kernel version.
        Use uname -m to display the machine hardware name.
    + The whoami command in Linux returns the current user’s username. It stands for 
      “who am I?” and it’s often used to determine the current user’s identity in shell scripts or the terminal.
  - cal : command displays a well-presented calendar on the terminal. Just enter the command cal on your terminal prompt.
  - / is root
  
 
-- File Manipulation -- :
touch filename: Creates an empty file.
cat filename: Displays the contents of a file.
echo "text" > filename: Writes text to a new file (or overwrites an existing one).
grep "pattern" filename: Searches for a specific pattern within a file.
-- System Information --:
uname -a: Displays detailed system information (kernel version, etc.).
df -h: Shows disk space usage.
free -h: Shows memory usage.
uptime: Displays the system uptime.
top or htop: Displays real-time system processes.
find: Searches for files in a directory hierarchy.
tar: Archives files. Example: tar -cvf archive.tar folder/ creates an archive of a folder.
chmod: Changes file access permissions.
chown: Changes file owner and group.
ps: Displays information about running processes.
kill: Sends a signal to a process, typically to stop the process.
du: Estimates file space usage.
76
-- User and Group Management --:
useradd username: Creates a new user.
userdel username: Deletes a user.
passwd username: Changes a user's password.
sudo: Executes commands with elevated privileges (typically root). 
-- Package Management (with yum or dnf) --:
yum update: Updates installed packages.
yum install package_name: Installs a new package.
yum remove package_name: Removes a package.
yum list: Lists available packages.
-- Networking --:
ping ip_address: Tests network connectivity.
ifconfig or ip addr: Shows network interface configuration.
netstat or ss: Displays network connections and listening ports.
--  Important Notes --:
CentOS Linux 8 is now at end-of-life (EOL). 
CentOS Stream is the recommended alternative to CentOS Linux. 
You can access online documentation and tutorials for more in-depth learning. 
