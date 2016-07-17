---
layout: post
title: "Ansible os-hardening role released"
date:   2015-07-13 18:00:00
image:
      url: /assets/article_images/2015-06-23-ansible-os/17905776305_0172f47d95_k.jpg
video: false
comments: true
theme_color: 302F2D

author: 'Sebastian Gumprich'
author_image: "/assets/images/basti.png"
author_link: "https://www.zufallsheld.de"
---

After two months of development the [Hardening Framework](http://dev-sec.io/) team is glad to announce that we created our second Ansible role: [ansible-os-hardening](https://github.com/dev-sec/ansible-os-hardening/). This role hardens a Linux operating system according to best practices and implements the same guidelines as our successful [Chef](https://github.com/dev-sec/chef-os-hardening) and [Puppet](https://github.com/dev-sec/puppet-os-hardening) implementations.

In these two months [Sebastian Gumprich](https://www.zufallsheld.de) implemented with the help of [Christoph Hartmann](https://github.com/chris-rock) and [Dominik Richter](https://github.com/arlimus) the following changes:

 * Implement os-hardening to meet our [tests](https://github.com/dev-sec/tests-os-hardening)
 * Enable GPG-checking on all yum-repository files [#5](https://github.com/dev-sec/ansible-os-hardening/pull/5)
 * Disable system accounts [#6](https://github.com/dev-sec/ansible-os-hardening/issues/6)
 * Module-loading configuration [#22](https://github.com/dev-sec/ansible-os-hardening/pull/22)
 * Travis support [#17](https://github.com/dev-sec/ansible-os-hardening/pull/17)
 
As always, this role supports Debian- and Enterprise Linux-based operating systems.

You can find the role on [Github](https://github.com/dev-sec/ansible-os-hardening/) and on [Ansible Galaxy](https://galaxy.ansible.com/list#/roles/4248).

Found a problem? Want to help? Open up a issue or pull request or join our [Gitter Chatroom](https://gitter.im/dev-sec/general) to chat directly with us!

Next on? MySQL hardening! Be sure to follow us on [Twitter](https://twitter.com/hardening_io) for the latest updates.
