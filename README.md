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
* Allow user to specify JDK & JRE version (1.6 and 1.7)

## License

This playbook is distributed under the
[Apache 2.0 license](http://www.apache.org/licenses/LICENSE-2.0.html).
