

This project uses **Ansible** to:
- Provision an EC2 instance 
- Install **Docker**
- Deploy an **Nginx container** that serves a custom `index.html` page.

## Files
- `inventory.ini`: Defines where Ansible will run
- `playbook.yml`: Automates the installation and deployment
- `index.html`: HTML file that Nginx serves
- `README.md`: This file you're reading

## How to Run (Locally)
## Make sure Ansible is installed
1. Open Terminal in VS Code
2. Run:
cd /mnt/d/ansible-docker-project
ansible-playbook -i inventory.ini playbook.yml
3. Access the webpage
http://localhost