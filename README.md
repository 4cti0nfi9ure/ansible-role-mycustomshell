# ansible-role-mycustomshell
Ansible role for installing and configuring:
* zsh
* oh-my-zsh
* zsh-autosuggestions
* zsh-syntax-highlighting

# Requirements
Tested on Ubuntu 20.04.

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
```
