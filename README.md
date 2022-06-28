# ansible-role-restic-rest

Deploy [rest-server](https://github.com/restic/rest-server) for restic.

## Requirements

None

## Role Variables

```yaml
restic_rest_args_path: "/mnt/Backups"
restic_rest_version: "0.11.0"
restic_rest_accounts:
  - name: admin
    password: Chang3Me
```

## License

[![GitHub](https://img.shields.io/github/license/itsnotgoodname/ansible-role-restic-rest)](./LICENSE)
