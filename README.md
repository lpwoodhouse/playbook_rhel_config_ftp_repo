# Ansible Playbook: rhel_config_ftp_repo
![GitHub last commit](https://img.shields.io/github/last-commit/lpwoodhouse/playbook_rhel_config_ftp_repo)
![GitHub repo file count](https://img.shields.io/github/directory-file-count/lpwoodhouse/playbook_rhel_config_ftp_repo)
![GitHub top language](https://img.shields.io/github/languages/top/lpwoodhouse/playbook_rhel_config_ftp_repo)

## Purpose

Creates a package repository from a RHEL installation .iso and makes the repository accessible to clients via ftp.

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (see ```defaults/main.yml```)
```shell
iso_device: /dev/sr0
```
## Dependencies

None

## Example Playbook
```yaml
    - hosts: localhost
      vars:
        - iso_device: /dev/sr0
      roles:
        - ftp_repo
```

## License

[![GitHub](https://img.shields.io/github/license/lpwoodhouse/playbook_rhel_config_ftp_repo)](LICENSE)

## Author Information

This role was created in 2022 by [Lee Woodhouse](https://www.leewoodhouse.com/)
