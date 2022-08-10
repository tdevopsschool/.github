## Windows with ADMIN rights 🖼
Use `1. Vagrant` or `2. WSL` but not together

### 1. Vagrant
#### Vagrant Preparation
1. You need some terminal to execute linux-like shell commands. Install [git-bash](https://gitforwindows.org/)
2. Install [Vagrant](https://www.vagrantup.com/downloads) and [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

- <i>*Tested versions - **Vagrant 2.0.0** and **VB 5.1.36** OR **Vagrant 2.2.16** and **VB 6.1.22** OR just try latest versions</i>

- <i>*Vagrant [mirror](https://www.filecroco.com/download-vagrant/download/)</i>

#### VM installation
1. Open git-bash or any another terminal with git
2. Clone git repository [tdevopsschool/6-CFM](https://github.com/tdevopsschool/6-CFM)
```bash
git clone https://github.com/tdevopsschool/6-CFM.git
```
3. Execute `vagrant up` command in directory with Vagrantfile
4. Check the installation logs, if everything is OK you may go inside VM `vagrant ssh`

#### Vagrant tips
- Type exit command if you are inside the VM - `exit`
- Use `vagrant halt` to stop the VM before poweroff a laptop
- See `vagrant -h` to list all commands

#### Install all necessary tools from Linux section
LINK TO BE DONE 
### 2. Windows subsystem linux

#### Install WSL2 and Ubuntu 
https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-10#1-overview

#### Install all necessary tools from Linux section
LINK TO BE DONE 
