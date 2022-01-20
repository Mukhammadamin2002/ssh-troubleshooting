## Trouble shooting ssh (Secure Shell)
### There are several steps to check wether ssh configured correctly.
* be sure ssh-server (`sshd_server status: active`) listening client ssh connection
* check wether you have correct key(`private key`) with correct permission (Linux)
* is ssh port defined correctly while connecting to ssh-server (remote server)
*  if you have server `private key` make sure server `public key` is in `authorized_keys` 
* absolute path need to be defined to `private key` by specifying `ssh -i path_to_file user@server_ip -p 22(it depends)` 