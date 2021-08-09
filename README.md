# ansible-loki

An Ansible role for installing and executing loki that is a scanner of simple indicators of compromise (IoCs).

  ┌────────────────────────┐
  │ Get The Latest Release │
  │    of Loki Zip File    │
  └────────────┬───────────┘
               │
     ┌─────────▼─────────┐
     │ Extract The Files │
     │ From The Zip File │
     └─────────┬─────────┘
               │
      ┌────────▼───────┐
      │      Run       │
      │loki-upgrade.exe│
      └────────┬───────┘
               │
          ┌────▼───┐
          │  Run   │
          │loki.exe│
          └────────┘

## OS Platforms

This role has been tested on the following operating systems:

- Windows Server 2019

## Usage

To use this role in your playbook, add the code below:

```
- name: Install Loki
  import_role:
    name: ansible-loki
```

## License

[MIT](LICENSE)
