### Alloy Ansible Role

This role installs Alloy. Available configs to override:

```yaml
alloy_version: 1.5.1

remote_loki_write_url: http://X.X.X.X:3100/loki/api/v1/push
remote_loki_username: admin
remote_loki_password: password

remote_prometheus_write_url: http://X.X.X.X:9090/api/v1/write
remote_prometheus_username: admin
remote_prometheus_password: password

alloy_hostname: ropen01_host
```
