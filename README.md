# Ansible Automation Practice & Mini Projects

This repository contains my hands-on practice and mini projects created while learning **Ansible** for Linux server automation and configuration management.

It includes multiple playbooks covering core Ansible concepts and a role-based project that deploys and configures a web server with a custom index page.

---

## 📌 What This Repo Covers

I created and tested playbooks for:

- User management and password setup
- Package installation
- File copy and file modifications
- File permissions
- Running shell commands
- Cron job creation and modification
- Process management
- Downloading files
- Firewall configuration using firewalld
- Conditional task execution
- Tags and handlers
- Variables usage
- Role-based structure

---

## 📂 Repository Structure


---

## ▶️ Playbooks Included

| Playbook | Purpose |
|----------|----------|
01_first_pb.yml | Basic Ansible playbook |
02_copy_files.yml | Copy files to managed nodes |
03_files_mod.yml | Modify file content |
04_permission.yml | Change file permissions |
05_shell_run.yml | Execute shell scripts |
06_cron_jobs.yml | Create cron jobs |
07_cron_modify.yml | Modify cron jobs |
08_user_mgm.yml | User management |
09_set_passwd.yml | Set user password |
10_app_install.yml | Install packages |
11_kill_process.yml | Manage processes |
12_download_file.yml | Download files |
13_firewalld.yml | Firewall configuration |
14_conditions.yml | Conditional tasks |
15_roles.yml | Execute roles |

---

## 🚀 Mini Project — HTTPD Setup Using Roles

A reusable Ansible role that:

- Installs httpd package
- Starts and enables service
- Configures firewall rules
- Deploys a custom `index.html`
- Uses handlers for service reload
- Uses variables for flexibility

### Role Name:

---

## 🛠 Tools & Technologies

- Ansible
- Linux
- YAML
- HTTPD / NGINX
- Firewalld
- Git & GitHub

---

## ▶️ How to Run a Playbook

```bash
ansible-playbook -i hosts playbooks/10_app_install.yml
ansible-playbook play.yml --tags install
