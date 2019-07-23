# Brave Browser

This role handles configuring the Brave Browser repository and then install
Brave Browser.

## Requirements

The hosts you are targeting should have the following packages:

- python >= 2.6
- python-dnf

## Role Variables

None

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers
  roles:
    - role: jaredhocutt.brave_browser
```

## License

MIT

## Author Information

Jared Hocutt (@jaredhocutt)
