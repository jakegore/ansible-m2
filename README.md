# Ansible M2

**This is a WIP and is not recommended for production use!**

This playbook will provision a new Magento 2 instance.

## Usage

1. Ensure that the values in the following files are correct:

- `hosts`
- `group_vars/dbservers`
- `group_vars/webservers`

2. Run `ansible-playbook -i hosts site.yml`

---

&copy; 2023 Jake Gore
