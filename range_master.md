# Rangemaster Description

<a href='https://gitlab.com/cyberatuc/range-master'>GitLab</a>

Rangemaster is monolithic cyber range application written in python. It utilizes the SSH protocol to communicate between different servers to deploy and configure virtual machine networks. I lead the development of this application with a small development team from Cyber@UC and plan to deploy it on our labs servers to provide an educational enviornment for students to get hands on experience in cyber operations. Rangemaster will have the capabilities to create entire simulate real world network enviornments. This will allow students to defend and attack machines in a safe virtualized enviornment. 
 
 ### Sample Rangemaster Commands
 ---
 
![Rangemaster commands](/images/range_master_demo.png "Rangemaster commands")
 
 Rangemaster uses `silos` which act as a storage container for virtual machine images and `servers` to run those images.  
 
 ### Deploying machines
 ---
 
 This video demonstrates taking a machine image `debian10.0_headless` from a silo and deploying it on a server.
 
 <video width='1032' height='980' autoplay>
   <source src="videos/range_master_demo_deploy.mp4" type="video/mp4">
   Your browser does not support the video tag.
 </video>

### Technologies
- QEMU/KVM
- Libvirt
- Python
- SQLAlchemy
- SSH
