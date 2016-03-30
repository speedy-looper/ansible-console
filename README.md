Role Name
=========

Console arsenal

Requirements
------------

user - for user specific config
git - for user specific config

Role Variables
--------------

N/A

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: localhost
      roles:
         - { role: speedy-looper.ansible-console }

Post-tweaks
-----

### Make taskwarrior work

    # ~/.taskrc
    taskd.credentials=[update here]

    > intheam setup
    > task sync

License
-------

MIT

Author Information
------------------

Speed-of-light
