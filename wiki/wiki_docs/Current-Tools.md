There are a wide variety of tools currently being implemented with the system. Open source tools are all preferred over proprietary tools.


### CentOS 6.5/6.6

CentOS (Community ENTerprise Operating System) is preferred as an enterprise edition of the linux operating system. Current build versions are i686 or x86_64 versions running either 6.5 or 6.6.
This is the platform everything is constructed on. Initial install must include the install of openssh-server and 


### Ansible

Ansible is a SSH driven provisioning system. Ansible operates and syncs all nodes for scalable provisioning. Runs from a centralized head node and contacts all nodes with Ansible installed on them as long as they are defined in the Ansible hosts file (on the head node).


### Zabbix

Zabbix is an open source monitoring tool that allows a centralized head node to monitor and track the performance of any given amount of nodes as long as the nodes are running the 'zabbix-agent' software. 


### Git and GitHub

Git is used to sync code between all of the nodes from a centralized database repository. This allows code to be edited on one node and then committed and synced to all others, if appropriate. 


### Munge

Munge is an open source, AES style encryption tool that manages all of the cross node authentication for the SLURM resource manager and cluster manager. 


### SLURM

Resource and cluster manager to oversee the execution of programs on the cluster. Using RIT's customized version of Slurm.


### Stress

Open source CPU, Memory, I/O and Desk Speed stress tester. Useful to see how the cluster handles massive jobs.

