## OTUS Administrator Linux. Professional ДЗ №24: LDAP. Централизованная авторизация и аутентификация 

**Задание**

Для выполнения домашнего задания используйте методичку
https://docs.google.com/document/d/1HoZBcvitZ4A9t-y6sbLEbzKmf4CWvb39/edit?usp=share_link&ouid=104106368295333385634&rtpof=true&sd=true

1. Установить FreeIPA;
2. Написать Ansible playbook для конфигурации клиента;
3. (\*) Настроить аутентификацию по SSH-ключам
4. (\*) Firewall должен быть включен на сервере и на клиенте

Формат сдачи: Vagrantfile + ansible

**_Решение_**

Провижн сделан при помощи vagrant+ansible. 

FreeIPA поднят. Создан пользователь otustest. Firewalld включён. 


Поднимать стенд командой vagrant up, затем ansible-playbook playbook.yml