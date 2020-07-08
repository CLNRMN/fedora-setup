 # Fedora Setup
 
 ## Prerequisites
 ### Installed Fedora 32
 Before you start, a fedora 32 with the option "Encrypt my data" should be installed.
 
 ### Installed Ansible
 ```bash
 sudo yum install ansible -y
 ```
 
 ## Setup
 
 ```bash
 ansible-playbook -i inventory setup.yaml -K
 ```
 
 ## Supported Version
 - Fedora 32


