Задание №1

В этом задании имеется данная топология!

![image](https://github.com/slavass15/slavass/assets/40364385/f9630e9a-9090-4e90-aac9-de513b72aaf9)


Что необходимо сделать:

Выполните базовую настройку всех устройств:

• Собрать топологию согласно рисунку. Все устройства работают на OC Linux - Debian
	
• Присвоить имена в соответствии с топологией
	
• Установить и настроить Web-server на NGINX

Все машины будут находится на виртуальном сервере VMware ESXi 

Шаг 1
Первым делом создал машины

![image](https://github.com/slavass15/slavass/assets/40364385/aa21688c-1549-49b6-be32-39db1b577034)

Шаг 2 — Установка Nginx

Сначала обновил локальный индекс пакетов, чтобы отразить последние изменения в исходной версии:
![image](https://github.com/slavass15/slavass/assets/40364385/134d4ecf-8dfe-4de9-a2da-7e0dda12b6e6)

Затем установил nginx пакет:
![image](https://github.com/slavass15/slavass/assets/40364385/5befab17-a4e2-434c-aeb0-9de06cf90c15)

Когда установились пакеты необходимо проверить статус веб-сервера
Чтобы убедиться, что служба работает, набрать:
![image](https://github.com/slavass15/slavass/assets/40364385/dcf37a1e-b88d-475d-9604-18b62cb7314e)
![image](https://github.com/slavass15/slavass/assets/40364385/965d7a83-9538-4c6b-9047-10e77b58d99e)

Этот вывод показывает, что служба запущена успешно. 

Чтобы визуально посмотреть веб-страницу необходимо в адресной строке написать IP-адрес сервера
![image](https://github.com/slavass15/slavass/assets/40364385/9800a1c9-a01f-47da-a9e2-4aeef626b4f3)


Задание №2
![image](https://github.com/slavass15/slavass/assets/40364385/45ac90dc-81f9-464f-a0cb-fade3d0e8559)



