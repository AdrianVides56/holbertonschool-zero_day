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
     ![first](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/9/07ab45cca73c3d47172fd5dab216fd24c445abd7.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210202%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210202T134540Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=be159b0883cad9cc4572dbb9216ef8397c4ce8d31d06a3d67e77e235d17d88f1)
- Create your first virtual machine:
    - ```vagrant init ubuntu/trusty64```
    ![secod](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/9/360129725d2153f59987581a8d28ad3cf48478e3.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210202%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210202T134540Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=735135b14541f5d5606b994bca53daf0d8e21078732576e63dd2bfe1d0088117)
    - ```vagrant plugin install vagrant-vbguest```
    - 
__At this point the installation is complete, then every time you want to acces your VM just follow the next steps:__

- ```vagrant up```
    ![third](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/9/d30afba034f625105ed4a805ac7fcede0640f2d2.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210202%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210202T134540Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=1732fadec9e98b6ef398aada34bd2f96c253fa5aaa377ebec552145bcfe49a86)
- ```vagrant ssh```
    ![fourth](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/9/c96cb3618227068018a94152385f9d36f1a9a06c.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210202%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210202T134540Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=03efe0518f1423914ad0bb9f3b7a280a95c1a6eb5aa1416951400682091ff0ca) 
---
