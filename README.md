# Task: Linux Fundamentals Project with Vagrant
## Objective
You are to set up a GitHub repository and complete a set of Linux system administration tasks using Vagrant on your local machine. You'll document your work with screenshots and descriptions in a README.md file.
##  1. Set Up a Vagrant Server
### Screenshot 1: Show the Vagrant initialization and login process
![alt text](screenshot1.png)
Add a short description under the screenshot explaining what you're doing.
> This screenshot shows the Vagrant initialization process (vagrant init), the VM startup with vagrant up, and successfully SSH-ing into the Ubuntu virtual machine using vagrant ssh. It confirms the VM is running and ready for Linux administration tasks.
## 2. Explore the Linux File System
### Screenshot 2: Show the created folder structure
![alt text](Screenshot2.png)
Describe the structure you created
> I created a custom folder that will contain some of the script for automation and other stuff for DevOps. 
## 3. Manage File Permissions and Ownership
### Screenshot 3: Create files and use chmod and chown to change its permissions and ownership.
![alt text](Screenshot3.png)
> Briefly explain the meaning of the permission and ownership values.
#### Permission in linux is the consent to use a file or folder. thy're 3 set of people that can be granted permission or permission can be removed from they're.
 User: the person who created or owns the file. U </h4>
<h4> Group: A set of users who might also have access. G </h4>
 <h4> Others: Other set of people that might be interested in using the file. O </h4>
 read -r
 write -w
 execute -x
 -rwxrwxrwx or drwxrwxrwx
where the - represent that it's a file and 