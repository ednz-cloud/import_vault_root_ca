Import Vault root CA
=========
> This repository is only a mirror. Development and testing is done on a private gitlab server.

This role imports root CA certificates from Vault to the trust store on **debian-based** distributions.

Requirements
------------

None.

Role Variables
--------------
Available variables are listed below, along with default values. A sample file for the default values is available in `default/hashicorp_nomad.yml.sample` in case you need it for any `group_vars` or `host_vars` configuration.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
# calling the role inside a playbook with either the default or group_vars/host_vars
- hosts: servers
  roles:
    - ednxzu.import_vault_root_ca
```

License
-------

MIT / BSD

Author Information
------------------

This role was created by Bertrand Lanson in 2023.
