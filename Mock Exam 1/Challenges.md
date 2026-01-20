# Challenge 1
```bash
An cli tool called awscli has been installed using pip3, and its out of date on remote servers. Ensure that it is updated to the latest version.

Write a playbook to update aws cli to the latest version.

Goal:
Explore Ansible pip module to solve this task!
```
# Challenge 2
```bash
A new developer called "John Doe" is recently hired in your team. He needs to get inside all the remote servers via ssh as root user.

Write a playbook to give ssh access on all the remote servers by pushing his public key located at: /home/petko/playbooks/john_doe.pub on all of the servers.

Goal:
Explore Ansible authorized_key module to solve this task!
```
# Challenge 3
```bash
Write a playbook /home/petko/playbooks/configure_webserver.yml which installs nginx web server and serves a html file: "index.html" from directory "/usr/share/nginx/html" on remote servers.

You are provided with /home/petko/playbooks/index.html that you should copy to remote web servers. Ensure that nginx is serving the file, that you copied.

Goal:
Explore Ansible package, copy and service modules
```
# Challenge 4
```bash
Write a playbook to copy the secret file located at /home/petko/playbooks/secret_file.txt to all remote hosts at location: /root/.secret_file.txt
The secret file is encrypted, please use the vault password from the script /home/thor/playbooks/get_vault_pass.txt

Goal:
Explore Ansible copy again, but this time use password located in the get_vault_pass.txt
Consider using " --vault-password-file get_vault_pass.txt" command line option
```

