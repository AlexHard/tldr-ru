# ping

> Отправить ICMP ECHO_REQUEST удаленному хосту.

- Пингануть удаленный хост:

`ping {{host}}`

- Пингануть удаленный хост, отправив определенное количество ICMP пакетов:

`ping -c {{count}} {{host}}`

- Пингануть удаленнй хост, указав время между запросами (по умолчанию 1 секунда):

`ping -i {{seconds}} {{host}}`

- Пингануть удаленнй хост, не пытаясь искать символические имена его адресов:

`ping -n {{host}}`

- Пингануть удаленнй хост и услышать звонок при получении пакета (если ваш терминал поддерживает это):

`ping -a {{host}}`
