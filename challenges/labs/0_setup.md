### Challenge Setup
```
* cloud provider:AWS
* IP address and NDS name:
   Public :
   IP:172.31.11.190 DNS ec2-54-214-223-37.us-west-2.compute.amazonaws.com
   IP:172.31.3.144 DNS ec2-54-190-17-67.us-west-2.compute.amazonaws.com 
   IP:172.31.9.182 DNS ec2-54-202-60-31.us-west-2.compute.amazonaws.com
   IP:172.31.8.38 DNS ec2-54-202-71-49.us-west-2.compute.amazonaws.com
   IP:172.31.1.173 DNS ec2-54-245-62-190.us-west-2.compute.amazonaws.com

* Linux release 
   /* cat /proc/version  */
  Linux version 2.6.32-431.el6.x86_64 (mockbuild@c6b8.bsys.dev.centos.org) (gcc version 4.4.7 20120313 (Red Hat 4.4.7-4) (GCC) ) #1 SMP Fri Nov 22 03:15:09 UTC 2013

 
 * system capacity for my fist node
   /* df -h*/
  $df -h
    Filesystem      Size  Used Avail Use% Mounted on
     /dev/xvde        30G  654M   28G   3% /
     tmpfs           7.4G     0  7.4G   0% /dev/shm

                                                   
  * yum repolist
    [root@ip-172-31-11-190 ~]# yum repolist enabled
    Loaded plugins: fastestmirror, presto
    base                                                                                                                                                                    | 3.7 kB     00:00     
    base/primary_db                                                                                                                                                         | 4.7 MB     00:00     
    extras                                                                                                                                                                  | 3.4 kB     00:00     
    extras/primary_db                                                                                                                                                       |  29 kB     00:00     
    updates                                                                                                                                                                 | 3.4 kB     00:00     
    updates/primary_db                                                                                                                                                      | 2.5 MB     00:22     
    repo id                                                                                repo name                                                                                         status
    base                                                                                   CentOS-6 - Base                                                                                   6,706
    extras                                                                                 CentOS-6 - Extras                                                                                    45
    updates                                                                                CentOS-6 - Updates                                                                                  447
    repolist: 7,198

```

