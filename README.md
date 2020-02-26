linux\_power\_saving
====================

Installs TLP if the target host has a battery. Installs powertop if the machine has a battery *and* an Intel CPU

Example Playbook
----------------

There is no configuration required you can just enable this role and
it will appropriately skip all work if the machine doesn't need power
saving features.

    - hosts: laptops
      roles:
         - chasinglogic.linux_power_saving

License
-------

BSD
