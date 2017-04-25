packer-definitions
==================

How to build:

`packer build ubuntu-14.04-amd64.json`

You can build box for only one provisioner packer

```
build -only=virtualbox ubuntu-14.04-amd64.json
build -only=parallels ubuntu-14.04-amd64.json
```

Add box to local vagrant environment

```
vagrant box add --name "express42/win2012r2-chef" builds/virtualbox/win2012r2-chef.box
```
