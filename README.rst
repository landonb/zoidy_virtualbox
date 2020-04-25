################
zoidy_virtualbox
################

An Ansible role to install VirtualBox, and to sign the drivers to appease Secure Boot.

- DEPRECATED: VirtualBox 6.0 and later are published to an apt repository. Use that instead!

  https://github.com/landonb/zoidy_home-fries/blob/master/tasks/app-virtualbox.yml

Example Playbook
================

It's simple to run the role from a playbook::

  - hosts: laptops
    roles:
       - role: zoidy_virtualbox

License
=======

`GPLv3 <LICENSE>`__

