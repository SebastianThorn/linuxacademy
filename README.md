# linuxacademy
Ansible-jobb to bootstrap playground servers on LinuxAcademy

# SUDO
dnf install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm
dnf install -y ansible git-core
ansible-pull -U https://github.com/SebastianThorn/linuxacademy new_rhel8.yml

