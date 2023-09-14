# ping
Test Ping Ansible Task


```yaml
---
- name: Test Connectivity
  hosts: all
  gather_facts: true
  tasks:
    - name: Test connection with ping
      ansible.builtin.ping:
```
