Instructions for setting up Vagrant/Ansible on a new machine

Install  Virtual Box
   go to https://www.virtualbox.org/wiki/Linux_Downloads
   Click on the appropriate version to install
   Select open with package manager

Get the OS for Virtual Box
   vagrant box add precise32 http://files.vagrantup.com/precise32.box
   vagrant box add centos-6.4-32 http://developer.nrel.gov/downloads/vagrant-boxes/CentOS-6.4-i386-v20130427.box
    
Install AnsibleDirections from http://docs.ansible.com/intro_installation.html#latest-releases-via-apt-ubuntu
   sudo apt-get install software-properties-common
   sudo apt-add-repository ppa:ansible/ansiblesudo 
   apt-get updatesudo 
   apt-get install ansible

Vagrant repo setup
   git submodule init
   git submodule update
