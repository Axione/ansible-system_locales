# ansible-system_locales

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_locales-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_locales)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_locales.svg)](https://github.com/lotusnoir/ansible-system_locales/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_locales?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56928)](https://galaxy.ansible.com/lotusnoir/system_locales)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56928)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Configure system language

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: system_locales
          become: yes
          become_method: sudo
          gather_facts: yes
          roles:
            - role: ansible-system_locales


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

