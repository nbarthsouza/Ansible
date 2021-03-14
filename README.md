Laboratório Ansible
-------------------

Objetivo é criar para estudos, um ambiente com 2 máquinas, uma com Apache + PHP + Wordpress, e a outra com um banco de dados MySQL.
Mas antes vamos entender algumas coisas sobre Ansible.

O que é Ansible?
-----------------
Ansible é uma poderosa ferramenta para automação de configuração de servidores.

Definições
--------------
Playbook: Um playbook é composto por um conjunto de plays.
Tasks: As operações a serem executadas chamando os módulos e passando as opções necessárias.
Roles: permitem que você carregue automaticamente tasks, handlers, e outros.

Nota:
Todo o projeto já foi estruturado com roles, para permitir a reutilização dos playbooks em outros servidores.

