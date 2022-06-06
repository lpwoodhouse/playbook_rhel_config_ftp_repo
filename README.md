# Ansible Role: rh_ftp_repo

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
        - rh_ftp_repo
```

## License

MIT

## Author Information

This role was created in 2022 by [Lee Woodhouse](https://www.leewoodhouse.com/)
