# Role: Users
*Creation and removal of user accounts.*

## What
- creation
- removal
- shells
- passwords
- groups
- sudo access
- home directories

## How
### Authorized Keys
```yaml
users:
  - name: shackadmin
    groups:
      - sudo
      - docker
    shell: /bin/bash
    state: present

  - name: olduser
    state: absent
```
