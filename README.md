# Ansible Role: Nginx tarantool upstream module
                                                                                            
[![Build Status](https://travis-ci.org/berkut3128/ansible-tarantool-nginx.svg?branch=master)](https://travis-ci.org/berkut3128/ansible-tarantool-nginx)

Install and assembly Nginx tarantool upstream module on Ubuntu servers.

## Requirements

No special requirements; note that this role requires root access, so either run it in a playbook with a global `become: yes`

## Dependencies

None.

## Example Playbook

    - hosts: server
      become: yes
      roles:
        - { role: "ansible-tarantool-nginx" }

