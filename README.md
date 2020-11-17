<div align="center">
    <img src="https://imagineer.in/assets/img/posts/packer-ubuntu.png" alt="logo" width="350px" style="margin-top: 1em">
    <h1>Packer for Ubuntu server</h1>
    <h4>Packer config to build VMware virtual machines (VMX) and VirtualBox machines (OVF - TODO) from Ubuntu 20.04 server ISO file as a source.</h4>
</div><br>

## Ubuntu 20.04 Server (VMWare)

Run packer build:

```bash
$ packer build -on-error=ask -force ubuntu-20.04-live-server-packer.json
```


## Ubuntu 20.04 Legacy Server (VMWare)

Run packer build:
```bash
$ packer build -on-error=ask -force ubuntu-20.04-legacy-server-packer.json
```
<br>

For more info: [imagineer.in/blog/packer-build-for-ubuntu-20-04](https://imagineer.in/blog/packer-build-for-ubuntu-20-04/)



TODO:

## Ubuntu 20.04 Server (VirtualBox)

Run packer build:

```bash
$ packer build -on-error=ask -force <TODO>
```

## Ubuntu 20.04 Legacy Server (VirtualBox)


```bash
$ packer build -on-error=ask -force <TODO>
```
