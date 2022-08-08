# 1. DevOps school content
1. DevToolKit: Git, Gradle, Python
2. Docker
3. GitLab CI/CD
4. Kubernetes + Helm 3
5. AWS theory
6. CFM: Ansible, Terraform
7. Monitoring: Prometheus, Grafana

# 2. Workspace preparation

## macOS 💻
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


## Windows with ADMIN rights 🖼
TO BE DONE

## Nucleus 🤷
You must have remote Linux VM somewhere (AWS e.g.)
1. Install Putty for SSH connection to remote VM
2. Install all requirements when particular topic is arised through the course

