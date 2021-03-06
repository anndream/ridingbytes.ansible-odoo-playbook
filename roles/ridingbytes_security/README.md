# RIDING BYTES: Security Role

This role ensures a secure environment for [Odoo][1].


## Dependecies

This role depends on the [Firewall Role][9].

## Role Variables

Please use the variables from the [Ansible Firewall Role][9].
This role uses some defaults of these variables that listed below, along with
default values (see `vars/main.yml`):

    firewall_open_tcp_ports: [80, 443]

Input TCP open ports list.

Note: SSH Port is dynamically fetched and open by default.

    firewall_use_fail2ban: false

Enable [Fail2ban][10] service.


[1]:  http://ridingbytes.com "RIDING BYTES"
[2]:  https://odoo.com "Odoo ERP"
[3]:  https://www.vagrantup.com/docs/getting-started/ "Vagrant"
[4]:  https://www.ansible.com "Ansible"
[5]:  https://docs.ansible.com/ansible/playbooks.html "Ansible Playbook"
[6]:  https://docs.ansible.com/ansible/playbooks_roles.html "Ansible Roles"
[7]:  https://galaxy.ansible.com "Ansible Galaxy"
[8]:  https://docs.ansible.com/ansible/intro_inventory.html "Ansible Inventory"
[9]:  https://galaxy.ansible.com/HanXHX/firewall/ "Firewall"
[10]: http://www.fail2ban.org/wiki/index.php/Main_Page "Firewall"
