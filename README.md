# CS615HW6
# 15:07
This program is a shell code. It can be used to duplicate a given EC2 instance. 
Commentary:
1.When we writen first version and run it. The system display "command not found".
modify PATH files. Add "export PATH=~/bin:"$PATH""

2.When we want to connect to the instance. Do not know which userName is work.
UserName default is 'root'. Then get the return infomation when connect to the instance. Than get the right userName value.

3.Do not know how to transfer files. 
Use scp transferring files between a local host and a remote host

