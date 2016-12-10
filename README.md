Memcached
=========

This role will install memcached.

Example Playbook
----------------

    - name: Installed memcached
      hosts: all
      become: true
      become_method: sudo
      roles:
        - mosufy.memcached

License
-------

This codebase is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)

Author Information
------------------

For any issues with installation or getting this to work, send an email to: [mosufy@gmail.com](mailto:mosufy@gmail.com)
