Challenge: SSH Connection  
Platform: pwn.college  

Goal:  
Learn how to connect to a remote machine using SSH and understand key-based authentication.

What I did:  
- Generated an SSH key pair using ssh-keygen  
- Obtained public and private keys  
- Linked the public key to my pwn.college account  
- Connected to the remote dojo instance using SSH  
- Accessed the remote environment successfully  

Command used:  
ssh-keygen -f key -N ''  
ssh -i key hacker@dojo.pwn.college  

What I learned:  
- How SSH works for remote access  
- Difference between public key and private key  
- How key-based authentication is used instead of passwords  
- How to connect to remote systems securely