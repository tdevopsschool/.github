# macOS 💻
## General step
### Oh my zsh
- https://ohmyz.sh/#install

⚠️ **Strongly recommended for macbook usage by default**

### Installer/Package Manager
- Homebrew for macOS: https://brew.sh/

⚠️ **Strongly recommended for macbook usage by default**

### Code Editor
- Intellij IDE: https://www.jetbrains.com/idea/download/

OR

- Alternative, e.g. Visual Studio Code: https://code.visualstudio.com/download

➔ **WHEN NEEDED** - `1. DevToolKit module`

## 1. Bare OS

### Git CLI
- Git Command Line Tool: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

➔ **WHEN NEEDED** - `1. DevToolKit module`

### Java - OpenJDK
- v1.8 for INTEL: https://mkyong.com/java/how-to-install-java-on-mac-osx/

OR

- v1.8 for M1:
1. Download zip from https://www.azul.com/downloads/?version=java-8-lts&os=macos&architecture=arm-64-bit&package=jdk
2. Unzip into /Library/Java/JavaVirtualMachines
3. Rename folder to zulu-8.jdk
```
sudo mv zulu8.64.0.15-ca-jdk8.0.342-macosx_aarch64 zulu-8.jdk
```
4. Add configuration
```
echo 'export JAVA_HOME=/Library/Java/JavaVirtualMachines/zulu-8.jdk' >> ~/.zshrc
```

➔ **WHEN NEEDED** - `1. DevToolKit module`

### PostgreSQL v.13
- https://www.postgresql.org/download/

➔ **WHEN NEEDED** - `1. DevToolKit module`

### Docker and Docker-Compose
1. Docker: https://docs.docker.com/get-docker/
2. Docker-Compose: https://docs.docker.com/compose/install/

➔ **WHEN NEEDED** - `2. Docker module`

### Kubectl
- kubectl: https://kubernetes.io/docs/tasks/tools/install-kubectl/

➔ **WHEN NEEDED** - `4. Kubernetes module`

### AWS CLI, AWS-IAM-AUTHENTICATOR, EKSCTL
1. AWS CLI: https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html
2. Eksctl: https://eksctl.io/introduction/#installation
3. Aws-iam-authenticator: https://docs.aws.amazon.com/eks/latest/userguide/install-aws-iam-authentica
tor.html

➔ **WHEN NEEDED** - `5. AWS module`

### CFM
1. Terraform: https://learn.hashicorp.com/tutorials/terraform/install-cli
2. Ansible: https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.ht
ml#installing-ansible-on-specific-operating-systems

➔ **WHEN NEEDED** - `6. CFM module`

## 2. Vagrant VM
### Apple silicon (M1) CPU
#### Preparation
```
brew install vagrant
brew install qemu
vagrant plugin install vagrant-qemu
```
*Source - https://github.com/ppggff/vagrant-qemu*

#### VM installation
1. Open git-bash or any another terminal with git
2. Clone git repository [tdevopsschool/6-CFM](https://github.com/tdevopsschool/6-CFM)
    - `git clone https://github.com/tdevopsschool/6-CFM.git`
3. `cd mac-demo`
4. Execute `vagrant up --provider qemu` command in directory with Vagrantfile
5. Check the installation logs, if everything is OK you may go inside VM `vagrant ssh`

#### Install all necessary tools from Linux section
LINK TO BE DONE 

### Intel (x86-64) CPU
#### Preparation
```
brew install vagrant
brew install --cask virtualbox 
```

#### VM installation
1. Open git-bash or any another terminal with git
2. Clone git repository [tdevopsschool/6-CFM](https://github.com/tdevopsschool/6-CFM)
    - `git clone https://github.com/tdevopsschool/6-CFM.git`
3. Execute `vagrant up` command in directory with Vagrantfile
4. Check the installation logs, if everything is OK you may go inside VM `vagrant ssh`

#### Install all necessary tools from Linux section
LINK TO BE DONE 

### Vagrant tips
- Type exit command if you are inside the VM - `exit`
- Use `vagrant halt` to stop the VM before poweroff a laptop
- See `vagrant -h` to list all commands
