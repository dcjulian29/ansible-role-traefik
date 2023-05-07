# Ansible Role: traefik

[![Lint](https://github.com/dcjulian29/ansible-role-traefik/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-traefik/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-traefik.svg)](https://github.com/dcjulian29/ansible-role-traefik/issues)

This an Ansible role to install Traefik, a modern reverse proxy and load balancer that can be configured statically and dynamically.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.traefik
  src: https://github.com/dcjulian29/ansible-role-traefik.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- Ansible Role: `dcjulian29.docker`
- Ansible Role: `geerlingguy.pip`
