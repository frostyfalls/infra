# infra

This is a collection of Ansible roles and playbooks for my personal
infrastructure I use.

## Technical

* Nearly all uses are for Void Linux specifically
* Services are expected to be used by <5 people at most
* Upkeep is intended to be automated after playbooks are ran
* Very little secrets or `ansible-vault` entries are kept

## Usage

```
# Primary playbook
ansible-playbook -DK main.yml
```

## Future Additions

* [ ] PostgreSQL role
* [ ] Static network configuration role
* [ ] ACME automation role
* [ ] System maintenance playbook
* [ ] nginx role
