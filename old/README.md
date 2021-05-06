# UniNet-Dynamic-Inventory
Add this to every Ansible, Juju, or SaltStack project to enable UniNetwork integration! Has examples, and a .gitignore allows users to define their own inventory.

Run a `.net/init.sh` setup call before you run ansible-playbook or Juju!
- `.net/init.sh`  # Dynamic using your ~/.uni profile
- `.net/init.sh --static`  # Static, edit .net/uninet for specific project
