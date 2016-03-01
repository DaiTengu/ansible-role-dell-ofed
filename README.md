Ansible Role - dell-ofed
========================

This playbook installs [Mellanox Linux Driver for Dell's Mellanox ConnectX3 adapters](http://www.dell.com/support/home/us/en/19/Drivers/DriversDetails?driverId=FJF94).

Platforms
---------

CentOS 6.7 is the only platform that is supported and tested so far.

Role Variables
--------------

- Check out [defaults/main.yml](defaults/main.yml)

Dependencies
------------

None.

Installation
------------

Regular installation:

```
ansible-galaxy install RDI2.dell-ofed
```

Installation to a specific directory(e.g. roles/):

```
ansible-galaxy install -p roles/ RDI2.dell-ofed
```

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: RDI2.dell-ofed }

License
-------

MIT License.

Author Information
------------------

- Koji Tanaka, RDI2
