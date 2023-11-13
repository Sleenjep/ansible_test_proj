check_for_usb_devices_role работает только с usb-флешками.

Из master-playbook'а запускается роль check_for_usb_devices_role.

Данная роль выполняет следующие дейтсвия:

	1. Роль просит пользователя втавить usb-флешками.
	2. Роль проверяет, что появилось новое usb-устройство и запоминает его.
	3. Роль просит пользователя удалить usb-устройство.
	4. Роль убеждается, что usb-устройство удалено.
	5. Роль просит вернуть usb-устройство.
	6. Роль убеждается, что вставлено то же самое устройство, что было вставлено на шаге 2.
	
Запуск производится из дирректории ansible с помощью команды: ansible-playbook -i hosts master_playbook.yml

Operating System: Ubuntu 22.04.3 LTS              
          Kernel: Linux 6.2.0-36-generic
          
ansible [core 2.15.5]
python version = 3.10.12 (main, Jun 11 2023, 05:26:28) [GCC 11.4.0] (/usr/bin/python3)
jinja version = 3.0.3

  





