andrewrothstein.influxdb-cluster
=========

Configures an [InfluxDB](https://docs.influxdata.com/influxdb) cluster

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

inventory.ini
```ini
[influxdb]
host1
host2
...
```

```yml
- hosts: influxdb
  roles:
    - andrewrothstein.influxdb-cluster
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
