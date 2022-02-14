# ansible_bootstrap_centos7

# Based on this aritcle:
https://opensource.com/article/18/3/manage-workstation-ansible


# Install Ansible pre-bootstrapping
sudo yum -y update
sudo yum -y install epel-release ansible git

# Run playbook
ansible-pull -U https://github.com/markvtt/ansible_bootstrap_centos7.git
