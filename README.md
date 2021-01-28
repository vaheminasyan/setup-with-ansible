# setup-with-ansible
Ansible workbooks to fasten your setups.

### Usage
`ansible-workbook -i hosts prometheusTSDB.yml`  
This assumes that you have an ansible inventory file called 'hosts' in the working directory and want to install "prometheus" in the hosts marked in it.  

### Prerequisites  
* Ansible installed and configured - Refer to [official documentation](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) on how to install Ansible for your OS.  
  * Repository includes a general configuration, so it can be run by only entering IP addresses for remote hosts.
* SSH connection to remote hosts (where the roles should be installed)

###List of available Roles  
Each role may have its own readme with additional detailed info.  
* [Prometheus](https://github.com/vaheminasyan/setup-with-ansible/tree/main/roles/prometheusTSDB)


