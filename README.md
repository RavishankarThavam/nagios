This will install below applications
   - Nagios Core-4.3.1
   - pnp4nagios-0.6.25
   
########## Prerequisites #######
Ansible
########## Instructions ########
Download the files into /tmp directory of Ansible server
Edit the hosts file with the Server IP in which nagios to be installed
Install the nagios with the below command
ansible-playbook nagios.yml
