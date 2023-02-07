### Server Setup

1. Create a python virtual environment.

```zsh
$ python3 -m venv venv
$ source venv/bin/activate
```

2. Install `ansible`

```zsh
$ make config
```

3. Create `hosts.prod` from `hosts` file and replace `127.0.0.1` with the host IP.

4. Create `prod.vault.yml` with these configs.

```zsh
$ ansible-vault create prod.vault.yml
```

```yaml
x: y
```

5. Run ansible playbook to setup the server

```zsh
$ make prod
```
