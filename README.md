Xen
===

Simple role to install and configure xen

Requirements
------------

No requirements

Role Variables
--------------

By default the role didn't install xen nor configure

```
xen__install: False
xen__configure: False
xen__use_libvirt_network: False
```

Dependencies
------------

None

Example Playbooks
-----------------

Play with:

```
- hosts: all
  name: Setup hypervisor
  roles:
    - role: xen
```

License
-------

GPLv3

Author Information
------------------

François TOURDE

