![Ansible Lint](https://github.com/johanneskastl/ansible-role-set_ntp_servers_for_chrony/workflows/Ansible%20Lint/badge.svg)

set_ntp_servers_for_chrony
=========

Set ntp servers for chrony.

Requirements
------------

Chrony needs to be installed.

Role Variables
--------------

- `chronyd_service`: The name of the chronyd service, by default 'chronyd'.
- `list_of_ntp_servers`: A list of ntp servers, default is to use the ones from the Friedrich-Alexander-University Erlangen-Nuremberg (FAU)

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: 'johanneskastl.set_ntp_servers_for_chrony'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via git@johannes-kastl.de.
