# BFsshPrivateKey.sh
 Bash script to bruteforce a username using an SSH private key.
 
 Script bash permettant de bruteforce un nom d'utilisateur en utilisant une clef privée SSH.

## Usage

```
$ chmod 600 id_rsa
$ chmod +x bruteforce-ssh.sh
$ ./bruteforce-ssh.sh
Usage: ./bruteforce-ssh.sh <target_ip> <port> <key_path> <usernames_file>
$ ./bruteforce-ssh.sh 192.168.209.177 22 id_rsa user.txt 
Testing root...
root@192.168.209.177: Permission denied (publickey,password,keyboard-interactive).
Testing admin...
admin@192.168.209.177: Permission denied (publickey,password,keyboard-interactive).
Testing test...
```
