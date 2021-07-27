# Web Server

A test Ansible role to install Apache and allow Molecule testing

## Testing

| Main Branch | Dev Branch |
|:------------|:-----------|
| [![CI](https://github.com/rosskouk/molecule-test/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/rosskouk/Ansible-Role-Web-Server/actions) | ![CI](https://github.com/rosskouk/molecule-test/actions/workflows/ci.yml/badge.svg?branch=dev) |

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```
    - hosts: servers
      roles:
         - { role: web_server }
```

## License

MIT

## Author Information

Ross Stewart
