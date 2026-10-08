# WSL Guide

Linux is a command line operating system based on unix. There are multiple operating systems that are based on linux.

Secure Shell (SSH) refers to a cryptographic network protocol used in secure communication between devices. SSH encyrpts data using cryptographic algorithm, such as advanced encryption system (AES) and is often used when logging in remotely to a computer or server.

## Dowloading steps:-

1. Open powershell on administration.
1. First wsl is installed or not by type ```wsl status``` or ```wsl -l -v```.
1. If not then install by ```wsl --install```.
1. After installation restart pc then automatically new terminal where write admin name and password (password not visisible is seem like black screen write two times).
1. If window don't open then go to powershell run as admistrator and type ```wsl --install -d Ubuntu``` then its installing after installed type admin name enter then password enter again retype password and wsl successfully downloaded.
1. Then its install and enjoy linux.

cmd

1. **cd ~ :** Going for home ubuntu director
1. **pwd :** Print present working directory
1. **cd / :** Going to root directory
1. **clear :** Clear terminal
1. **/ :** Forward slash
1. **\ :** Backward slash

### ls => content of directory [options] [files/directories]

1. **ls :** Show content of directory
1. **ls / :** Open contents of root directory
1. **ls /home/program :** Content shown by path
1. **ls [option] :** like **ls Downloads/** going in Download directory
1. **ls ../.. :** going in root directory
1. **ls -l:** Gives content in long formate
1. **ls -a :** Shown hidden files
1. **ls -al :** shown hidden and long formates of files
1. **ls -lS :** S shown sort by largest size of file
1. **ls Documents/*.html :** find all .html files inside Documents folder
1. **ls Documents/* . * :** finding file with dot
1. **ls [option] [files/directories]:**
1. **ls -lS > out.txt :** ">" Put content of ls in out.txt
1. **ls -d */ :** Show only all directory
1. **man ls:** man is a manual of command

### cd Command cd [directorie ]

1. **cd :** Moving from one directory to another
1. **cd :** Go to Home directory
1. **cd / :** Going to root directory
1. **cd ~ :** Going to home
1. **cd .. :** Going to above one directory
1. **cd Downloads/text/hello.html :** Access files by absolute path
1. **cd Download/ :** Access directories in current working directories

**Notes** How to navigate on directories which make with space like ```My books```. their are three way we can approach below:

1. **cd My\ books :** Use backward slash before second argument.
1. **cd "My books" :** Write directories with start with double quot
1. **cd 'My books' :** Write directories with start with single quot

### cat [option] [filename] Command

1. **cat :** Take input and print output
1. **cat text.txt :** Print data from ```text.txt``` file
1. **cat file1.txt file2.txt :** cat cmd displaying content of file or multiple files
1. **cat -b text.txt :** Line number to non-blank line
1. **cat -n text.txt :** Line to all line include blank lines
1. **cat -s text.txt :** squeezes blank lines to one blank line
1. **cat -E text.txt :** I adds ``$`` dollar symbol at the end of each line

Note: More about cat write ``man cat`` cmd.

1. **touch:** for creat file
1. **mkdir:** full name is make directory and purpose to create a folder
1. **cp:** Full name is copy and purpose is copy a file or folder
1. **mv:** Move a file or folder
1. **rm:** Remove a file or folder

### Introducing terminal text editors

1. **nano filename:** To create or edit a file using nano under terminal. we simple use "nano filename" --replacing "filename" with the name of the file you wish to edit.
1. **wget downloading_filename:** Tis command allows us to downlaod files from web via HTTP-- as if you were accessing the file in your browser.
1. **scp important.txt ubuntu@192.168.1.30:/home/ubuntu/transferred.txt:**, **scp ubuntu@192.168.1.30:/home/ubuntu/documents.txt notes.txt** Copy files & directories from your current system to a remote system, Copy files & directories from a remote system to your current system.
1. **Serving Files from your Host-WEB:** Python3's "HTTPServer" will serve the files in the directory where you run the command, but this can be changed by providing options that can be found within the manual pages. Simply, all we need to do is run ``python3 -m  http.server``.
