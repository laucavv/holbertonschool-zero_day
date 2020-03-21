![readme2](https://user-images.githubusercontent.com/60374349/77229662-224fb100-6b5d-11ea-89ff-188607b48859.png)
## What is a virtual machine?
In computing, a virtual machine (**VM**) is an emulation of a computer system. Virtual machines are based on computer architectures and provide functionality of a physical computer. Their implementations may involve specialized hardware, software, or a combination.
### The tools ⚙
at Holberton we will work with **VirtualBox** and **Vagrant** for our projects

**VirtualBox** is a Virtual Machine provider. The virtual machines themselves will be spawned using VirtualBox. VirtualBox is free and lightweight, which make it a perfect choice for us. [virtualbox](https://www.virtualbox.org/)

**Vagrant** is a tool that sits on top of a VM provider. Again, we chose to use VirtualBox as a provider, but other providers exist out there and Vagrant offers the possibilty to use dfferent providers  Just like VirtualBox, we choose to use Vagrant because it is free, reliable and well maintained. Keep in mind that the purpose here is to use Virtual environments, and both VirtualBox and Vagrant are just means to achieve this purpose.[vagrant](https://www.vagrantup.com/downloads.html)

VirtualBox and Vagrant together allow you to manage and ship isolated development environments. Those isolated environments in the context of Holberton (and in the future, in the context of a company) allow you to match the environment we use to automatically check your work.
Although both VirtualBox and Vagrant are widely used in the industry, it doesn’t mean it is the only means to achieve virtualization, and other tools exist with their pros and cons.
