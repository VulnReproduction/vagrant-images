Packer CentOS
=============

[Packer](http://packer.io) configuration to generate Debian VirtualBox image/Vagrant boxes.

* CentOS 6.10 (Minimal) 64-bit

## Usage

```
packer build centos-6.10-x86_64.json
```

Use the box (generated in `build` subdirectory) with [Vagrant](http://vagrantup.com) and [VirtualBox](http://virtualbox.org).

## References

[1] <https://gitlab.com/ariya/packer-vagrant-linux>
