# smi2021 dkms

smi2021 [kernel source](https://github.com/Manouchehri/smi2021) I used

### Download

```bash
$ cd /usr/src
$ git clone git@github.com:vkulpa/smi2021-dkms.git smi2021-0.1
```

### Dependencies

See original repositories for dependecies

### Add to kernel & Install
```bash
$ dkms add -m smi2021/0.1
$ dkms install -m smi2021/0.1
```
