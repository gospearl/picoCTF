#NICE NETCAT

![img1](images/FullDes.png)

#Walkthrough:
Use the command: nc mercury.picoctf.net 43239 to interact 
with the shell. This will give you more info about the output

Save the output to a file

![img2](images/netcat2.png)

On examining the output, you can see that it is in ascii. 
Convert to characters using this command

awk '{printf "%c", $1}' file.txt

![img3](images/netcat3.png)

FLAG: picoCTF{g00d_k1tty!_n1c3_k1tty!_7c0821f5} 
