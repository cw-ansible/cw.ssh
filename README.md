<!--

---
lang: american
---
-->

[![Build Status](https://travis-ci.org/cw-ansible/cw.ssh.svg?branch=master)](https://travis-ci.org/cw-ansible/cw.ssh)
[![Tweet this](http://img.shields.io/badge/Tweet-it00aced.svg)](https://twitter.com/intent/tweet?tw_p=tweetbutton&via=renard_0&url=https%3A%2F%2Fgithub.com%2Fcw-ansible%2Fcw.ssh&text=Install%20and%20secure%20%23OpenSSH%20with%20%23ansible.)
[![Follow me on twitter](http://img.shields.io/badge/Twitter-Follow-00aced.svg)](https://twitter.com/intent/follow?region=follow_link&screen_name=renard_0&tw_p=followbutton)


# OpenSSH

Install and secure [OpenSSH](http://www.openssh.com/).

## Usage

Include the `cw.ssh` module to your playbook.

## Description

This roles installs the `openssh-server` package. It also disable `root`
login and slow down bad login response (if system is using *PAM*).

## Configuration

None for the moment.

## Copyright

Author: Sébastien Gross `<seb•ɑƬ•chezwam•ɖɵʈ•org>` [@renard_0](https://twitter.com/renard_0)

License: WTFPL, grab your copy here: http://www.wtfpl.net
