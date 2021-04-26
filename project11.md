# Ansible Client as a Jump Server (Bastion Host)  
* Install and configure Ansible on EC2 Instance  
1. Create a new repository ansible-config-mgt in GitHub account  
![](/image1.png)  
1. Install Ansible (in bastion server)  
\# mkdir ansible  
\# install git to clone created repository  
$ sudo yum install git -y  
$ git clone \<repository address>  
![](/image2.png)  
\# install ansible  
$ sudo yum install ansible -y  
![](/image3.png)  
