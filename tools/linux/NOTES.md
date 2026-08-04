# WSL Guide

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
