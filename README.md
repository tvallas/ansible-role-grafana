Ansible role grafana
=========

Installs grafana

Requirements
------------

None

Role Variables
--------------

#### `grafana_repo_baseurl` (optional)
Grafana repo url

#### `grafana_repo_gpgkey` (optional)
Grafana repo gpgkey

#### `grafana_repo_sslcacert` (optional)
Path to the directory containing the databases of the certificate authorities yum should use to verify SSL certificates.

#### `grafana_packages` (optional)
Required packages for grafana.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: grafana, tags: grafana }

License
-------

MIT

Author Information
------------------

Tuomas Vallaskangas
