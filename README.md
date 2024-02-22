Containers - Monitoring
=========

* WIP 

Configure Grafana, Loki, Prometheus, and Alertmanager. 

Requirements
------------

The following should have already been applied. 

planetmikeorg.baseline_linux
planetmikeorg.containers_host

Role Variables
--------------

See defaults/main.yml, vars/main.yml.

Dependencies
------------



Example Playbook
----------------

  - name: Configure Monitoring
    hosts: all
    become: true
    roles:
      - planetmikeorg.containers_monitoring

License
-------

BSD

Author Information
------------------

Michael Cleary
planetmike.org
