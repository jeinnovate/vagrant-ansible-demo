Vagrant Ansible Demo
=====================

A quick display of using Ansible with a disposable VM via Vagrant.

This should be easy and consistent to replicate on a variety of development environments.

Dependencies
------------

- VirtualBox
- Vagrant
- Ansible

Install using package managers on your respective OS or see dependency sites for details.

Getting the code
----------------

```shell
git clone https://github.com/jeinnovate/
```

Creating
-------

```shell
vagrant up
```
You should now be able to see “It works!” at [http://localhost:8000/](http://localhost:8000/).

Testing Changes
-------

```shell
vagrant provision
```

Destorying
----------

```shell
vagrant destroy
```
