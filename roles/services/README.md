# Role: Services
*Management of linux services.*

## How
### Services
```yaml
services:
  - name: ssh
    state: restarted
    enabled: true

  - name: docker
    state: started
    enabled: true

  - name: chrony
    state: stopped
    enabled: false
```
