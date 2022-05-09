# ansible-role-jira
This Ansible role installs and configures Atlassian Jira (Official website: https://www.atlassian.com/jira).

## Prerequisites

* Java 8
* Postgresql 12

## SystemD variables

You can add Environment variables to the systemd daemon like this:

    jira_env_vars:
      - key: 'HTTP_PROXY'
        value: 'http://company.com:3128'
      - key: 'NO_PROXY'
        value: 'localhost'

## License

MIT

## Author Information

This role was created in 2022 by Olivier Locard on the behalf of Deveryware.
  
