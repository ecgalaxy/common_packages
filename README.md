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

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

ECGALAXY team.
