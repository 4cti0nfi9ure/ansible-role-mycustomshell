# ansible-role-mycustomshell
Ansible role for installing and configuring:
* zsh
* oh-my-zsh
* zsh-autosuggestions
* zsh-syntax-highlighting
* fzf

# Requirements
Tested on Ubuntu 18.04 and 20.04.
Ansible 2.9, git

# Configuration
```
- hosts: localhost
  roles:
          - ansible-role-mycustomshell
```

# Defaults
```
zsh_theme: robbyrussell
user_name: ubuntu
zsh_plugins:
        - git
        - zsh-autosuggestions
        - zsh-syntax-highlighting
        - fzf
```
