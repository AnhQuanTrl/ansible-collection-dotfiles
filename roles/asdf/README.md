# Ansible Role: asdf

Manage plugins configuration of `asdf`.

## Requirements

This role requires `asdf` to be installed beforehand.

## Role Variables

```
asdf_plugins:
  - name: "erlang"    # a plugin name
    repository: ""    # a plugin repository, optional
    versions:         # a list of versions to install
      - 18.3
      - 20.1
    global: 20.1      # set as a global version, optional
asdf_user: ""
```

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

## License

MIT

## Author Information

[AnhQuanTrl](https://github.com/AnhQuanTrl)
