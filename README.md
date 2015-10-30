## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) cryptsetup

  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.cryptsetup-660198.svg?style=flat)](https://galaxy.ansible.com/detail#/role/4559)

This role allows you to configure a encrypted filesystem on top of any given
block device using [dm-crypt][] and [LUKS][].  A random keyfile generated on the Ansible
controller will be used for the encryption by default.  It is your
responsibility that the keyfile is kept secure for this to make sense.  For
example by storing the keyfile on a already encrypted filesystem (both on
the Ansible controller and the remote system).

[LUKS]: https://en.wikipedia.org/wiki/Linux_Unified_Key_Setup
[dm-crypt]: https://en.wikipedia.org/wiki/Dm-crypt

### Features

* Create a random key or use an already existing key.
* Manage `/etc/crypttab` and `/etc/fstab`.
* Create a LUKS header backup and store it on the Ansible controller.

### Note

This role is currently being migrated to the DebOps project.
For the time in between, v0.1.0 of the role is available on Ansible Galaxy as
[`ypid.crypttab`](https://galaxy.ansible.com/detail#/role/4559).

### Installation

This role requires at least Ansible `v1.8.4`. To install it, run:

    ansible-galaxy install debops.cryptsetup

### Documentation

More information about `debops.cryptsetup` can be found in the
[official debops.cryptsetup documentation](http://docs.debops.org/en/latest/ansible/roles/ansible-cryptsetup/docs/).


### Role dependencies

- `debops.secret`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`cryptsetup` role was written by:
- [Robin Schneider](http://ypid.de/) | [e-mail](mailto:ypid@riseup.net) | [Twitter](https://twitter.com/ypid) | [GitHub](https://github.com/ypid)

License: [AGPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
