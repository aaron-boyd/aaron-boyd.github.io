# Rangemaster

<a href='https://gitlab.com/cyberatuc/range-master'>GitLab</a>

### Description

---

Rangemaster is monolithic cyber range application written in python. It utilizes the SSH protocol to communicate between different servers to deploy and configure virtual machine networks. I lead the development of this application with a small team from Cyber@UC. We plan to deploy it on our lab servers to provide an educational enviornment for students. This will provide students the ability to get hands on experience in cyber operations. Rangemaster will have the capabilities to create entirely simulated  network enviornments which allows students to defend and attack machines in a safe virtualized enviornment. 

### Technologies

---

- QEMU/KVM
- Libvirt
- Python
- SQLAlchemy
- SSH


### Sample Rangemaster Commands

---

1216 x 508
<img src="/images/range_master_demo.png" alt="Rangemaster command examples" width="800" height="600"> 

Rangemaster uses `silos` which act as a storage container for virtual machine images and `servers` to run those images.  

### Deploying machines

---

This video demonstrates taking a machine image `debian10.0_headless` from a silo and deploying it on a server.

<video width='900' height='950' autoplay>
<source src="videos/range_master_demo_deploy.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
