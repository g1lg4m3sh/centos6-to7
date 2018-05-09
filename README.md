# How we upgraded our BackBox CentOS 6 to CentOS 7

One of the challenges every organization faces is the the lack of capability to do an in place upgrade of CentOS 6.x to CentOS 7. At the moment, the only official method of upgrading major versions of CentOS is to wipe and reinstall everything. Having said that, there were always processes you could follow with varying levels of success (based on straying from the official repositories and how customized your setup and package list was). We have run through this process now with a 99% success rate, on our systems, with over a hundred successful upgrades, so let’s break everything down.