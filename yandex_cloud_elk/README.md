# Ansible Collection - my_own_collection

## Modules

- [my_own_module.py](https://github.com/Serg2211/my_own_collection/blob/main/yandex_cloud_elk/plugins/modules/my_own_module.py) - Модуль, уоторый оздаёт файл с определенным содержимым

## Roles

- [single_task_role](https://github.com/Serg2211/my_own_collection/blob/main/yandex_cloud_elk/roles/single_task_role/) - Роль, в которой включен модуль создания файла. Содержимое файла можно настроить в [tasks](https://github.com/Serg2211/my_own_collection/blob/main/yandex_cloud_elk/roles/single_task_role/tasks/main.yml)

## Playbooks

- [site.yml](https://github.com/Serg2211/my_own_collection/blob/main/yandex_cloud_elk/site.yml) - Playbook для роли single_task_role
