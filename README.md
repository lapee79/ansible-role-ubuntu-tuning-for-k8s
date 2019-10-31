Ansible Role: Ubuntu tuning for Kubernetes
=========

Configure sysctl settings, PAM limits, SSDs optimizing and GRUB for Ubuntu to deploy Kubernetes.

Role Variables
--------------

see `defaults/main.yml` .

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: ubuntu-servers
  roles:
     - ubuntu-tuning-for-k8s
```

License
-------

BSD

Author Information
------------------

This role was created in 2019 by lapee79 to tune Ubuntu server for Kubernetes.
