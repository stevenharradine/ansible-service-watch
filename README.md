# ansible-service-watch

[![Licence](https://img.shields.io/badge/Licence-ISC-blue.svg)](https://opensource.org/licenses/ISC)
[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg)](#)

Tunables
--------
* `servicewatch_user` (string) - The user that should own the cloned repo
* `servicewatch_install_directory` (string) - The directory that we should be cloned too
* `servicewatch_install_name` (string) - The folder name of the checked out repo
* `servicewatch_path` (string) - The concatenation of `servicewatch_install_directory` and `servicewatch_install_name`

Example Playbook
----------------
    - hosts: servers
      roles:
         - role: telusdigital.service-watch

Contributors
------------
* Steven Harradine
