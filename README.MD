1. Install VirtualBox
   https://www.virtualbox.org/wiki/Downloads
2. Install Vagrant
   http://www.vagrantup.com/
3. Get PuTTYGen
   http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html
4. Run the following cmd in folder in cmd window to initialize OS(ubuntu)
   vagrant init ubuntu/trusty64
5. Bring up the vagrant by running the following cmd
   vagrant up
6. Run ssh-config to get the Identity File location
   vagrant ssh-config
7. Load the Identity file using PuTTYGen and generate the private key
8. Use the private key in putty(SSH->AUTH) to connect using user vagrant
   