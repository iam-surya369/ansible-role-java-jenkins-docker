# java_jenkins_docker_setup

Thsi role installs Java, Jenkins, and Docker on Ubuntu machines.

## Role Variables

- `java_version`: Specifies the Java version to be installed. Default value is `openjdk-17-jdk`.

## Requirements

Before running this playbook, ensure that you have the following prerequisites:

- Ubuntu instances created on AWS EC2.

## Tested Ubuntu Versions

This role has been tested on the following Ubuntu versions:

- Ubuntu 22.04 LTS (Jammy Jellyfish)
- Ubuntu 24.04 LTS (Noble Numbat)

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

## License

MIT

## Author Information

Author: Surya