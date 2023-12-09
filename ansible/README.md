# Ansible

I am using [my fork of techno-tim/k3s-ansible](https://github.com/tom-elvidge/k3s-ansible) to configure all my cluster nodes with Ansible.

Clone that repository separately and run the ansible playbook. Examples assume k3s-ansible was cloned at the same level as this repository and use relative paths as needed.

The `k3s_token` in `kevin/group_vars/all.yml` needs to be updated before running the playbook.

```sh
ansible-playbook ../k3s-ansible/site.yml -i ./ansible/kevin/hosts.ini
```