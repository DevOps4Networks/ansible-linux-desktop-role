Ansible Linux Desktop Role
==========================

[![Build Status](https://travis-ci.org/smola/ansible-java-role.svg?branch=master)](https://travis-ci.org/smola/ansible-java-role)

Manages installation of a Linux desktop of choice on RedHat and Debian distributions. 
All packages are installed using the package manager.

Requirements
------------

None.

Role Variables
--------------

The main variable is the name of the desktop to be installed. The supported
desktops are listed below:

# Debian / Ubuntu

Valid desktops for Debian and Ubuntu are:

...

# Fedora/RedHat

Valid desktops for Fedora and RedHat are:

...

# Others

Got this role working with a different distro? Please, [report it on GitHub](https://github.com/DevOps4Networks/ansible-linux-desktop-role/issues).

Dependencies
------------

None.

Example Playbook
-------------------------
...
License
-------

Copyright (c) Nathan Sowatskey <nathan@nathan.to>

ansible-linux-desktop-role is released under the terms of the MIT License.


Acknowledgements
----------------

Thanks to [Santiago M. Mola](https://github.com/smola) from whom I have borrowed 
some ideas from his [ansible-java-role](https://github.com/smola/ansible-java-role) 
and also idea from 
[Testing Ansible Roles with Travis CI on GitHub](https://servercheck.in/blog/testing-ansible-roles-travis-ci-github).
