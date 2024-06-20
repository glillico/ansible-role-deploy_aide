# Ansible Role : deploy_aide

[![CI](https://github.com/glillico/ansible-role-deploy_aide/workflows/CI/badge.svg)](https://github.com/glillico/ansible-role-deploy_aide/actions?query=workflow%3ACI)


Installs and configures aide.

## Requirements

None.

## Role Variables

### defaults Directory

|Variable|Description|
|---|---|
|daid_package_name|The name of the aide package to install.|
|daid_conf_path|Path to the aide configuration file|
|daid_conf_name|The name of the aide configuration file|
|daid_db_path|Path to the aide database file|
|daid_db_name|The name of the aide database file|
|daid_new_db_name|The name of a new aide database file|

## Dependencies

None.
## Example Playbook

    - hosts: servers
      roles:
        - glillico.deploy_aide

## License

MIT

## Author Information

Created in 2024 by Graham Lillico.