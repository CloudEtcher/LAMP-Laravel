###  Vagrantfile Configuration to install two Ubuntu-based servers named “Master” and “Slave” using Vagrant. <br>
![Vagrantfile Configuration](image.png)

### Bringing up Master and Slave servers <br>
![vagrant up](image-1.png)

### Master and Slave machines running on Oracle VM <br>
![Master and Slave running](image-2.png)

### SSH into Master and Slave servers <br>
![shh into both Master and Slave servers](image-5.png)

### Create a bash script to automate the deployment of a LAMP (Linux, Apache, MySQL, PHP) stack. <br>
##### touch deploy_lamp.sh 
##### nano deploy_lamp.sh 
##### chmod u+x deploy_lamp.sh
##### ./deploy_lamp.sh

### IP addresses of both Servers <br>
![IP addresses](image-7.png)

### Laravel on Master Server  <br>
![Laravel on Master Server](image-6.png)

### Slave IP address before running Ansible playbook<br>
![Apache Default Page](image-8.png)

### Ansible playbook to deploy Lamp and Laravel on Slave Server<br>
![Ansible Configuration](image-9.png)

### 'Verify that the PHP application is accessible through the VM’s IP address (take screenshot of this as evidence)' <br>
![Verified](image-10.png)

### 'Create a cron job to check the server’s uptime every 12 am' <br>
![Cron Job](image-11.png)
![Cron Job/](image-12.png)