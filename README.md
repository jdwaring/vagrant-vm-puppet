Basic Vagrant VM Apache2 webserver project with pupper config
=======================

##Introduction
This is a very basic Vagrant Box set-up that will enable you host your very own
Apache2 webserver on a Virtual Machine. Once up and running you should be able 
to access the contents of the htmldocs forlder from any web browser using the
following link. http://localhost:1234

You can make changes to the contents of this folder(htmldocs) and instantly see 
them in your browser.

Please note this is a very basic apache2 set up and is only intended for developers
to get a basic understanding of Vagrant and puppet configuration.

If you find this interesting please visit the Vagrant web site and find out how 
you can build your own VM box.


##Installation
Download and install the software listed below:

###Requirements:
1. Vagrant 1.5.x  - https://www.vagrantup.com/downloads.html
2. VirtualBox 4.3.x - https://www.virtualbox.org/wiki/Downloads
3. Git 1.9.x - http://git-scm.com/downloads

##Installing software:
1. $ git clone https://github.com/jdwaring/vagrant-vm-puppet.git
2. $ cd vagrant-vm-puppet
3. $ vagrant up
4. $ vagrant ssh (optional - only if you need to access the web server).

