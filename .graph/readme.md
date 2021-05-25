# net-template
Ansible hosts template for Playbooks

Consists of a few Ansible inventory templates and a init.sh script.

# How to add
- Add this `net` folder and .gitignore to your ansible project and commit it.
- `net/templates`: You can edit these to match your network & project.
- `.gitignore:` Everything in `hosts/` only applies locally and will be ignored by git.
- `ansible.cfg`: is used to set hosts as it's default inventory.


# Using ansible-playbook
- First run `net/init.sh` after git clone. This copies `templates/` into `hosts/`
- Now you now can edit `hosts/` to match your network.
- and run `ansible-playbook _[file]_` normally

