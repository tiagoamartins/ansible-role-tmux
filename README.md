# Ansible Role: tmux

Ansible role that installs [tmux](https://github.com/tmux/tmux)

## Requirements

The following executables are required for installing tmux's `terminfo`:

- `gunzip` (part of `gzip` package)

- `tic` (part of `ncurses` package)

## Role Variables

Available variables are listed below:

- `tmux_packages`: List of packages necessary to install tmux.

## Use with Ansible

```yaml
- hosts: all

  roles:
    - tmux
```

## Dependencies

None.

## Author Information

This role was created in 2022 by Tiago Martins.
