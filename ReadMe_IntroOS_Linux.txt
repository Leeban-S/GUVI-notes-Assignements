-------------- DevOps Engineering Program-----------------
DevOps
Development + Operation

Is DevOps a technology?
Its not itself a technology either it is relying on different
tools and technologies to implement its principle

SDLC: Software Development lifecycle
lifecycle: series of steps or stages something goes through
from begining to end

Prerequisite:
1. Basic IT knowledge
2. Basic Computer Networking Knowledge
3. Basic Linux Understanding (OS understanding)
4. Scripting knowledge (Automate day to day tasks)

Reference Link
Create and Activate an AWS Account
https://repost.aws/knowledge-center/create-and-activate-aws-account

Introduction to Operating System
What is an Operating System ?
Its a software that makes all the other programs work and 
helps them share the computer resources.

Main Jobs of OS
1. Process Management
   The OS decides which program runs when and for how long
   
2. Memory Management
   The OS keeps track of which part of memory is used by which prorgam
   
3. File System Management
   Organizing and keeping track of files on storage (hard drive, SSD)
   
4. Device Management
   OS communicates with the devices through drivers
   
Simple flow
1. You double-click a program (like chrome)
2. The OS
   Loads Chrome from the disk into memory
   Gives it some CPU time to start running
   Handles any request (like reading files, showing windows)
   
3. You open more apps: OS divides resources among them
4. You shut down: OS saves data, stop programs and safely turns
off the hardware.

Examples of Operating Systems
1. Windows
2. Linux
3. macOS
4. Android
5. iOS

Virtual Machine and Virtualization
Virtualization : technology
Virtual Machines: Output which we get from Virtualization,
                  Guest Machines, Computer within a Computer
What, why and Where, how

What is Virtualization ?
Virtualization is a technology that lets you divide one
physical computer into multiple virtual computers each behaving
like a real, separate machine.

What are Virtual Machines ?
A virtual machine is one of those virtual computer created by
virtualization.
Each VM:
1. Has its own operating system (like windows, Linux)
2. Has virtual hardware (virtual CPU, virtual RAM, disk, network card)
3. Runs independently even though it shares the same real
hardware.

Analogy:
Think of physical computer as a big apartment building
Each apartment is a virtual machine

Why Virtualization ?
Refer the excel sheet.

Why virtual machines ?
1. Better hardware utilization (Effeciency)
2. Cross-Platform Compatability
3. Easier Maintenance and Migration

Disadvantages of Virtual Machines
1. Slower performance
extra overhead dur to additional layer for hypervisor between
the hardware and virtual system.

2. High Resource Usage
Running many VMs on a system can lead system run out of memory
or slow down quickly.

3. Complex setup and Management.

Where Virtualization ?
Where Virtual Machines ?
Use Cases:
1. Corporate IT: Running multiple servers on one machine
2. Personal Computers: Learning and testing other operating systems
3. Embedded Systems: Isolate different software environments
4. Cloud Computing: Rent virtual servers to customers on demand


How Virtualization ?
How Virtual Machines ?
Through hypervisor that divides physical resources into
virtual ones.

Linux Hands-on Exercises
1. Checking your current directory
pwd  #Print the current working directory

2. List files and folders
ls
3. List files and folders with detailed info
ls -l #-l shows details (permissions, owner, size, date)

4. change directory
cd <directory-name> # Moves into the specific folder

Go back one level
cd ..

5. Create a new directory
mkdir <directory-name> #Create a folder/directory with a specific name

6. Create a New Empty file
touch hello.txt #create a blank file with name hello.txt

7. Write text into file
echo "Hello Linux World" > hello.txt

> (writes the text into file and replaces the previous one)

To add (append) text
echo "Appending another line into the file" >> hello.txt

8. Read a file's content
cat <file-name>

9. Find your current user
whoami 

10. Check running processes
ps #show which programs/processes are currently running

11. See system info
uname -a #Displays info about your linux version, kernel and system type

12. Delete a file or folder
#Delete a file
rm <file-name>

#Delete a folder
rm -r <folder-name>

13. Move or rename file
mv <old-file-name> <new-file-name>

#Move a file to another folder
mv <file-name> <folder-name>/
14. Count word, lines and characters
wc <file-name> #to count word, lines, characters

15. Search for a word in a file
grep "Hello" <file-name> #searches for lines that contains Hello

16. search for a word in a file (case-insensitive)
grep -i "word" filename
#-i: makes the search case insensitive

17. Show line numbers while search
grep -in "word" filename

18. Highlight matches
grep --color -in "word" filename




