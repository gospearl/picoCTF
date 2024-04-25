![img1](images/description.png)

Walkthrough:

Step 1:
Use the command: nc mercury.picoctf.net 43239 to interact 
with the shell. This will give you more info about the output

![img](images/netcat1.png)

Save the output to a file

![img2](images/netcat2.png)

Step 2:
On examining the output, you can see that it is in ascii. 
Convert to characters using this command

awk '{printf "%c", $1}' file.txt

![img3](images/netcat3.png)

FLAG: picoCTF{g00d_k1tty!_n1c3_k1tty!_7c0821f5} 
