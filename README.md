p3r7.dec-vt
=========

Integrates a VTxxx into your life.

Automates the setup described by [Drew Devault's blog post "Integrating a VT220 into my life"](https://drewdevault.com/2016/03/22/Integrating-a-VT220-into-my-life.html).

Requirements
------------

Having a hardware terminal plugged into your computer.

This role should only be played against a Linux server with SystemD.

Also, don't hesitate to take a look at [meta/main.yml](meta/main.yml).


Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)


Dependencies
------------

None, but just in case look at [meta/main.yml](meta/main.yml).


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: p3r7.dec-vt, dec_vt_term: vt220, dec_vt_login_as_user: me }

License
-------

MIT

Author Information
------------------

Project page: [p3r7/ansible-dec-vt](https://github.com/p3r7/ansible-dec-vt)
Author's blog: [eigenbahn.com](https://www.eigenbahn.com/)
