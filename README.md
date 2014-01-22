Erlang
========

This role will install Erlang with [kerl](https://github.com/spawngrid/kerl).

Requirements
------------

This role requires Ansible 1.4 or higher, and platform requirements are listed in the metadata file.

Role Variables
--------------

The variables that can be passed to this role and a brief description about them are as follows:

* `erlang_kerl_url`: url of the kerl script
* `erlang_default_ver`: Erlang version to install [default: `R16B03`]
* `erlang_install_to`: location to install [default: `/usr/lib/kerl/installs`]
* `erlang_kerl_download_dir`: folder for otp source [default: `/tmp/kerl/archives`]
* `erlang_kerl_build_dir`: folder for otp builds [default: `/tmp/kerl/builds`]

Dependencies
------------

None

License
-------

BSD

Author Information
------------------

stwind
