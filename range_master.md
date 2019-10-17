# Rangemaster Description

<a href='https://gitlab.com/cyberatuc/range-master'>GitLab</a>
 
 
 <video width='1032' height='980' autoplay>
   <source src="videos/range_master_demo_deploy.mp4" type="video/mp4">
   Your browser does not support the video tag.
 </video>

```
aaron@r2d2:~/school/range-master$ ./range-master.py silo list    
----------------------------------------------------------------------
| ID | FRIENDLYNAME | URI                                            |
----------------------------------------------------------------------
|  1 | silo_1       | ssh://user@192.168.122.92:22/home/user/vm_silo |
----------------------------------------------------------------------
aaron@r2d2:~/school/range-master$ ./range-master.py server list
-----------------------------------------------------------------------
| ID | FRIENDLYNAME     | URI                                         |
-----------------------------------------------------------------------
|  1 | libvirt_server_1 | ssh://user@192.168.122.129:22/home/user/vms |
-----------------------------------------------------------------------
aaron@r2d2:~/school/range-master$ ./range-master.py silo machines
----------------------------------------------------------------------------
| ID | FRIENDLYNAME        | IMG_TYPE | OS    | USER    | SILO_ID | ARCH   |
----------------------------------------------------------------------------
|  1 | debian10.0_headless | qcow2    | linux | default |       1 | x86_64 |
----------------------------------------------------------------------------
aaron@r2d2:~/school/range-master$ ./range-master.py network list --id 1
-------------------------------------------------------------------------------------------------------------------------------
| ID | FRIENDLYNAME | BRIDGE | IP           | NETMASK       | START        | END            | AUTOSTART | ACTIVE | PERSISTENT |
-------------------------------------------------------------------------------------------------------------------------------
|  0 | default      | virbr0 | 192.168.64.1 | 255.255.255.0 | 192.168.64.2 | 192.168.64.254 | True      | True   | True       |
|  1 | aaronnet     | virbr2 | 10.14.0.1    | 255.255.255.0 | 10.14.0.2    | 10.14.0.254    | True      | True   | True       |
-------------------------------------------------------------------------------------------------------------------------------
```
