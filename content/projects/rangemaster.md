## $ ./rangemaster.py
#### July 2019 - Present

Rangemaster is monolithic cyber range application written in python. It utilizes the SSH protocol to communicate between different servers to deploy and configure virtual machine networks. Aaron works in a small development team with other members of Cyber@UC. They plan to deploy Rangemaster on their lab servers to provide an educational enviornment for students. This will provide the ability to get hands on experience in cyber operations. Rangemaster will have the capabilities to create entirely simulated  network enviornments that allows students to defend and attack machines in a safe virtualized enviornment. Through the development of this tool Aaron has learned how to implement large scale command line driven python programs and manage a virtualization stack over SSH.

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

Rangemaster uses `silos` which act as a storage container for virtual machine images and `servers` to run those images.  

### Deploying machines

---

This video demonstrates taking a machine image `debian10.0_headless` from a silo and deploying it on a server.

<video autoplay loop>
  <source src="/content/videos/range_master_demo_deploy.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
