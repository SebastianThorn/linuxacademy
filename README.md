# linuxacademy
Ansible-jobb to bootstrap playground servers on LinuxAcademy

sudo dnf install git-core -y
install https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm
pip3 install ansible
/usr/local/bin/ansible-pull -U https://github.com/SebastianThorn/new_fedora_host new_fedora_host.yml


# SUDO
```
dnf install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm
dnf install -y ansible git-core
ansible-pull -U https://github.com/SebastianThorn/linuxacademy new_rhel8.yml
```
