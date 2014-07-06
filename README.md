spree-ansible-vagrant
=====================

Get started quickly with Spree Commerce on a Vagrant box provisioned with Ansible

## Run on vagrant: 

    git checkout git@github.com:toast38coza/spree-ansible-vagrant.git
    vagrant up

## Run on Ubuntu server:

    mv hosts.example hosts
    
_add relevant IPs/hostnames to your hosts file. Then run:

    ansible-playbook spree -i hosts -u <remote user>
