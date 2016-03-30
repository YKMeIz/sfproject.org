![SFProject-logo](https://raw.githubusercontent.com/SwordFishProject/sfproject.org/master/misc/image/SFProject-logo.jpg)<br>
**Here is my unofficial, non-profit, RPMs repository for RedHat related GNU/Linux Distros:**
**e.g. RHEL, CentOS, Scientific Linux, etc.**

SFProject is the abbreviation of **S**word**F**ish **P**roject. "Swordfish" name comes from the fastest fish. It was chosen to reflect the repository would contain rebuild packages and some extra latest packages in order to improve RedHat related GNU/Linux Distros performance and add new features. The goal of this repository is to provide more up to date version of packages and some extra packages which cannot be found in official repositories. (*Unfortunity, most of packages are still under rebuilding. The repository currently only provides some* **latest** *packages such as* **docker**, **git**, **gcc**, **glibc**, *etc.*)

Sometimes, I might push over bleeding edge packages, and every package in this repository might not be tested fully. Therefore, use them **at your OWN RISK**!

This repository is dependent on EPEL. If you find you're missing a dependency, make sure you have the EPEL repository [active in your package manager](https://fedoraproject.org/wiki/EPEL).
If you meet any problem or would like some specific packages included into the repository, feel free to send me email: *neil@gyz.io*

Currently, this repository only support packages for EL7 with x86_64(AMD64).

Installation: copy and paste thie command below to install repository config file.

`yum -y install epel-release && yum install http://sfproject.org/download/el7/SFProject-release-0.2-1.el7.sfp.noarch.rpm`

You can browse packages at [here](http://sfproject.org/download).

Here is the GPG key: http://sfproject.org/download/el7/RPM-GPG-KEY-el7-SFProject

If you meet installation issue, check this known issues and solutions. It may help. 
