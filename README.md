# ansible-role-letsencrypt

Ansible role to install and use Let's Encrypt.

## Requirements

* Ansible version 2.*

## Role Variables

You can override all the variables in `defaults/main.yml`.

## Example Playbook

    - hosts: servers
      roles:
         - { role: monsieurbiz.letsencrypt }

## License

MIT

## Authors

* Jacques Bodin-Hullin - [@jacquesbh](https://twitter.com/jacquesbh)
