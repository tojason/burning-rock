---
layout: single
title: Fix Federa Mate on Virtual Box auto resize problem
---

Try the follow code, see if that works for you.

First step takes little longer, it is a huge update. Beware of your battery if you using laptop.

```bash
1- sudo dnf update

2- reboot

3- sudo dnf install gcc kernel-devel-$(uname -r)

4- Insert Guest Additions CD and Run the installer

5- reboot
```

Virtualbox version: *5.0.32 r112930*

Federa Mate version: *Fedora-MATE_Compiz-Live-x86_64-25-1.3*

[Reference][credit]

[credit]: https://ask.fedoraproject.org/en/question/77949/virtualbox-screen-resolution-problem-with-fedora-23/

[jekyll-docs]: http://jekyllrb.com/docs/home