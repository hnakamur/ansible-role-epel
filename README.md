epel
====

An ansible role to install the EPEL repository.

Requirements
------------

None.

Role Variables
--------------

- epel_base_url: The base url of the EPEL repository. The default value is http://ftp.iij.ad.jp/pub/linux/fedora/epel

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: hnakamur.epel }

License
-------

MIT

Author Information
------------------

[Hiroaki Nakamura]( http://hnakamur.github.io/ )
