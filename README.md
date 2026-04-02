# oss-audit--24BCE10818-
OSS VITYARTHI
Agastya Chitransh Shrivastav
24BCE10818
SCRIPT 1:
This Bash script is intended to produce a basic system audit report for an open-source software project. The script starts by declaring basic information such as the name of the student and the selected software. The script then proceeds to fetch critical system information such as the Linux kernel version, the current user, the system uptime, the distribution name, and the current date and time. The fetched system information is then presented in a clean and formatted manner using the echo command. The script illustrates the use of variables, system commands, and echo statements in the Linux operating system.
HOW TO RUN:
Step-by-Step Points
Variable Declaration
Stores user-defined values:
STUDENT_NAME → Student’s name
SOFTWARE_CHOICE → Selected software (Python)
Collecting System Information
Uses Linux commands with $( ):
uname -r → Kernel version
whoami → Current user
uptime -p → System running time
lsb_release -d | cut -f2 → Linux distribution
date → Current date & time
Command Substitution
$(command) stores command output into variables
Makes the script dynamic (auto-updates info)
Displaying Output
Uses echo to print:
Title and separators
Software and system details
OS license information
Formatting
Uses ===== lines for a structured and readable report

SCRIPT 2:
This is a Bash script used for checking the installation of a certain software package. In this case, the package being checked is the python3 package. This script will check if the package is installed on the system by using the command -v command. If the package is installed, it will confirm the installation and print the path of the package. If it is not installed, it will notify the user. The script will also have a case statement that will print a philosophy regarding the chosen open-source tool. This will show the importance of open-source tools in today's world.
HOW TO RUN:
Define Package Name
The variable PACKAGE="python3" stores the name of the software to check.
Check Installation
command -v python3 is used to check if the package exists in the system.
&>/dev/null hides output (clean terminal).
If Condition
If installed:
Prints confirmation message
Displays path of the executable
If not installed:
Prints "NOT installed"
Case Statement
Matches package name and prints a related message:
python3 → Python message
httpd → Apache message
vlc → VLC message
* → Default message for others
Output
Combines system check + informational message

SCRIPT 3:
This Bash script performs a disk and permission audit on critical system directories. The script checks if specific directories exist on the system. If they exist, it retrieves the permissions, ownership information, and disk usage of the directories. The script helps users understand the file structure and security of system files. Moreover, the script checks the existence of the Python configuration directory.

SCRIPT 4:
The following is a Bash script for a log file analyzer. This script will require a log file and a keyword as input, and it will count the occurrences of the keyword in the log file. It will also display a summary and show the last five lines of the log file where the keyword has occurred. 

SCRIPT 5:
The following is a Bash script for an Open Source Manifesto Generator. It engages the user in a dialogue by asking three questions regarding the usage and beliefs of open sources. Depending on the user’s feedback, it automatically produces a personalized manifesto in the form of a text file. This script shows how user input is handled, variables are used, files are written, and output is displayed in Linux.
