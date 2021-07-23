# Ansible Role for SQLite

[![Gitlab pipeline status](https://img.shields.io/gitlab/pipeline/alvistack/ansible-role-sqlite/master)](https://gitlab.com/alvistack/ansible-role-sqlite/-/pipelines)
[![GitHub release](https://img.shields.io/github/release/alvistack/ansible-role-sqlite.svg)](https://github.com/alvistack/ansible-role-sqlite/releases)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-sqlite.svg)](https://github.com/alvistack/ansible-role-sqlite/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/galaxy-alvistack.sqlite-blue.svg)](https://galaxy.ansible.com/alvistack/sqlite)

Ansible Role for SQLite Installation.

## Requirements

This role require Ansible community package 4.3 or higher.

This role was designed for:

  - Ubuntu 18.04, 20.04, 20.10, 21.04
  - CentOS 7, 8 Stream
  - openSUSE Leap 15.2, Leap 15.3, Tumbleweed
  - Debian 10, 11
  - Fedora 33, 34
  - RHEL 7, 8

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

[ansible-galaxy-requirements.yml](ansible-galaxy-requirements.yml)

## Example Playbook

[molecule/default/converge.yml](molecule/default/converge.yml)

This role could simply deploy to `localhost` as below:

    molecule converge -s default

## License

  - Code released under [Apache License 2.0](LICENSE)
  - Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

## Author Information

  - Wong Hoi Sing Edison
      - <https://twitter.com/hswong3i>
      - <https://github.com/hswong3i>
