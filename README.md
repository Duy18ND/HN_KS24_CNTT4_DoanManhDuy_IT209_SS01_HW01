-rw------- 1 root root  104 Oct  1 08:03 authorized_keys
root@Duy18ND:~# exit
logout
Connection to 221.121.3.153 closed.
PS C:\WINDOWS\system32> ssh -i $HOME\.ssh\id_ed25519 root@221.121.3.153
Welcome to Ubuntu 22.04.5 LTS (GNU/Linux 5.15.0-143-generic x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/pro

This system has been minimized by removing packages and content that are
not required on a system that users do not log into.

To restore this content, you can run the 'unminimize' command.
New release '24.04.5 LTS' available.
Run 'do-release-upgrade' to upgrade to it.

Last login: Thu Oct  1 07:59:30 2026 from 42.117.128.94
root@Duy18ND:~# whoami
root
root@Duy18ND:~# lsb_release -a
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 22.04.5 LTS
Release:        22.04
Codename:       jammy
root@Duy18ND:~# hostname
Duy18ND
root@Duy18ND:~#
