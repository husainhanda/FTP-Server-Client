# FTP-Server-Client
We created FTP server and client on C language. Our server supports multiple client and can be connected to them simultaneously. Our client can perform many tasks on server using different commands like STOR, PWD and STOR which can be used to perform different task like uploading downloading files, getting current directories and much more. We implemented 20 such commands to perform different tasks.

List Of Commands:
1.User: for login takes argument user<argument> try user husain 
2.Pass: for authentication takes argument pass<argument> try pass tejbir
3:CDUP  to change the server directory to the parent directory
4.REIN:to reset the connection between client and server
5.QUIT: it will quit the server connection
6.PORT:it will open FIFO to transfer file in a specific port between client and the server needs argument try unix
7.RETR: to send the retrieve files to client use PORT command before using this command needs argument filename
8.APPE:append the data in the store file
9.REST:request file
10.RNFR:used to rename the selected file taken from client 
11.RNTO:rename to which name we have to give to the file
12.ABOR: to abort all the commands
13.DELE: to delete the file 
14:RMD used to remove the directory 
15.MKD :to make new directory
16.PWD :current working directory 
17.LIST:list all the contents of the directory 
18.STAT: to give the pid's of all the current working processes 
19.NOOP: sends an ok reply.
20.STOR :accept the data to store the data as a file in server site use PORT command before using this command Needs argument file name"
