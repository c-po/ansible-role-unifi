# Ansible role `unifi`

An Ansible role for installing Ubiquiti Unifi Controller on a Debian Host.

Tested on Debian 10 (Buster)

- install all necessary packages

## Requirements

none

## Dependencies

none

## License

BSD

## Author Information

Christian Poessinger (christian@poessinger.com)

## Example Playbook

```
$ cat unifi.yml
- hosts: unifi
  remote_user: root
  become_method: sudo
  become_user: root
  roles:
    - ansible-role-unifi
```
