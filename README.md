# Ansible Role: MkDocs

[![Ansible Galaxy](http://img.shields.io/badge/galaxy-novuso.mkdocs-000000.svg)](https://galaxy.ansible.com/list#/roles/3893)
[![MIT License](http://img.shields.io/badge/license-MIT-003399.svg)](http://opensource.org/licenses/MIT)
[![Build Status](https://travis-ci.org/novuso/ansible-role-mkdocs.svg)](https://travis-ci.org/novuso/ansible-role-mkdocs)

An Ansible role that manages MkDocs on Ubuntu 14.04

## Requirements

None

## Role Variables

Ansible variables are listed here along with their default values:

`mkdocs_keep_updated` flags whether or not to keep mkdocs updated.

    mkdocs_keep_updated: true

## Dependencies

None

## Example Playbook

    ---
    - hosts: all
      roles:
      - novuso.mkdocs

## License

This is released under the [MIT license](http://opensource.org/licenses/MIT).
