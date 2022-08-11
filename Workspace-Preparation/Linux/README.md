## Linux 🐧
### Code Editor
- Intellij IDE: https://www.jetbrains.com/idea/download/

OR

- Alternative, e.g. Visual Studio Code: https://code.visualstudio.com/download

➔ **WHEN NEEDED** - `1. DevToolKit module`

### Git CLI
- Git Command Line Tool: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

➔ **WHEN NEEDED** - `1. DevToolKit module`

### Java - OpenJDK v1.8
Check before to install
```bash
$ java -version
openjdk version "1.8.0_342"
OpenJDK Runtime Environment (Zulu 8.64.0.15-CA-macos-aarch64) (build 1.8.0_342-b07)
OpenJDK 64-Bit Server VM (Zulu 8.64.0.15-CA-macos-aarch64) (build 25.342-b07, mixed mode)
```

- Debian or Ubuntu - https://docs.datastax.com/en/jdk-install/doc/jdk-install/installOpenJdkDeb.html
- CentOS - https://phoenixnap.com/kb/install-java-on-centos#ftoc-heading-8
- Manually - https://www.azul.com/downloads/?version=java-8-lts&package=jdk

➔ **WHEN NEEDED** - `1. DevToolKit module`

### PostgreSQL v.13
- https://www.postgresql.org/download/
- CentOS 7:
```
sudo yum install -y https://download.postgresql.org/pub/repos/yum/reporpms/EL-7-x86_64/pgdg-redhat-repo-latest.noarch.rpm
sudo yum install -y postgresql13-server
sudo /usr/pgsql-13/bin/postgresql-13-setup initdb
sudo systemctl enable postgresql-13
sudo systemctl start postgresql-13
```

➔ **WHEN NEEDED** - `1. DevToolKit module`

### Node v.14
- Ubuntu - https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04
- CentOS 7:
```bash
sudo su
curl -fsSL https://rpm.nodesource.com/setup_14.x | bash -
yum install -y nodejs
```
- Manually - https://nodejs.org/en/download/

➔ **WHEN NEEDED** - `1. DevToolKit module`

### Yarn v.1
- https://classic.yarnpkg.com/lang/en/docs/install/#debian-stable

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
