# Default shell

Ansible role to change the default shell for a given user

## Role Variables

Stored in defaults folder

### user

Default value "{{ ansible\_user }}"
The name of the user to change it's default shell

### new\_shell

Default value /usr/bin/zsh
The the shell to set by default for the {{ user }}.

## Howto use this role

This role needs to be included in a playbook
You can install it with *Galaxy*

```bash
ansible-galaxy install -r requirements.yml
```

requirements.yml
```
- src: probakilla.default_shell
```

# Requirements

- Ansible 2.4+
