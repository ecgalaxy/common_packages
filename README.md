ECGALAXY common_packages role
=============================

Common packages to be installed on most platforms.

Requirements
------------

None.

Role Variables
--------------

- `installed_packages`: the list of packages to install.

Dependencies
------------

- optional: ecgalaxy.bootstrap

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.bootstrap
        - ecgalaxy.common_packages

One-liner
---------

    bash <(curl -s https://code.europa.eu/-/snippets/1/raw/main/ansible-role.sh) ecgalaxy.common_packages

See [ansible-role](https://code.europa.eu/-/snippets/1) for instructions.

Please verify the script integrity first.

Upgrading & Uninstalling
------------------------

This Ansible role uses the distribution's package manager to install packages.

In order to upgrade or uninstall a package, please refer to your distribution's package manager documentation.

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

ECGALAXY team.
