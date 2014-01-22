Erlang
========

This role will install Erlang with [kerl](https://github.com/spawngrid/kerl).

Requirements
------------

This role requires Ansible 1.4 or higher, and platform requirements are listed in the metadata file.

Role Variables
--------------

The variables that can be passed to this role and a brief description about them are as follows:
```yaml
erlang_kerl_url: https://raw.github.com/spawngrid/kerl/master/kerl  # Url of the kerl script
erlang_default_ver: R16B03                                          # Version to install
erlang_install_to: /usr/lib/kerl/installs                           # Install location
```

Dependencies
------------

None

License
-------

BSD

Author Information
------------------

stwind
