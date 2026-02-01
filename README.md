> This project demonstrates real-world Ansible role development and automation practices used in enterprise environments.

# Ansible Web Server Role Automation

This project demonstrates a complete Ansible-based automation solution using **custom Ansible roles** to install, configure, test, and manage an Apache web server on Ubuntu systems.
The project follows Ansible best practices, including structured roles, reusable playbooks, templates, handlers, and automated validation.

---

## 📌 Project Features

- Custom Ansible role for Apache web server
- Role-based directory structure (tasks, handlers, templates, vars, defaults)
- Jinja2 templates for dynamic configuration
- Support for custom variables and overrides
- Service management using handlers
- Automated testing and validation
- Cleanup playbook for complete removal
- Fully documented and GitHub-ready

---

## 🛠 Technologies Used

- Ansible
- Apache (apache2)
- YAML
- Jinja2 Templates
- Linux (Ubuntu)
- Systemd
- UFW Firewall

---

## 📂 Project Structure
project structure file is availiable you can see it in this directory

---

## 🚀 How to Run

### 1️⃣ Install Ansible
```bash
pip3 install ansible
2️⃣ Verify Setup
ansible all -m ping
3️⃣ Deploy Web Server
ansible-playbook webserver-playbook.yml
4️⃣ Deploy with Custom Configuration
ansible-playbook custom-webserver-playbook.yml
5️⃣ Test the Role
ansible-playbook test-webserver-role.yml
6️⃣ Cleanup Deployment
ansible-playbook cleanup-webserver.yml

⚙ Customization
You can override default variables directly in the playbook:

vars:
  site_title: "Custom Website"
  webserver_port: 8080
  webserver_server_name: example.com

✅ Validation & Testing
Apache package verification
Service status checks
HTTP response validation
Configuration file existence checks

📚 Learning Outcome
This project strengthens practical understanding of:

Ansible Roles
Infrastructure as Code (IaC)
Configuration Management
Reusable automation design
DevOps best practices


👤 Author
Saad Khan
Cloud devops engineer 

---
