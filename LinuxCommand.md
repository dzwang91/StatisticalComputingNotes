# Udacity: Linux Command Line Bacis

## Lesson 1: Get into the shell

- What's a virtual machine? 
  - A virtual machine is a computer program that simulates a computer. 
  - When you set up your virtual machine you installed Linux on the VM, making Linux the guest operating system. The operating system that's installed directly on your physical computer is called the host OS. 
  - VirtualBox
  - Vagrant: ```vagrant up``` and ```vagrant ssh```
  
## Lesson 2: Shell commands  
  
## Lesson 3: The Linux filesystem  
  
--------------------------------------

# Commands

- ```rm file1```: delete the file1;
- ```rm -rf folder1```: delete the folder1; (DON'T USE IT! CAUTION!!)
- ```rm -r directory```: remove the directory; 
- ```pwd```: check current working directory;
- ```sysctl -n hw.ncpu```: chenk how many cores on mac;
- ```ls -l```: list the files in the current folder;
- ```ps -ax```: to list every process running, along with additional details such as PID, the elapsed running 
          and the process name and location.  
- ```scp -r sourcedirectory serverpath```: send the file to the server
- ```hostname```: my computer's network name
- ```cd <directory name>```: change directory; 
- ```cd ~```: back to home; 
- ```cd ..```: go back to the previous directory. 
- ```ls```: list directory
- ```rmdir <directory name>```: remove the empty directory;
- ```mkdir <directory name>```: make directory
- ```pushd <firectory name>```: push directory 
- ```popd```: pop directory (?)
- ```dirs```: show the directory
- ```cp <source> <target>```:copy a file or directory
- ```mv <source> <target>```: move a file or directory
- ```echo <some texts>```: print some arguments
- ```echo "some text" > filename```: write some text to the file
- ```touch <file name>```: make an empty file. 
- ```exit``` or ```Control-D```: log out 
- ```cat filename```: display contents of some file
- ```cat filename1 filename2```: display contents of file1 and file2  
- ```man commandname```: show manual page of the command
































