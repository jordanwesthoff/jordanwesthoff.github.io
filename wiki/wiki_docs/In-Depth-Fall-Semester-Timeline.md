This page outlines the projected timetable to be followed for this project through the end of the Fall Semester, by week. This schedule will be less rigid than the Spring Semester calendar since a good deal of research and implementation and testing have yet to be completed, but significant progress is required and expected as well.

------------------------------------

### Week 4
- ~~Prepare updated presentation material~~ 
- ~~Do an initial benchmark of the system and each node.~~

### Week 5
- ~~Memory Testing Week (Can project be run from RAM or SHM Swap)~~
- ~~Disk Testing Week (Will drives explode if project is run from local drive storage)~~
- ~~Turn information gathered into a good infographic~~
![Initial Single vs Multi-Core Benchmarks](http://logcat.student.rit.edu/Public%20Share/image%20(3).png)
![Initial Image Processing Multi-Core Tests (PNG)](http://logcat.student.rit.edu/Public%20Share/image%20(1).png)
- ~~Build a repository of all packages needed for SLURM and other important packages~~

### Week 6
- ~~Initialize resource managers and task schedulers~~
 - ~~Slurm~~
 - ~~Maui + Torque~~
 - ~~GEARS, OpenPBS, ROCKS, etc~~
- ~~Initialize Fortress and benchmark it (HP GL3 series)~~
- ~~Disk test Prowler (FreeBSD / FreeNAS)~~
- ~~Work on SLURM repository~~

### Week 7 
- ~~Benchmark the system as a whole~~
- ~~Start learning C++ as well as research compiling and running C++ code~~

### Week 8
- ~~Time to begin the paper~~
 - ~~Cover design~~
 - ~~Architecture~~
 - ~~Available benchmark data~~

### Week 9
- Working on paper [abstract, preamble, introduction and hardware]
- compiling dc.RAW and open.CV for C++
- [cimg](http://cimg.sourceforge.net/)

### Week 10
- ~~Convert head node [intruder] from i686 to x86_64~~
- ~~Converting to Phoronix Test Suite [PTS]~~
- ~~Tinkering with Phoromatic server setup and web 'dashboard' setup~~

### Week 11
- More C++
- dpx -> Tiff operations with dc.RAW
- ~~Full Pool Stats Update~~
![Full Pool Stats](http://logcat.student.rit.edu/Public%20Share/servers.png)

### Week 12
- ~~Five new intruder nodes acquired~~
 - ~~Registered and on the network after much stress (thanks RIT RESNET)~~
 - ~~Cent Initialized, Updated, Provisioned and Benchmarked~~
- Phoromatic server running and setup
- Image processing setup and custom dc.RAW testmarking built
- ~~Must convert Crawler to x86_64 arch for better RAM and CPU utilization.~~
- ~~32-bit and 64-bit performance comparisons~~
![Full Pool Stats - MCluster Included](http://logcat.student.rit.edu/Public%20Share/FullCluster.png)
![32vs64 [Headnode, Compute, Commodity]](http://logcat.student.rit.edu/Public%20Share/32bit64bit.png)
![MicroCluster Comparison](http://logcat.student.rit.edu/Public%20Share/MicroCluster.png)

### Week 13
![Ansible Square Logo](https://raw.githubusercontent.com/jordanwesthoff/jordanwesthoff.github.io/master/images/ansible.png)
- Implementation and Testing of Ansible SSH provisioning 
- Ansible testing and playbook demo'ing
- Kickstart and Ansible playbooks developed and spread across all cluster machines. 

### Week 14
![Zabbix Logo](https://raw.githubusercontent.com/jordanwesthoff/jordanwesthoff.github.io/master/images/zabbix.png)
- Implementation of monitoring and testing software to look over the entire cluster. Phoronix, Ganglia and Zabbix were tested. Ganglia and Phoronix were removed and determined to be deprecated - Zabbix wins. 
- Write zabbix install, maintain and update scripts for shell execution and Ansible playbook provisioning
- Configure Zabbix and all required templates
- Asset management
- Benchmarking to ensure data fetch accuracy

### Week 15
- More C++
- Convert Shell scripts and messy init scripts to Ansible YAML

### Week 16
- Power management
- Lots of Ansible scripting
- Improved Zabbix monitoring
  - Generated custom screens and graphs for full cluster
  - Found the Zabbkit iOS app, yay for mobile monitoring

### Week 17
- Finals week
- Didn't do any cluster work
- Cried
- Mostly kidding.