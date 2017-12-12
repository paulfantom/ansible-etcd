<a href="https://coreos.com/etcd/">
    <img src="https://seeklogo.com/images/E/etcd-logo-DC3A108AAF-seeklogo.com.png" alt="etcd logo" title="etcd" align="right" height="60" />
</a>

Ansible Role: etcd
==================

[![Build Status](https://travis-ci.org/paulfantom/ansible-etcd.svg?branch=master)](https://travis-ci.org/paulfantom/ansible-etcd) [![License: MIT](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT) [![Ansible Role](http://img.shields.io/badge/ansible%20role-paulfantom.etcd-blue.svg)](https://galaxy.ansible.com/paulfantom/etcd/) [![GitHub tag](https://img.shields.io/github/tag/paulfantom/ansible-etcd.svg)](https://github.com/paulfantom/ansible-etcd/tags)

Role installs etcd - distributed, reliable key-value store

Examples
--------

Use it in a playbook as follows:
```yaml
- hosts: all
  become: true
  roles:
    - paulfantom.etcd
```

Have a look at the [defaults/main.yml](defaults/main.yml) for role variables
that can be overridden.
