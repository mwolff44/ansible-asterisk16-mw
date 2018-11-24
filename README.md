# Ansible Role: ansible-asterisk16-mw

* Master branch: [![Build Status](https://travis-ci.org/mwolff44/ansible-asterisk16-mw.svg?branch=master)](https://travis-ci.org/mwolff44/ansible-asterisk16-mw)


Ansible role for asterisk 16

## Using the role
### Installation
```
ansible-galaxy install ansible-asterisk16-mw
```

### Example Playbook
```
  - hosts: all
    roles:
      - ansible-asterisk16-mw
```

### Variables

See [`defaults/main.yml`](defaults/main.yml).

## Testing the role

### Dependencies
- molecule
- docker
