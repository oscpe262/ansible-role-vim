# Ansible role 'vim'

An Ansible role for setting up vim.

## Requirements
Following distributions are supported:
- Arch Linux
- CentOS 7
- Linux Mint 18
- RHEL 7
- Ubuntu 16.10

## Role Variables
| Variable                       | Default                          | Comments (type)  |
| :---                           | :---                             | :---             |
| as_user | root | User for non-package installs |
| python_version | py3 | Python version for powerline <py/py3> |

## Dependencies
yaourt module (TODO: To be replaced with pacaur and included or linked)

## Example Playbook
```Yaml
- hosts: foo
  roles:
    - { role: vim, as_user: moocow }
```

## Testing

## License

BSD

## Contributors

Issues, feature requests, ideas, suggestions, etc. are appreciated and can be posted in the Issues section. Pull requests are also very welcome. Please create a topic branch for your proposed changes, it's the easiest way to merge back into the project.

- [Oscar Petersson](https://github.com/oscpe262/) (Maintainer)
