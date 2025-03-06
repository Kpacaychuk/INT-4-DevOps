# INT-4-DevOps-Ansible
Готовый сценарий для разворачивания PostgreSQL-16 на свежеустановленном Debian 11 с SSH-сервером.   
Перед запуском сценария необходимо файле в vault.yaml в качестве пароля указать пароль от root на Debian 11.  
Так как Debian свежеустановленный, то запускать сценарий нужно с указанием имени обычного пользователя, который был создан во время установки ОС, например:  
ansible-playbook playbook.yaml -u amirkhan -k - если подключение ssh не по ключам или   
ansible-playbook playbook.yaml -u amirkhan - если подключение ssh с использованием кючей.  

Отчет о выполнении задания: https://amirkhan.yonote.ru/share/INT-4-Ansible
