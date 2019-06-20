Example multi-os role
=====================

Demonstrate a way to switch the role defaults based on Operating System,
allowing the end user of the role to override the values in `host_vars` or
`group_vars`

Requirements
------------

None.

Role Variables
--------------

`multi_var` is a variable that has a different default based on which OS is in use.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
      - multi-os-role

License
-------

Apache-2.0 or MIT or BSD-3-Clause

Author Information
------------------

[James Cassell](https://github.com/jamescassell)
