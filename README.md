# ansible-role-restic-rest

Deploy [rest-server for restic](https://github.com/restic/rest-server).

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

BSD [![License](https://raw.githubusercontent.com/donat-b/ansible-restic-rest/master/.github/license.svg?sanitize=true)](https://github.com/donat-b/ansible-restic-rest/blob/master/LICENSE)
