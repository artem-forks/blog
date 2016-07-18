---
layout: post
title: "Ansible mysql-hardening role released"
date: 2016-07-17 18:00:00
image:
      url: /assets/article_images/2015-06-23-ansible-os/17905776305_0172f47d95_k.jpg
video: false
comments: true
theme_color: 302F2D

author: 'Sebastian Gumprich'
author_image: "/assets/images/basti.png"
author_link: "https://www.zufallsheld.de"
---

Even though the Github repository already got 17 stars at the time of writing, we never officially released the [ansible-mysql-hardening](https://github.com/dev-sec/ansible-mysql-hardening) role.
Today we change that and release [1.0.0](https://github.com/dev-sec/ansible-mysql-hardening/releases/tag/1.0.0)!

The mysql-hardening role joins the other two already existing Ansible roles, [ssh-hardening](https://github.com/dev-sec/ansible-ssh-hardening) and [os-hardening](https://github.com/dev-sec/ansible-os-hardening).

This role hardens a MySQL server according to best practices and implements the same guidelines as our successful [Chef](https://github.com/dev-sec/chef-mysql-hardening) and [Puppet](https://github.com/dev-sec/puppet-mysql-hardening) implementations.

The main work was done by [Anton Lugovoi](https://github.com/fitz123) and [Sebastian Gumprich](https://www.zufallsheld.de) who implemented the following changes:

- Local testing [\#17](https://github.com/dev-sec/ansible-mysql-hardening/pull/17)
- fix rhel daemon [\#16](https://github.com/dev-sec/ansible-mysql-hardening/pull/16)
- alt version initial commit [\#15](https://github.com/dev-sec/ansible-mysql-hardening/pull/15)
- add test support for ansible 2.0 and 1.9 [\#13](https://github.com/dev-sec/ansible-mysql-hardening/pull/13)
- update platforms in meta-file [\#10](https://github.com/dev-sec/ansible-mysql-hardening/pull/10)
- Simplify local testing with custom role [\#9](https://github.com/dev-sec/ansible-mysql-hardening/pull/9)
- New role layout [\#8](https://github.com/dev-sec/ansible-mysql-hardening/pull/8)
- fix mysql restart not happening because of missing os specific variable [\#5](https://github.com/dev-sec/ansible-mysql-hardening/pull/5)
- Separate system-vars from editable vars. [\#2](https://github.com/dev-sec/ansible-mysql-hardening/pull/2)
- Add documentation for testing, change value in vars [\#1](https://github.com/dev-sec/ansible-mysql-hardening/pull/1)


We're supporting this role on Debian- and Enterprise Linux-based operating systems, but we'll also try our best in helping you run the role on other systems! Just open up an issue or pull request or join our [Gitter Chatroom](https://gitter.im/dev-sec/general) to chat directly with us!


You can find the role on [Github](https://github.com/dev-sec/ansible-mysql-hardening/) and on [Ansible Galaxy](https://galaxy.ansible.com/dev-sec/mysql-hardening/).


Be sure to follow us on [Twitter](https://twitter.com/hardening_io) for the latest updates.
