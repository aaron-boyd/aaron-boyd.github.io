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
```
