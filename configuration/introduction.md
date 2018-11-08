---
description: Everything you must know to properly configure VerneMQ
---

# Introduction

Every VerneMQ node has to be configured. Depending on the installation method and chosen platform the configuration file `vernemq.conf` resides at different locations. If VerneMQ was installed through a Linux package the default location for the configuration file is `/etc/vernemq/vernemq.conf`.

### File Format

* A single setting is handled on one line.
* Lines are structured `Key = Value`
* Any line starting with \# is a comment, and will be ignored

### Minimal Quickstart configuration

You certainly want to try out VerneMQ right away. For that you need to allow anonymous clients to connect.

* Set `allow_anonymous = on`
* Do not use this setting in production \(or at least _think_ before you do\)

