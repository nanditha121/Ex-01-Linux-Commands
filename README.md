# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
 ![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/7e25ae6b-d31d-4c63-afec-e19e6a0333cd)



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/c6aebd34-d526-46d5-9422-231b3a0f7748)


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/f5ae9861-6a69-490a-a8ea-4081557c9857)



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/099b200c-1203-48e4-990a-5d724295920b)



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/54217e03-022c-4c50-8cec-9ba4de43da28)



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..



![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/75cf9188-8ea4-4c66-9c70-ed079ad7326e)


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/95fcefe6-0b59-46f2-b6a1-8742fcc171b5)




### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/64511280-fee9-426f-b83c-bec57a868dc4)



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/73fe82d0-43d7-4322-9121-cee3680f1c6d)



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/a9db5a04-7d02-4b91-8300-1db0d63d3200)


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/14d84d49-1c57-43b9-9f20-8364c263ef9d)



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/5825ad37-2561-458d-a4b4-2a79b4e235b4)



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/297fe7e4-9413-4f0d-b3ce-358d2e966892)


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/90974df6-5532-4a11-9ef4-c01be1462a9b)



### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/35acc026-cba3-49be-9cd0-5fb97d8ffeb8)



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/5ceff69c-cecc-443c-a208-151fa3b31bce)


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name



![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/31055a23-1ae0-4dba-b888-889214dfe753)


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/089bf2d3-9eeb-4050-9890-8c36f157bec9)



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/df86ce11-e34e-4ccc-ae27-ad5aa850ce24)


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/2916d170-4ac5-4f80-a4b5-dbbeaba5c15c)
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/9a014669-7747-4334-825b-a2c4fe0c4e88)




### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..



![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/b72ab523-dfab-4131-bd16-1e10130bbc9e)



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/aab05fbc-dc87-4c95-b7a3-269902c22ba7)


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/036fafd4-5a1f-44cf-b1d8-d534a1c2839a)



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/63da506c-90a7-4b7e-9544-bced9e5cfa47)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/f0cfae45-274f-4484-970e-aec5d70ed39c)


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df


![image](https://github.com/nanditha121/Ex-01-Linux-Commands/assets/142209508/59348c01-2a08-41f3-b8fa-3c914348d647)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
