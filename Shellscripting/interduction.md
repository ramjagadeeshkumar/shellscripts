# INTRODUCTION 
---
![preview](./images/shell.png)

## KERNEL
---
* kernel is the hart of linux O/S 
* it manages resources of linux O/S 
  * resources mean facilites available in linux 
  * example : facility to store data, print data on printer, memory and file managment ..etc

---

![preview](./images/S1.png)

## This is shell what does for us 
![preview](./images/S2.png)

![preview](./images/s3.png)

--- 
* its environment provided for user interaction
* shell is a command language interpreter that executes commands read from the standard input device (keyboard)or(from a file)

----

![preview](./images/s5.png)

## Types of shells in Linux
![preview](./images/s4.png)

## Basic commands for shell
---
To find which type of shell on your linux machine 
   * echo $SHELL (Defult shell)
   * echo $0 (current shell)
   * cat /etc/shells (its shows how many shells are installed)
   * chsh (change defult shell(passwd required)) or (usermod -s /bin/bash myuser(admin permission required))
---

## example for shell for mutiple adduser (for loop) 
---
* for i in u1 u2 u3 u4 
* do
* useradd $i

![preview](./images/s6.png)

## To Create script 

* vim script-name.sh or vi script-name.sh
---
![preview](./images/cmd.png)

* :wq! (save & exist)
## file types supported for linux 

![preview](./images/basic-cmd.png)

![preview](./images/s7.png)


## Requried for run shell file
---
* create file : vim shellscript.sh (.sh is identy for checking file we are using)
![preview](./images/s9.png)
#### !/bin/bash  (its helps where to exective script)
* To run shell file  & its fail due if file did not have exectue permission

![preview](./images/s8.png)

![preview](./images/s10.png) 

