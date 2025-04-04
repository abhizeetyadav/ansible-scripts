# 🛠️ part01-create-user: Linux User Creation and Update Automation with Ansible


# 👤 User Creation with Ansible

This Ansible playbook automates the process of creating a new Linux user, setting up SSH keys, assigning groups, and enforcing password policies. It is ideal for system administrators and DevOps teams who want to streamline user provisioning across servers.

---

## 🧾 What It Does

- ✅ Creates a new user (default: `devops`)
- 🔐 Generates an SSH key pair for the user
- 👥 Adds the user to `root` and `wheel` groups
- 🛡️ Sets a login password and password expiration policy

---










# 🛠️ part02-update-linux: This Ansible playbook automates the update process for Linux systems (Debian/Ubuntu and RedHat/CentOS-based). It ensures that all packages are upgraded using the appropriate package manager (`apt`, `yum`, or `dnf`), depending on the system.

---

## 📦 What This Does

- 🔄 Updates all installed packages
- 🧠 Detects and uses correct package manager (apt/yum/dnf)
- 🔐 Can be extended to include automatic reboots after updates

---


