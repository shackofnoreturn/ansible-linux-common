# Role: Sysctl
*Generic kernel parameter management.*

## What
- Docker
- Kubernetes
- networking
- security tuning

## How
### Sysctl Settings
```yaml
sysctl_settings:
  net.ipv4.ip_forward: 1
  vm.swappiness: 10
```
