# Configure EPEL

Sets up EPEL on RHEL and its clones (Rocky, Alma etc). Does nothing on Fedora.

## Example dependency

```yml
dependencies:
  - name: cosandr.epel
    src: https://github.com/cosandr/ansible-role-epel.git
    scm: git
    version: v1.0.0
```

## Example Playbook

```yml
    - hosts: servers
      roles:
         - role: cosandr.epel
```

## License

MIT

## Author Information

Andrei Costescu
