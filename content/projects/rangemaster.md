## $ ./rangemaster.py
#### July 2019 - Present

Rangemaster is a monolithic cyber range application written in python. It utilizes the SSH protocol to communicate between different servers to deploy and configure virtual machine networks. Aaron works in a small development team with other members of Cyber@UC. They plan to deploy Rangemaster on their lab servers to provide an educational environment for students. This will provide the ability to get hands-on experience in cyber operations. Rangemaster will have the capability to create entirely simulated network environments that allow students to defend and attack machines in a safe virtualized environment. Through the development of this tool, Aaron has learned how to implement large scale command-line driven python programs and manage a virtualization stack over SSH.

### Technologies

---

- Virtualization
- Libvirt
- Python
- Object Relational Mapping (ORM)
- SSH


### Sample Commands

---

![Rangemaster command examples](/content/images/range_master_demo.png "Rangemaster commande examples")

Rangemaster uses silos which act as a storage container for virtual machine images and servers to run those images. From the output above it can be seen there is one silo and one hypervisor server configured in rangemaster. There is a 'debian10.0_headless' machine on 'silo_1'. Hypervisor 'server_1' also has two networks on it, 'default' and 'aaronnet' 

### Deploying machines

---

This video demonstrates taking a machine image 'debian10.0_headless' from 'silo_1' and deploying it on a 'server_1's' 'default' network. Future plans are to automate this process through Ansible or a web interface.

<video autoplay loop>
  <source src="/content/videos/range_master_demo_deploy.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
