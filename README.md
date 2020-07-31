# Setup and Deploy Bookstack Wiki

This assumes the server has been set up using the ubuntu-server-ansible playbook.

To deploy run:

    ansible-playbook -i inventory.linode -u root --ask-vault-pass playbook.yml
