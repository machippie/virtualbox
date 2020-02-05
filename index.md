
## Default Variables

### virtualbox_machines

#### Default value

```yaml
virtualbox_machines: []
```

### virtualbox_user

User to run user-specific commands

#### Default value

```yaml
virtualbox_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
