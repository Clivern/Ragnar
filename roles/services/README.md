### Core Services Ansible Role

This role installs Docker. Available configs to override:

```yaml
# MySQL configs
mysql_root_password: "root"
mysql_database: "d_ropen"
mysql_user: "u_ropen"
mysql_password: "m06rs011e9h9ihuboi7s"

# Redis password
redis_password: "mystery"

# Ivar backup configs
s3_access_key_id: "XXXX"
s3_secret_access_key: "YYYY"
s3_bucket: "ropen"
s3_region: "us-east-1"
s3_endpoint: "https://ropen.ams3.digitaloceanspaces.com"
schedule: "*/10 * * * *"
mysqldump_extra_options: "--skip-ssl --no-tablespaces"

# RabbitMQ Credentials
rabbitmq_default_user: "guest"
rabbitmq_default_pass: "1bltngynndsa5ucdq682"
```
