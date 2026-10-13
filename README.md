# 🐧 Linux for Cloud & DevOps

### Hands-On Learning • System Administration • Automation

A practical learning repository documenting my journey of mastering Linux fundamentals and applying them to cloud computing, server administration, networking, and DevOps workflows.

---

## 📌 About This Repository

Linux is a core technology behind cloud infrastructure, containers, automation, and modern application deployments.

This repository serves as my technical learning journal, where I document Linux commands, concepts, hands-on exercises, troubleshooting experiences, and practical implementations.

My focus is on understanding how Linux systems work and developing the skills required to manage servers, automate tasks, troubleshoot infrastructure, and work with cloud and DevOps technologies.

Rather than simply memorizing commands, I aim to understand their purpose, behaviour, and real-world applications.

## 🎯 Learning Objectives

- Build a strong foundation in Linux and command-line operations.
- Understand filesystems, users, groups, and permissions.
- Manage processes, services, packages, and system resources.
- Develop Linux networking and troubleshooting skills.
- Learn Bash scripting and task automation.
- Understand SSH and remote Linux server administration.
- Apply Linux knowledge to AWS cloud infrastructure.
- Prepare for working with Docker, CI/CD, and infrastructure automation.

## 🛠️ Learning Environment

| Component | Details |
|---|---|
| Operating System | Ubuntu Linux |
| Shell | Bash |
| Terminal | Ubuntu Terminal |
| Version Control | Git |
| Documentation | Markdown |
| Cloud Platform | AWS — practical application as I progress |

## 📚 Learning Roadmap

### 01. Linux Fundamentals
- [ ] Introduction to Linux and its architecture
- [ ] Understanding the shell and terminal
- [ ] Linux filesystem hierarchy
- [ ] Essential commands: `pwd`, `ls`, `cd`, `whoami`, `uname`
- [ ] Getting help with `man` and command options

### 02. File and Directory Management
- [ ] Creating, copying, moving, and deleting files
- [ ] Directory navigation and management
- [ ] Reading files with `cat`, `less`, `head`, and `tail`
- [ ] Searching with `find` and `grep`
- [ ] Redirection, pipes, and command chaining

### 03. Users, Groups, and Permissions
- [ ] User and group management
- [ ] Understanding file ownership and permissions
- [ ] Working with `chmod`, `chown`, `id`, and `sudo`
- [ ] Environment variables and shell configuration
- [ ] SSH keys and secure remote access

### 04. Package Management
- [ ] Understanding APT and package repositories
- [ ] Installing, updating, and removing packages
- [ ] Managing software dependencies
- [ ] Installing common Linux server utilities

### 05. Processes and Services
- [ ] Process management using `ps`, `top`, and `kill`
- [ ] Managing services using `systemctl`
- [ ] Investigating logs with `journalctl`
- [ ] Understanding background processes
- [ ] Monitoring CPU, memory, and system load

### 06. Linux Networking
- [ ] IP addresses and network interfaces
- [ ] Routing tables and default gateways
- [ ] DNS resolution and connectivity
- [ ] Ports, sockets, and listening services
- [ ] Troubleshooting using `ping`, `ip`, `ss`, `curl`, and `dig`
- [ ] SSH connectivity and remote administration

### 07. Storage and System Monitoring
- [ ] Disk usage with `df` and `du`
- [ ] Filesystems, partitions, and mounts
- [ ] Memory monitoring with `free`
- [ ] System resource monitoring
- [ ] Log analysis and disk-space troubleshooting

### 08. Bash Scripting and Automation
- [ ] Variables and user input
- [ ] Conditional statements and loops
- [ ] Functions, exit codes, and command-line arguments
- [ ] Automating repetitive administrative tasks
- [ ] Scheduling jobs with `cron`
- [ ] Writing reusable Bash scripts

### 09. Linux for Cloud Computing
- [ ] Understanding Linux-based cloud servers
- [ ] Connecting to AWS EC2 using SSH
- [ ] Managing server users, permissions, and packages
- [ ] Configuring and troubleshooting network services
- [ ] Monitoring server health and investigating logs
- [ ] Understanding the relationship between AWS security groups and host firewalls

