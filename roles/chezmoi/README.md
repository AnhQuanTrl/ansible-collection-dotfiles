# Ansible Role: chezmoi

Manage installation of Chezmoi (dotfiles manager).

## Requirements

This role requires a package manager to install `chezmoi` based on the managed node's OS distribution.

## Role Variables

```
chezmoi_user: ""
chezmoi_repo: ""
chezmoi_homedir: ""
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
