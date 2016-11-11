# Start Here #

This is a **Puppet Enterprise** and **Git** training tutorial.
We will also use **Vagrant** and/or **Docker** to provision our training environment.

### Training Overview ###

What will we do in this training tutorial?

* Deploy your own training environment using either Docker or Vagrant + VirtualBox
* Install Puppet Enterprise (Monolithic Install), GitLab, and one additional training VM/Container
* Learn the basics of Puppet Enterprise (Config, CLI, Environments, Code, etc.)
* Learn how to use Hiera for...
    - Node classification
    - Auto-lookup of class parameters
    - Hierarchical data lookup
* Learn how to install and Setup GitLab, and how to use it to host your Puppet code
* Learn how to setup R10K to automate code deployment
* Learn basic Puppet Coding, Git usage, and Vagrant & Docker usage

### How to use this repo? ###

* Download and install the Git client on your workstation

     - Link:  https://git-scm.com/downloads

* Clone this repo

```
     git clone https://github.com/bentlema/puppet-training
```

* Change directory to...

```
     cd puppet-training
```

* Begin following the Labs (links below)

### Navigating This Tutorial ###

This entire tutorial is of course a Git repository!  All of the tutorial
files are written in [Markdown](https://en.wikipedia.org/wiki/Markdown).
Make sure you're comfortable navigating this code repo before you start.
At any time, if you wish to return to this main README.md file, you can
click the bentlema/[puppet-training](https://github.com/bentlema/puppet-training#start-here) link at the top of the page.

### Minimum System Requirements ##

* You will need the ability to install software on your workstation (Admin / Super-User privileges).  We will use the following software:
    - Git
    - VirtualBox
    - Vagrant or Docker

* The software we will use is available for Windows, Linux, and Mac OS X, so you should be able to use any platform.

* Disk space:
    - 2GB of free disk space to acomodate software and VM/Container images

* Memory:
    - minimum 8GB of RAM if using Docker Containers
    - minimum 12GB of RAM if using VirtualBox VMs

* Note: You will use either Vagrant to spin up VM's or Docker to spin up Containers
    - We will not use both (at the same time), so choose one or the other
    - Although Vagrant is capable of spinning up Docker containers, we will
      not use this capability

### Labs ###

There are enough differences between using Docker and Vagrant+VirtualBox,
I've split this tutorial into two distinct tracks.  I will cover all of the
same core materials, but will use different examples in each track, so it
may be worth it to go through both tracks if you have the time and energy.


#### Track: Vagrant + VirtualBox ####

 * **Lab 01** - [Vagrant to deploy 3 training VMs](/tutorial/vbox/01-Provision-Training-VMs.md#lab-1)
 * **Lab 02** - [Prepare to Install Puppet Enterprise on VMs](/tutorial/vbox/02-Prep-to-Install-Puppet-Master.md#lab-2)
 * **Lab 03** - [Install Puppet Master](/tutorial/vbox/03-Install-Puppet-Master.md)
 * **Lab 04** - [Install Puppet Agent](/tutorial/vbox/04-Install-Puppet-Agent.md)
 * **Lab 05** - [Get familiar with puppet config files, and puppet code, and CLI](/tutorial/vbox/05-Puppet-Config-and-Code.md)
 * **Lab 06** - [Practice doing some puppet code, and puppet runs](/tutorial/vbox/06-Puppet-Code-Practice.md)
 * **Lab 07** - [Configure Hiera](/tutorial/vbox/07-Config-Hiera.md)
 * **Lab 08** - [More about Environments](/tutorial/vbox/08-Environments.md)
 * **Lab 09** - [Install GitLab on the gitlab VM](/tutorial/vbox/09-Install-GitLab.md)
 * **Lab 10** - [Move Puppet Code under Git Control](/tutorial/vbox/10-Move-Puppet-Code-to-GitLab.md)
 * **Lab 11** - [Modules, Roles & Profiles, and the environment.conf](/tutorial/vbox/11-Roles-and-Profiles.md)
 * **Lab 12** - [Git Basics](/tutorial/vbox/12-Git-Basics.md)
 * **Lab 13** - [Git Workflow](/tutorial/vbox/13-Git-Workflow.md)
 * **Lab 14** - [Practice doing some puppet code, and puppet runs](/tutorial/vbox/14-practice.md)

#### Track: Docker Containers ####

 * **Lab 01** - [Docker to deploy 3 training Containers](/tutorial/docker/01-Provision-Training-Containers.md#lab-1)
 * **Lab 02** - [Prepare to Install Puppet Enterprise on Containers](/tutorial/docker/02-Prep-to-Install-Puppet-Master.md#lab-2)
 * **Lab 03** - [Install Puppet Master](/tutorial/docker/03-Install-Puppet-Master.md)
 * **Lab 04** - [Install Puppet Agent](/tutorial/docker/04-Install-Puppet-Agent.md)
 * **Lab 05** - [Get familiar with puppet config files, and puppet code, and CLI](/tutorial/docker/05-Puppet-Config-and-Code.md)
 * **Lab 06** - [Practice doing some puppet code, and puppet runs](/tutorial/docker/06-Puppet-Code-Practice.md)
 * **Lab 07** - [Configure Hiera](/tutorial/docker/07-Config-Hiera.md)
 * **Lab 08** - [More about Environments](/tutorial/docker/08-Environments.md)
 * **Lab 09** - [Install GitLab on the gitlab VM](/tutorial/docker/09-Install-GitLab.md)
 * **Lab 10** - [Move Puppet Code under Git Control](/tutorial/docker/10-Move-Puppet-Code-to-GitLab.md)
 * **Lab 11** - [Modules, Roles & Profiles, and the environment.conf](/tutorial/docker/11-Roles-and-Profiles.md)
 * **Lab 12** - [Git Basics](/tutorial/docker/12-Git-Basics.md)
 * **Lab 13** - [Git Workflow](/tutorial/docker/13-Git-Workflow.md)
 * **Lab 14** - [Practice doing some puppet code, and puppet runs](/tutorial/docker/14-practice.md)

### Some Further Reading ###

 * **Lots of Links** - [Further Reading](/tutorial/YY-Further-Reading.md)

---

Copyright © 2016 by Mark Bentley
