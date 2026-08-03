# Role: Firewall
*Configuration of the UFW firewall.*

## How
### Firewall Rules
```yaml
firewall_rules:
  - port: 22
    protocol: tcp
  - port: 80
    protocol: tcp
```
