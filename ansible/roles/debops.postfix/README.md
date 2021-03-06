## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) postfix

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-postfix.svg?style=flat)](https://travis-ci.org/debops/ansible-postfix)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--postfix-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-postfix/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.postfix-660198.svg?style=flat)](https://github.com/debops/ansible-postfix)


The `debops.postfix` Ansible role can be used to install and manage
[Postfix](http://www.postfix.org/), a SMTP server. It allows configuration
of Postfix using Ansible inventory variables, and providea a flexible API to
the Postfix configuration for other Ansible roles when it's used as a role
dependency.

### Installation

This role requires at least Ansible `v2.3.0`. To install it, run:

```Shell
ansible-galaxy install debops.postfix
```

### Documentation

More information about `debops.postfix` can be found in the
[official debops.postfix documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-postfix/docs/).


### Role dependencies

- `debops.secret`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
