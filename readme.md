# Ubuntu Termux Root
Install Ubuntu Base 21.10 on the root of your smartphone with termux. To start the system, use the command `ubuntu`.

## Warning!
Install it yourself, I will not be responsible for any damage that may happen to your device.
## Request
• Magisk

• Architecture arm64, armhf, amd64 or x86_64
## Installation
Enter the shell command below in Termux to be able to install.
```bash
curl -s -L https://raw.githubusercontent.com/B4gol/rooted-ubuntu-termux/master/install.sh -o install && bash install
```
## Uninstall
First stop all services and exit ubuntu with command `exit` then close termux, then enter the shell command below in Termux to be able to uninstall. If not, restart your smartphone and start the code again.
```bash
ubuntu -u
```
Or
```bash
ubuntu --uninstall
```
### Problem no apt upgrade
If you can't do the `apt upgrade`, this problem happens due to ubuntu not recognizing kernel version correctly in libc6, use below command to "maneuver" this problem. 
```bash
apt-mark hold libc6
```
NextGen: https://t.me/B4gol
