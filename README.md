# Ansible Role Go

Library of Ansible plugins and roles for deploying various services.
See [ansible-roles](https://github.com/davidfischer-ch/ansible-roles) for additional documentation.

This repository hosts the role go and may depend of other roles and plugins of the library.

## Dependencies

See [meta](meta/main.yml).

## Variables

TODO VARIABLES

## Example

### Playbook

```
---

- hosts: localhost
  roles:
    - go
  vars:
    go_version: 1.14.2
    go_release_checksum: 6272d6e940ecb71ea5636ddb5fab3933e087c1356173c61f4a803895e947ebb3
```

## License

See [LICENSE.rst](LICENSE.rst).

## Authors

See [AUTHORS](AUTHORS).

2014-2020 - David Fischer
