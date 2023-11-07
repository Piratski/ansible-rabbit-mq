## Requiered for install RabbitMQ

1. Add actual rpm package Erlang and RabbitMQ to files dir
2. Change all needs vars in inventory/groups_vars/all.yml
3. Add all your needs hosts to inventory/hosts.inventory

## Command for start playbook from /path/to/repo/ansible-rabbit-mq

```
ansible-playbook -i inventory/hosts.inventory setup_rabbit_MQ.yml
```