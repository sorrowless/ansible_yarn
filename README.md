sbog/yarn
=========

Role for Ansible to install Yarn Classic (1.x) to target node.

#### Requirements

Ansible 2.4+

#### Role Variables

You can see all vars in [default vars](defaults/main.yml).

#### Dependencies

None

#### Example Playbook

```yaml
- name: Install Yarn
  hosts: all
  remote_user: root

  roles:
    - yarn
```

#### License

Apache 2.0

#### Author Information

Stan Bogatkin (https://sbog.ru)
