# 0x00. Vagrant
---
### Description
This project was created with learning purposes at holberton school. Is about vagrant and virtaul machines.
The OS I am simulating is Ubuntu 14.04 (trusty64)
#### Virtual machine:
In computing, a virtual machine (VM) is the virtualization/emulation of a computer system. Virtual machines are based on computer architectures and provide functionality of a physical computer. Their implementations may involve specialized hardware, software, or a combination.

#### Virtual Box:
Is a Virtual Machine provider. The virtual machines themselves will be spawned using VirtualBox. VirtualBox is free and lightweight.

#### vagrant:
Is a tool that sits on top of a VM provider.
---
### How to intall vagrant:
##### Windows:
- Download VirtualBox from this [link]
- Install VirtualBox
- Download Vagrant from this [link.]
- Install Vagrant
- Open the command prompt__(win + r < cmd)
- Add the Ubuntu 14.04 (Trusty) image to your box list:
    - ```vagrant box add ubuntu/trusty64```
- Create your first virtual machine:
    - ```vagrant init ubuntu/trusty64```
    - ```vagrant plugin install vagrant-vbguest```


__At this point the installation is complete, then every time you want to acces your VM just follow the next steps:__

- ```vagrant up```
- ```vagrant ssh```
---
## Author
[Adrian Vides] | [Twitter] | [GitHub]


[link]: <https://www.virtualbox.org/wiki/Downloads>
[link.]: <https://www.vagrantup.com/downloads>
[GitHub]: <https://github.com/AdrianVides56>
[Twitter]: <https://twitter.com/termi56661>
[Adrian Vides]: <https://www.linkedin.com/in/adrian-felipe-vides-jimenez-a201401b7> 
