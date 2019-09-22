# Unix-command-summary
A break down of unix-based commands

1. man - Accessing On-Line Manual Pages
In the terminal, the "man" command looks up the manual page for a command. The format of man is:
man <commandname> for example
man ls
man pwd
man cat
  
2. pwd - Print the Working Directory
The "pwd" command prints the full pathname of your current working directory. The syntax for pwd is:
pwd for example
(base) gunz@DESKTOP-19EC1CK:~$pwd
/home/gunz

3. cd - Changing Directory
The "cd" command changes the current working directory to the directory speciﬁed. The format of cd is:
cd <directorypath>. If you do not specify directory, cd changes to your home directory for example
(base) gunz@DESKTOP-19EC1CK:~$ cd /
(base) gunz@DESKTOP-19EC1CK:/$ pwd 
/  (notice that the directory has changed to the root folder)
(base) gunz@DESKTOP-19EC1CK:/$ cd ~
(base) gunz@DESKTOP-19EC1CK:~$ pwd
/home/gunz (realize we have returned to the original home directory)
