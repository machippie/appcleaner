
## Default Variables

### appcleaner_started

Restart app if already running

#### Default value

```yaml
appcleaner_started: false
```

### appcleaner_user

User to run user-specific commands

#### Default value

```yaml
appcleaner_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
