Containerization
================

List of open-source containerization (operating-system-level virtualization) technologies.


## AppArmor ##

URL: http://wiki.apparmor.net/index.php/Main_Page
OS: Linux

AppArmor is an application security system that works by defining per-application security policies that define what system resources applications can access in what way.


## Bocker ##




## chroot ##

OS: Linux, BSD
root: yes

chroot is a kernel functionaility that can change the apparent root directory for a process and its children. The environment created by `chroot` is called a "chroot jail".

`chroot`s are a fairly low-level containerization technology, and can be broken out of if not properly set up.


## Contain ##




## Docker ##

UR: https://www.docker.com/
OS: Linux
root: yes

Docker is a 


## Fakechroot ##

OS: Linux
root: no


## Firejail ##

OS: 
root: no
based on: kernel namespaces, seccomp-bpf
focus: user application isolation (i.e. Firefox, BitTorrent clients etc.)


## FreeBSD Jail ##




## LXC ##

OS: Linux
based on: AppArmor, cgroups, chroots, cgroup, kernel namespaces, seccomp policies, SELinux profiles



## LXD (uses LXC) ##

OS: Linux
based on: LXC



## OpenVZ ##

OS: Linux


# Pflask

based on: kernel namespaces



## PRoot ##




## Pseudo ##





## rkt (uses LXC) ##




## sysjail ##




## Vagga ##

