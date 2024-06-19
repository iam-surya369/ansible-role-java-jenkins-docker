# java_jenkins_docker_setup

Ansible role to install Java, Jenkins, and Docker on Ubuntu machines.

## Role Variables

- `java_version`: Specifies the Java version to be installed. Default value is `openjdk-17-jdk`.

## Requirements

Before running this playbook, ensure that you have the following prerequisites:

- Ubuntu instances created on AWS EC2.

## Dependencies

No dependencies on other roles.

## Example Playbook

```yaml
- name: Install Java, Jenkins and Docker on ubuntu machines
  hosts: all
  become: true
  roles:
    - java_jenkins_docker_setup
```

License
MIT

Author Information
Author: Surya
Company: YourCompany
