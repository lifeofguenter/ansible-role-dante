# Ansible Role: Dante (SOCKS Proxy Server)

An Ansible role that compiles & installs Dante on Debian flavoured systems.

## Requirements

None

## Role Variables

Available variables are listed below, along with default values:

    dante_version: 1.4.1
    dante_working_dir: /tmp

## Dependencies

None

## Example Playbook

    - hosts: socks
      roles:
        - { role: lifeofguenter.dante }

## License

MIT