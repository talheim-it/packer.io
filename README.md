# packer.io
Repository to build images for virtualbox with packer.io

## Tested
 - CentOS7
 - CentOS8
 - Fedora32
 - Ubuntu1804
 - Ubuntu2004

## Vars
```
"hostname": "ubuntu",
"domain": "local",
"ssh_user": "vagrant",
"ssh_pass": "vagrant",
"iso_url": "http://cdimage.ubuntu.com/ubuntu/releases/18.04/release/ubuntu-18.04.5-server-amd64.iso",
"iso_target_path": "/home/titrumbold/Data/Development/images/ubuntu-18.04.5-server-amd64.iso",
"iso_checksum": "8c5fc24894394035402f66f3824beb7234b757dd2b5531379cb310cedfdf0996",
"export_path": "/home/titrumbold/Data/Development/images/final/Ubuntu1804.box"
"iso": "/home/rumbold/Development/images/source/rhel-8.1-x86_64-dvd.iso" <= Only needed for Redhat when local
```

## @ToDo Ansible-Playbook
```
```

