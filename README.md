![](https://raw.githubusercontent.com/SwordFishProject/sfproject.org/master/misc/image/SFProject-logo.jpg)

####Here is my unofficial, RPMs repository for RedHat related GNU/Linux Distros:
*e.g. RHEL, CentOS, Scientific Linux, etc.*

SFProject is the abbreviation of **S**word**F**ish **P**roject. "Swordfish" name comes from the fastest fish. It was chosen to reflect the repository would contain some extra bleeding edge packages for RedHat related GNU/Linux Distros.These packages are also updated rapidly. The current goal of this repository is to provide more up to date version of packages and some extra packages which cannot be found in official repositories. (such as *docker, git, vlc, texlive, kodi, midori, cuda, claws-mail, httpd, nginx, cairo-dock, thunderbird, spotify, gimp, inkscape, chromium,* etc.)

Sometimes, I might push over bleeding edge packages, and every package in this repository might not be tested fully. Therefore, use them at your own risk! Anyway, you will be fine if you use this repository for desktop system purpose. If you unhappy with some packages in this repository, simply downgrade them and set them to be excluded during updating. This repository is dependent on EPEL. If you find you're missing a dependency, make sure you have the EPEL repository active in your package manager. If you meet any problem or would like some specific packages included into the repository, feel free to send me email: *neil@gyz.io*

Currently, this repository only support packages for EL7 with x86_64(AMD64).

<br>
######Installation: 
- copy and paste thie command below to install repository config file:
  `yum -y install epel-release && yum install http://sfproject.org/download/el7/SFProject-release-current.el7.sfp.noarch.rpm`

<br>
######Browse RPM binary packages:
You can browse packages at [here](http://sfproject.org/download). It contains both rpm binary packages and source rpm packages.

<br>
######Browse sources of packages:
The sources of rpm packages are available in Github now. They are put as spec format instead of the source rpm package. [Click here](https://github.com/SwordFishProject/SFProject) to browse spec file repository.

If you prefer to browse source rpm packages, click this [link](http://sfproject.org/download/el7/update/source/SRPMS/).

<br>
######GPG key:
Here is the GPG key: [Click Me](https://raw.githubusercontent.com/SwordFishProject/sfproject.org/master/RPM-GPG-KEY-el7-SFProject)
