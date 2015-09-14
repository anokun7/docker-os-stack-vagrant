# Open Source Docker Stack

To quickly install a complete (but opinionated) docker (open source only) stack

Vagrant files to automate the setup of docker engine.

**Instructions to use this vagrant setup**

1. Install Oracle VirtualBox
2. Install Vagrant
3. In a terminal run: 
  ```
  git clone git@github.com:anokun7/docker-os-stack-vagrant.git ~/docker-os-stack-vagrant
  cd ~/docker-os-stack-vagrant
  vagrant up   
  vagrant status
  ```
  This should show 3 vm's created and running.
  ```
  Current machine states:
  
  ubuntu-4                  running (virtualbox)
  ubuntu-5                  running (virtualbox)
  ubuntu-6                  running (virtualbox)
  
  This environment represents multiple VMs. The VMs are all listed
  above with their current state. For more information about a specific
  ```
  Now you can ssh into any of them using `vagrant ssh /-4/` or `vagrant ssh /-6/`

  Pre-configured IP addresses issued to the boxes as per below:
  ```
  ubuntu-4                  10.0.0.4
  ubuntu-5                  10.0.0.5
  ubuntu-6                  10.0.0.6
  ```
