# SAMBA
Docker SAMBA image to share a directory between different systems.

# USAGE 
docker run --name SAMBA -v /home/SAMBA-HOST:/SAMBA -p 139:139 -p 445:445 -id javi98/samba

# USER AND PASSWORD
USER: USUARIO 

PASSWORD: 12345678

# Problem i do not have permission to create files
chmod 777 /home/SAMBA-HOST
