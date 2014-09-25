packer-definitions
==================

How to build:

`packer build ubuntu-14.04-amd64.json`

You can build box for only one provisioner packer

```
build -only=virtualbox ubuntu-14.04-amd64.json
build -only=parallels ubuntu-14.04-amd64.json
```