### 10. Linux for DevOps
- [ ] Git workflows from the command line
- [ ] Running and troubleshooting applications on Linux
- [ ] Docker fundamentals and container management
- [ ] Application logs and process management
- [ ] Introduction to CI/CD workflows
- [ ] Bash-based automation
- [ ] Preparing for infrastructure automation with Terraform

*The roadmap represents planned learning areas. Progress will be updated as I complete hands-on practice.*

## 📂 Repository Structure

```text
linux-cloud-devops/
├── README.md
├── 01-linux-fundamentals/
│   └── notes.md
├── 02-file-management/
│   └── commands.md
├── 03-users-and-permissions/
│   └── commands.md
├── 04-package-management/
│   └── commands.md
├── 05-processes-and-services/
│   └── commands.md
├── 06-linux-networking/
│   └── commands.md
├── 07-storage-and-monitoring/
│   └── commands.md
├── 08-bash-scripting/
│   ├── notes.md
│   └── scripts/
├── 09-cloud-computing/
│   └── ec2-practice.md
├── 10-devops-practice/
│   └── exercises.md
└── troubleshooting.md
```

Directories and files will be added gradually as I progress through each topic.

## 💻 Initial Command-Line Practice

The following commands demonstrate some of the basic operations I am practising in Ubuntu.

### System Information

```bash
# Display the current user
whoami

# Display the current working directory
pwd

# Display kernel and system information
uname -a
```

### Filesystem and Storage

```bash
# List files, including hidden entries
ls -la

# Display available filesystem space
df -h

# Display the size of a directory
du -sh .
```

### Processes and Networking

```bash
# Display running processes
ps aux

# Display available memory
free -h

# Display network interfaces and IP addresses
ip addr

# Display listening sockets
ss -tuln
```

These commands are introductory examples. Further notes will include explanations, observed outputs, use cases, and practice exercises.

## 🧪 Documentation Approach

Each topic will be documented using a consistent, practical format.

- **Concept:** What I learned and why it matters.
- **Command Syntax:** How the command works.
- **Practical Examples:** Commands executed in my environment.
- **Output and Observations:** What I observed during execution.
- **Hands-On Exercises:** Tasks to reinforce understanding.
- **Troubleshooting:** Errors, root causes, and solutions.
- **Cloud/DevOps Relevance:** How the concept applies to infrastructure and automation.

## 🔧 Learning Methodology

My learning process follows four steps:

1. **Learn** — Understand the underlying concept.
2. **Practise** — Execute commands in a Linux environment.
3. **Document** — Record examples and observations in Markdown.
4. **Troubleshoot** — Investigate problems and understand their causes.

The objective is to build practical knowledge through consistent experimentation rather than theoretical study alone.

## ☁️ Future Practical Applications

As my knowledge develops, I plan to apply these skills to:

- Linux server administration
- AWS EC2 management and troubleshooting
- Network connectivity and service diagnostics
- Bash scripting and operational automation
- Docker containers and application deployment
- CI/CD fundamentals
- Infrastructure automation using Terraform

These are future learning objectives, and I will document practical work as I complete it.

## 📖 References and Resources

- [Ubuntu Documentation](https://help.ubuntu.com/)
- [Ubuntu Server Documentation](https://documentation.ubuntu.com/server/)
- [Linux man-pages Project](https://www.kernel.org/doc/man-pages/)
- [GNU Bash Reference Manual](https://www.gnu.org/software/bash/manual/)
- [AWS Documentation](https://docs.aws.amazon.com/)
- [Docker Documentation](https://docs.docker.com/)
- [Git Documentation](https://git-scm.com/doc)
- [Terraform Documentation](https://developer.hashicorp.com/terraform/docs)

## 📈 Progress Tracking

Progress will be tracked through completed exercises, practical command usage, troubleshooting tasks, and small projects.

I will update this repository as I gain experience and move from Linux fundamentals toward cloud infrastructure and DevOps practices.

## ⚠️ Safe Practice

Commands that modify files, permissions, packages, or system configuration should be understood before execution. Experiments involving administrative privileges will be performed carefully in an appropriate environment.

Sensitive information such as passwords, access tokens, private keys, and cloud credentials will not be committed to this repository.

---

**Learn. Practise. Automate. Troubleshoot. Repeat.** 🐧
