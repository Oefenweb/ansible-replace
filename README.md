## replace

[![CI](https://github.com/Oefenweb/ansible-replace/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-replace/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-replace-blue.svg)](https://galaxy.ansible.com/Oefenweb/replace)

Set up (the latest version of) [replace](https://replace.richardlloyd.org.uk/) in Debian-like systems.

#### Requirements

* `build-essential` (will be installed)

#### Variables

* `replace_version`: [default: `1.7.4.2`]: Version to install

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.replace
```

#### License

MIT

#### Author Information

* Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-replace/issues)!
