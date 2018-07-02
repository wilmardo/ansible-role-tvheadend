# wilmardo.ansible-role-tvheadend

[![Build Status](https://travis-ci.org/wilmardo/ansible-role-tvheadend.svg?branch=master)](https://travis-ci.org/wilmardo/ansible-role-tvheadend)
[![Galaxy](https://img.shields.io/badge/galaxy-wilmardo.ansible-role-tvheadend-blue.svg)](https://galaxy.ansible.com/wilmardo/ansible-role-tvheadend/)

Role to install TV Headend and Oscam in one go!

## Requirements

None.

## Role Variables

### Default usage

As default ansible-role-tvheadend is installed and running.
If you want to adapt this to your needs look at the [Advanced usage](#advanced-usage) section.

### Advanced usage

For more advanced usage the following variables are available:
```yaml
# see defaults/main.yml
```

## Dependencies

None

## Example Playbook

Install ansible-role-tvheadend with the default settings
```yaml
- hosts: all
  roles:
     - role: wilmardo.ansible-role-tvheadend
```

## License

BSD-3-Clause-Clear

## Author Information

This role was created in 2018 by [Wilmar den Ouden](https://wilmardenouden.nl).
