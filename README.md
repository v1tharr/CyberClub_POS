# CyberClub_POS

POS-приложение для компьютерного клуба

##Предназначение 
Программа изначально разработана в рамках производственной практики для франчайзи - [CyberX](https://cyberxcommunity.ru/clubs/barnaul/cyberx-barnaul.html) 

###Использование
Для корректной работы программы необходимо выполнить следующее:
-  Иметь операционную систему Windows версии 7 и выше
-  Предустановить SQL Server Management Studio

После этого выполните импорт файла script.sql из репозитория в SQL Server Management Studio для работы с построенной архитектурой приложения для работы с базой данных. Заполните данные и после этого установите соединение в Visual Studio как .ADO.
База данных должна функционировать согласно схеме изображенной ниже:
[![Логическая схема](https://telegra.ph/file/3b47f3783cbe65db04d16.png "Логическая схема")](https://telegra.ph/file/3b47f3783cbe65db04d16.png "Логическая схема")

При запуске приложения на главной странице, а также в <abbr title="bin\Release">корневой папке</abbr> можно открыть руководство пользователя где подробно описано как использовать программу.
