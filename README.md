# Hyper V Manager  Virtualization Setup for Active Directory Lab

This screenshot shows the initial configuration stage of my Active Directory home lab using Hyper-V Manager on Windows. At this step, I am preparing the virtualized environment where my Domain Controller and additional Windows Server/Client machines will run. The Hyper-V console displays the host system (TCCHAM) with no virtual machines created yet.
![image alt](https://github.com/tavoych/Project/blob/2f1a5212ee753ae75d4b7760ca94a93abb105793/Hyper-V%20Manager.png)

The screenshot displays the New Virtual Machine Wizard within Hyper-V Manager, where I began provisioning a virtual machine that will host the Active Directory Domain Services (AD DS) role. This step initializes the VM creation process prior to installing Windows Server and configuring the domain environment
![image alt](https://github.com/tavoych/Project/blob/32a0d7d5c6d0ac5deb6e38fcfac6dd323408a7ea/Before%20You%20Begin.png)
Here, I assigned a name to the virtual machine (Windows Server)  This step is part of preparing the virtual environment to install Windows Server
![image alt](https://github.com/tavoych/Project/blob/02160089e1996b1f743c43ed95c1b8086fca1472/Windows%20Server.png)
In this step, I configured the virtual machine generation while creating my Windows Server VM in Hyper-V. I selected Generation 2 to enable modern virtualization features such as UEFI-based boot and improved security. This selection is required for newer 64-bit operating systems, including Windows Server editions used for Active Directory Domain Service
![image alt](https://github.com/tavoych/Project/blob/2a7b98b8d57174ee00ab1d37e26e82a1bb9fa476/Selecting%20the%20Virtual%20Machine%20Generation.png)
In this step, I configured the startup memory for the virtual machine in Hyper-V. I allocated 4096 MB (4 GB) of RAM and enabled Dynamic Memory, allowing Hyper-V to automatically adjust memory usage based on the VM’s needs. This ensures efficient resource management and stable performance
![image alt](https://github.com/tavoych/Project/blob/a66108e3f6a662cd8cd049ba50270aa4f21f40e1/Assigning%20Memory.png)
In this step, I configured the virtual machine’s network adapter to connect to my pre-created Virtual Switch Network. This allows the VM to communicate with other machines in the lab environment
![image alt]()


