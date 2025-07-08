# Linux_Basics
# 06-03-2024
# Command Line Interface :
* Text Based Commands
* using Text Based Commands
* creating Multiple Files at a time using CLI TEXT BASED COMMANDS
* Then Open git Bash go to the particukar path
```
HARIKRISHNA@LAPTOP-S1ET7NA0 MINGW64 ~ (main)
$ cd Downloads/
```
* the command is
```
 touch file-{1..100}.txt
```
* here the ".." two dot;s are range from 1 to 100 and .txt is type of the file
```
HARIKRISHNA@LAPTOP-S1ET7NA0 MINGW64 ~/Downloads (main)
$ touch file-{1..100}.txt
```
* the another command is cat
* cat is a command for viewig text
* here we use to see the cpu info
```
$ cat /proc/cpuinfo
```
* i want to check the RAM of the memory
```
free -m
```
* Check the storage
* the command is "df -h"
```
HARIKRISHNA@LAPTOP-S1ET7NA0 MINGW64 ~ (main)
$ df -h
```
```
Filesystem            Size  Used Avail Use% Mounted on
C:/Program Files/Git  101G   95G  5.4G  95% /
D:                    137G   35G  103G  26% /d
```
* To see the IP Address
```

```
* to Konw the SHELL we use the command
```
echo $SHELL
```
```
HARIKRISHNA@LAPTOP-S1ET7NA0 MINGW64 ~ (main)
$ echo $SHELL
/usr/bin/bash
```
* To Know the name
* use the command is "uname -r "
```
HARIKRISHNA@LAPTOP-S1ET7NA0 MINGW64 ~ (main)
$ uname -r
3.4.10-87d57229.x86_64
```
* To create a Folder
```
mkdir
```
```
HARIKRISHNA@LAPTOP-S1ET7NA0 MINGW64 ~ (main)
$ cd Downloads/

```
```
HARIKRISHNA@LAPTOP-S1ET7NA0 MINGW64 ~/Downloads (main)
$ mkdir aws
```
* for creating multiple folders
```
HARIKRISHNA@LAPTOP-S1ET7NA0 MINGW64 ~/Downloads (main)
$ mkdir rrrr azure
```
* I want to create a file
* use the command is " touch "
```
touch aws.txt
```
```
HARIKRISHNA@LAPTOP-S1ET7NA0 MINGW64 ~/Downloads (main)
$ touch aws.txt
```
* I want to create 10 files at a time
* use this command pattern
```
touch aws-{1..10}.txt
```
* use case :
```
HARIKRISHNA@LAPTOP-S1ET7NA0 MINGW64 ~/Downloads (main)
$ touch aws-{1..10}.txt
```
* you can jump into the present working directory to direct home directory
* just use this command
```
cd ~
```
* use case :
```
HARIKRISHNA@LAPTOP-S1ET7NA0 MINGW64 ~/Downloads/aws/aws-sub-1 (main)
$ cd ~
```

