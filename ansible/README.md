## Ansible Steps 

Step 0 : Launch a server manually and install apache webserver



https://github.com/ravsau/ansible-practice


- Launch Ansible master and  Ansible Slave using Amazon EC2
  - Port 22 Open ( Ansible uses port 22)
  - Port 80 Open ( For downloading packages using HTTP) 
- Install Ansible on the Master
- Configure the Ansible Master
  - add ansible user
  - Add sudo password ssh access
  - add inventory file 
  - disable ssh key check
  - install sshpass 
  
  
- Configure the Ansible Slave 
 -  Add ansible user
  - Add sudo passwordless access 
  
- Use ad hoc commands to ping and install apache webserver
- Use ad hoc command to uninstall apache webserver
  
- Use Ansible Playbook to install softwares

