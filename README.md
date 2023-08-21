# Ansible M2

**This is a WIP and is not recommended for production use!**

This playbook will provision a new Magento 2 instance.

## Usage

1. Ensure that the values in the following files are correct:

- `hosts`
- `group_vars/all`
- `group_vars/webservers`

2. Run `ansible-playbook -i hosts site.yml`

## Todo

- [X] Run Magento install commands
- [ ] Run apt update before anything
- [ ] Add custom admin URL
- [ ] Add proper Nginx configuration
- [ ] Add in Varnish
- [ ] Set up magento user on system instead of root
- [ ] Set up correct DB & Search host during Magento install
- [ ] Set up firewall
- [ ] Improve Opensearch tasks

---

&copy; 2023 Jake Gore
