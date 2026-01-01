# Ansible Web Orchestration Lab 🚀

This repository documents a hands-on project in **Infrastructure as Code (IaC)**. I built a multi-node environment where a single Ansible Master node orchestrates the deployment and deep customization of professional web servers across an AWS EC2 cluster.



## 🎯 Project Goals
* **Automate** the installation of Apache (`httpd`) and Git across multiple RHEL/Amazon Linux nodes.
* **Deploy** a professional Bootstrap portfolio theme directly from a remote GitHub repository.
* **Orchestrate** surgical content changes (Title, Sub-heading, and Avatar) across the cluster using the Ansible `replace` module with Regex.
* **Ensure Idempotency** to guarantee consistent states across the entire infrastructure.

## 🛠 Tech Stack
* **Configuration Management:** Ansible
* **Infrastructure:** AWS EC2
* **Web Server:** Apache (httpd)
* **Search/Replace:** Regular Expressions (Regex)
* **Version Control:** Git

## 📂 Project Structure
* `setup_webserver.yml`: The main automation playbook.
* `inventory.ini`: Defined server list and SSH connection parameters (IPs redacted for security).
* `.gitignore`: Security filters to prevent sensitive files (like `.pem` keys) from being tracked.
* `README.md`: Project documentation.

## 📸 Results
### Terminal Execution
*The screenshot below shows the successful execution of the playbook, highlighting the "Changed" status for the customization tasks.*

![Ansible Terminal Output](terminal_output.png)

### Final Customized Website
*The final result showing the "MY ANSIBLE CLUSTER" title, custom sub-heading, and AI-generated avatar.*

![Web Server Result](website_result.png)

## 🚀 Key Learning Moments
During this lab, I successfully navigated:
1. **SSH Key Management:** Established secure communication between cloud instances.
2. **Regex Implementation:** Used `(?i)` flags to handle case-insensitive text replacement at scale.
3. **Module Compatibility:** Resolved errors regarding unsupported parameters in older Ansible versions.
4. **Security Best Practices:** Implemented `.gitignore` and redacted sensitive IP addresses for public documentation.

---
*Developed as a hands-on lab to master Cloud Automation and DevOps best practices.*