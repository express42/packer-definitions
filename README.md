# packer-definitions

### How to build:

`packer build ubuntu-16.04-amd64.json`

You can build box for only one provisioner packer

```
packer build -only=virtualbox ubuntu-16.04-amd64.json
packer build -only=parallels ubuntu-16.04-amd64.json
```

### Add box to local vagrant environment

```
vagrant box add --name "express42/win2012r2-chef" ../builds/virtualbox/win2012r2-chef.box
or
vagrant box add --name "express42/ubuntu-16.04" ../builds/virtualbox/express42-ubuntu-16.04_chef-latest.box
```
