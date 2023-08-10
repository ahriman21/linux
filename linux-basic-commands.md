# system information
### to see hardware info:
> lshw

### to see connected usb devices :
> lsusb

### to see memory info :
> cat /proc/meminfo

### to see cput info :
> lscpu
> cat /proc/cpuingo

### to see disk info:
> lsblk

# linux package manager:
### how to install, remove and update apps and packages in debian distros :
> apt install [app name]  
> apt remove [app name]  
> apt upgrade [app name]

### to remove unused libraries in debian distros:
> apt autoremove

### to reconfig or config a package or app:
> dpkg-reconfigure [app name]


# environment variables :  

### to see environment variables :
> env

### to see system path:  
> echo $PATH

### add to system path:
> PATH=$PATH:/your deisred path

# terminal manual :  
### how to search in terminal commands:  
> apropos [command you wanna search for]


# file and directories
### how to search in a directory :  
> find [path] -name "[name of the file you are loogin for]"  

### search a file that starts with letter i :
> find [path] -name "i*"

# processes :
### how to see processes with details:
> ps -aux  

### how to find a specific process:
> ps -aux | grep [process or program name]

### how to kill a process:
> kill [process id]

### to see processes that are having most resources:
> top  

# vi text editor
### to open vi editor 
> vi filename  

### to go on edit mode 
> i  

### to go on command mode
> esc  


### to save file
> press esc  
> :w  

### to quit
> press esc  
> :q  


### to quit without saving
> press esc  
> :q!  

### to delete a character in command mode  
> press esc  
> x  

### to copy a line in command mode
> press esc
> yy

### to paste 
> press esc  
> p

* note : notice the columns before some commands



# user manager:
### create user:  
> sudo useradd bob

### delete user:
> sudo userdel bob   

### change password:
> sudo passwd bob  
