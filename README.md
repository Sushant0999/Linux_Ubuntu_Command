# Linux Commands

- ``` uname -a ```
  - to obtain information about the operating system and hardware on which it is running. </br>
- ``` dpkg --print-architecture ```
  - to obtain information about architecture
- ``` cp source target```
  - to copy file from source to target ex - ( cp /home/user.txt /usr/share )
- ```pwd```
  - stands for the present working directory
- Ubuntu :  ```apt list --installed``` Debian : ```dpkg list --installed```
  - used to check for installed packges.
- Debian : ```dpkg --get-selections | grep pkg-name```
  - to search for specific package ex - ( dpkg --get-selections | grep postgres )
- ```apt-get update```
  - use to update packges
- ```apt-get upgrade```
  - use to upgrade packages
- ```sudo lshw -C display```
  - use to get display information
