## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) x2go_server

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops-contrib/ansible-x2go_server.svg?style=flat)](https://travis-ci.org/debops-contrib/ansible-x2go_server)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--x2go__server-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-x2go_server/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops--contrib.x2go_server-660198.svg?style=flat)](https://galaxy.ansible.com/debops-contrib/x2go_server)


The `debops-contrib.x2go_server` role allows you to setup and mange
[X2Go][] on the server-side.
X2Go enables you to access a graphical desktop of a computer over a low
bandwidth (or high bandwidth) connection.

[X2Go]: http://wiki.x2go.org/

### Installation

This role requires at least Ansible `v2.1.3`. To install it, run:

```Shell
ansible-galaxy install debops-contrib.x2go_server
```

### Documentation

Until the documentation is available in a rendered version you can refer to the
reST documentation source files in the
[/docs](https://github.com/debops-contrib/ansible-x2go_server/tree/master/docs) directory.
Refer to the [debops/docs#111 issue](https://github.com/debops/docs/issues/111) for details.



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- [Robin Schneider](http://ypid.de/) (maintainer) | [e-mail](mailto:ypid@riseup.net) | [Twitter](https://twitter.com/ypid) | [GitHub](https://github.com/ypid)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps Contrib](https://github.com/debops-contrib/debops-contrib). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
<!-- Ansigenome sources: https://github.com/ypid/ypid-ansible-common/tree/master/template_READMEs/debops-contrib -->
