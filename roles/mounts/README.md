# Role: Mounts
*Handles permanent filesystem mounts via /etc/fstab.*

## How
### Mounts
```yaml
mounts:
  - path: /mnt/media
    src: 10.0.0.20:/media
    fstype: nfs
    opts: rw,nfsvers=4
```
