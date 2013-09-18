# Ansible Apache Cassandra playbook

This is an Ansible playbook for deploying Apache Cassandra 2.0.

This playbook was tested on Ubuntu 12.04 x86_64.

## Requirements

This playbook requires Ansible 1.2 or higher.

## group_vars

Variables which can be configured are located in the `group_vars/all` file.

## Running playbook

```bash
ansible-playbook -i ansible.host setup.yml
```

## TODO

* Support multiple node deployments
* Parameterize more cassandra.yaml options
* Support older Cassandra versions (1.1 and 1.2)
* Allow user to specify JDK & JRE version (1.6 and 1.7)

## License

Apache 2.0.
