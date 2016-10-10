# How to Run Playbook

```sh
# Only localhost
ansible-playbook site.yml [--check|-C]
# For some hosts
ansible-playbook -i HOST1,HOST2,..., site.yml [--check|-C]
```
