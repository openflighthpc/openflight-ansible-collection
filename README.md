# Overview

An ansible [collection](https://docs.ansible.com/ansible/latest/collections_guide/collections_using_playbooks.html#using-collections-in-playbooks) providing generic HPC roles utilised by OpenFlight ansible playbooks. 

## Install

To install the latest stable version, run the following:
```bash
ansible-galaxy collection install git+https://github.com/openflighthpc/openflight-ansible-collection.git#/openflight/
```

## Using

Once installed, playbooks can utilise the roles directly from the playbook launch file (e.g. `main.yml`) by specifying the roles with the appropriate collection namespace. For example, specifying `openflight.generic.flightweb` will include the `flightweb` role in the playbook.

