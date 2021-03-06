## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) mailman

[![Travis CI](http://img.shields.io/travis/debops/ansible-mailman.svg?style=flat)](http://travis-ci.org/debops/ansible-mailman) [![test-suite](http://img.shields.io/badge/test--suite-ansible--mailman-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-mailman/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.mailman-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/1574)

The `debops.mailman` Ansible role can be used to create and manage mailing
lists using [GNU Mailman](http://list.org/) package.

By default the role provides configuration for `debops.postfix` role to
configure the SMTP server integration, as well as `debops.nginx` role to
configure access to the web control panel.

### Installation

This role requires at least Ansible `v2.0.0`. To install it, run:

    ansible-galaxy install debops.mailman

### Documentation

More information about `debops.mailman` can be found in the
[official debops.mailman documentation](http://docs.debops.org/en/latest/ansible/roles/ansible-mailman/docs/).


### Role dependencies

- `debops.secret`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`mailman` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
