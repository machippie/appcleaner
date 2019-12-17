
## Default Variables

### appcleaner_automatically_update

Automatically update

#### Default value

```yaml
appcleaner_automatically_update: true
```

### appcleaner_enable_automatic_check

Enable automatic checks

#### Default value

```yaml
appcleaner_enable_automatic_check: true
```

### appcleaner_protect_opened_apps

Protect opened apps

#### Default value

```yaml
appcleaner_protect_opened_apps: false
```

### appcleaner_started

Start in background after install

#### Default value

```yaml
appcleaner_started: true
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
