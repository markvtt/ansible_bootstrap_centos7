# ansible_bootstrap_centos7

# Based on this aritcle:
https://opensource.com/article/18/3/manage-workstation-ansible


# Before bootstrapping
sudo yum -y update
sudo yum -y install epel-release ansible git


ansible-pull -U https://github.com/markvtt/ansible_bootstrap_centos7.git
