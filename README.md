# ansible-loki

An Ansible role for installing and executing loki that is a scanner of simple indicators of compromise (IoCs).

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
