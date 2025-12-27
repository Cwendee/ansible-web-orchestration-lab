# Ansible Web Orchestration Lab 🚀

This repository documents my journey in mastering **Infrastructure as Code (IaC)**. I built a multi-node environment where a single Ansible Master node orchestrates the deployment and deep customization of professional web servers.



## 🎯 Project Goals
* **Automate** the installation of Apache and Git across multiple RHEL/Amazon Linux nodes.
* **Deploy** a professional Bootstrap portfolio theme directly from a remote GitHub repository.
* **Orchestrate** surgical content changes (Title, Sub-heading, and Avatar) across the cluster using the Ansible `replace` module with Regex.
* **Ensure Idempotency** so that rerunning the playbook only changes what is necessary.

## 🛠 Tech Stack
* **Configuration Management:** Ansible
* **Infrastructure:** AWS EC2
* **Web Server:** Apache (httpd)
* **Branding:** Jinja2 & Regex customization
* **Version Control:** Git

## 📂 Project Structure
* `setup_webserver.yml`: The main automation playbook.
* `inventory.ini`: Defined server list and SSH connection parameters.
* `README.md`: Project documentation.

## 🚀 Key Learning Moments
During this lab, I successfully navigated:
1. SSH key authentication between cloud instances.
2. Troubleshooting YAML syntax and indentation.
3. Managing Ansible module compatibility (handling `ignore_case` vs Regex flags).
4. Dynamic file manipulation to personalize web content at scale.

---
*Developed as a hands-on lab to master Cloud Automation and DevOps best practices.*