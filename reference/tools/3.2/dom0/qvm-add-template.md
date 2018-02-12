---
layout: doc
title: qvm-add-template
permalink: /doc/tools/3.2/dom0/qvm-add-template/
redirect_from:
- /doc/dom0-tools/qvm-add-template/
- /en/doc/dom0-tools/qvm-add-template/
- /doc/Dom0Tools/QvmAddTemplate/
- /wiki/Dom0Tools/QvmAddTemplate/
---

```
================
qvm-add-template
================

NAME
====
qvm-add-template - adds an already installed template to the Qubes DB

SYNOPSIS
========
| qvm-add-template [options] <vm-template-name>

OPTIONS
=======
-h, --help
    Show this help message and exit
-p DIR_PATH, --path=DIR_PATH
    Specify path to the template directory
-c CONF_FILE, --conf=CONF_FILE
    Specify the Xen VM .conf file to use(relative to the template dir path)
--rpm
    Template files have been installed by RPM

AUTHORS
=======
| Joanna Rutkowska <joanna at invisiblethingslab dot com>
| Rafal Wojtczuk <rafal at invisiblethingslab dot com>
| Marek Marczykowski <marmarek at invisiblethingslab dot com>
```