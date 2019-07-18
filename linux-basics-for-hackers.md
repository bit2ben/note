### Topics
* Networking
* BASH Scripting
* Security
### Introduction
* How to be a aspiring hacker?
* Some basic linux skills are a prerequisite to becoming professional hacker.
* Why hackers use linux?(Most hacking tools are written for linux and the future belongs to linux.)
* kali linux runs on VM.How to do it?
### The basic
* Fundamental skills,terms and concepts.
* Basic commands in linux : 
  * *pwd cd ls*
  * *locate whereis find which*
  * *mkdir mv rm rmdir*
  * *whoami  man  ps cat* 
### Text manipulation
* viewing files
  * *cat*
  * *head* :Just to view the beginning of a small file.
  * *tail* :It's used to view the last lines of a file.
  * *nl* :To display a file with numbers.
  * *more*
  * *less* :You can not only scroll through a file ,but you can also filter it for terms.
* Filtering,finding and replacing text
  * *grep* :filtering
  * *sed* :finding and replacing
### Analyzing networks
* CLI *ifcnfig* and *iwconfig
* Being able to change your IP address and other network infomation is a useful skill.
   Done with the *ifconfig* command.
  * Changing your IP address.
  * Changing your network mask and broadcast address
  * Spoofing your MAC address.
* DHCP(dynamic host configuration protocol) server
  * To connect to the internew from a LAN,you must have a DHCP-assigned IP.
  * Done with the *dhclient* command.
* DNS(domain name system)
  * Manipulating the DNS with *dig*.
  * Changing your DNS server
  * A important file /etc/hosts.
### Configuring software
* Using apt to handle software
  * apt-get install packname
  * apt-get remove packname or apt-get purge packname.
  * apt-get update or apt-get upgrade.
* sources.list file
* Installing software with git(very important)
  * git clone website
  * Following the readme file to make program.
### Permissions
* Checking permissions:ls -l
* Changing permissions:chmod
  * changing permissions with decimal notation
  * changing permissions with decimal UGO(user,group and others)
* Umask
   In Debian systems,the umask is preconfigured to 0022
   * To change the umask value for a user,edit the file /home/username/.profile
* Privilege escalation
  * How to?
### Process management
* Viewing processes
  *  ps top
* Killing processes
  * kill
* Running processes in the background
* Moving a process to the foregroud
* How to schedule processes to run at a particular time of day?
  * at command
### Managing user environment variables
* there are two types of variables:shell and environment.
* *env* command
* *set* command
  * viewing all environment variables.
  * Sometimes ,you won't want your system to save any past command.make HISTSIZE=0.
* PATH variable
 *adding to the PATH variable:PATH=$PATH:/pathname.Do not type the command line like this:PATH=/pathname.
 

 
