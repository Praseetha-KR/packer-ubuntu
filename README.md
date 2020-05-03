# Packer for Ubuntu server

Packer config to build VMware virtual machines (VMX) from Ubuntu 20.04 server ISO file as a source.


## Ubuntu 20.04 Server

Run packer build:

```bash
$ packer build -on-error=ask -force ubuntu-20.04-live-server-packer.json
```


## Ubuntu 20.04 Legacy Server

Run packer build:
```bash
$ packer build -on-error=ask -force ubuntu-20.04-legacy-server-packer.json
```
