# Overview

An ansible [collection]() providing generic HPC roles utilised by OpenFlight ansible playbooks. 

## Install

To install the latest stable version, run the following:
```bash
ansible-galaxy collection install git+https://github.com/openflighthpc/openflight-ansible-collection.git#/openflight/
```

## Using

Once installed, playbooks can utilise the roles directly from the playbook launch file (e.g. `main.yml`) by specifying the roles with the appropriate collection namespace. For example, specifying `openflight.generic.flightweb` will include the `flightweb` role in the playbook.

## Testing 

- Can easily override default vars? (ideally through placing a file somewhere in the playbook) 
- Can better mix and match various server types?
