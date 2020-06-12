Dev Setup
=========

This repo contains scripts and the like to set up and work with a VPC-based development environment.

Usage
-----

Add `dev-box` to `~/.ssh.config` like so, pointing to the private key you set up to connect to the machine.

```
Host dev-box
Hostname 1.2.3.4
IdentityFile ~/.ssh/id_rsa
```

* `bin/setup-initial`: Run once on a freshly booted box to create my user account and prevent root access to the machine.
