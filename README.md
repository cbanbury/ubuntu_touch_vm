# Intro

A simple Vagrantfile and Ansible playbook to create and setup VM for building ubuntu-touch from source. 
This is much the same as building android. 

# Requirements 

 - [Ansible](http://docs.ansible.com/intro_installation.html) >= 1.7
 - [Vagrant](http://www.vagrantup.com/downloads.html) >= 1.5
 
# What you get
Ubuntu 14.04 X64 VM install with: 

- 1 GB RAM assigned 
- Dependencies for installing ubuntu 
- `phablet-tools`
- Initialised phablet repo (currently 4.4.2)
- `repo sync` into vagrant user home directory

# Vagrant up? 
1. Clone the repo 
2. Make sure you have Vagrant and Ansible installed 
3. From the cloned repo, run `vagrant up`
4. To get onto the box: `vagrant ssh`