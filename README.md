# FTP-using-python
This is a basic python code for file tranfer between devices.
To make this happen first install pip using `sudo apt install python-pip` .
For server we will use *pyftpdlib* module, so first install it via pip using `pip install pyftpdlib`.
Don't forget to replace username with your's.
Also keep in mind that the port number should be greater than 1024 or it will throw an error "socket.error: [Errno 13] Permission denied" because you can't bind to a port lower than 1024.
For client we are using *ftplib* module from the official python library.
Excecute the server script first then the client script. 


Special Note::The port number and ip should be same as the server's.
