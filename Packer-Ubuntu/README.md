Packer CentOS
=============

[Packer](http://packer.io) configuration to generate Debian VirtualBox image/Vagrant boxes.

* Ubuntu 12.04.5 LTS (Precise Pangolin) 64-bit

## Usage

```
packer build ubuntu-12.04-amd64.json
```

Use the box (generated in `build` subdirectory) with [Vagrant](http://vagrantup.com) and [VirtualBox](http://virtualbox.org).

## References

[1] <https://gitlab.com/ariya/packer-vagrant-linux>

