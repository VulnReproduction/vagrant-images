Packer Debian
=============

[Packer](http://packer.io) configuration to generate Debian VirtualBox image/Vagrant boxes.

* Debian Wheezy
* Debian Jessie
* Debian Stretch

## Usage

To generate a VirtualBox image, edit debian-<version> (replace <version> by the desired version of Debian like stretch) file and adapt the variables fields:

```
    "variables": {
        "debian_version": "9.0.0",
    },

```
Once done, create your box file:
```
packer build debian-<version>
```
So for example:
```
packer build debian-stretch
```

## References

[1] https://github.com/deimosfr/packer-debian
