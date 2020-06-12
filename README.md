# Ansible Playbook DirectAdmin for EzyAdmin Connectors

## Configuration

| key                | description                                     |
| ------------------ | ------------------------------------------------|
| ez_connector       | connector module name                           |
| ez_config          | Array of object congig                          |
|                    | [{                                              |
|                    |     "cmd" : "***{{ command_line }}***"          |
|                    |     "regex" : "***{{ regular expression }}***"  |
|                    | }]                                              |