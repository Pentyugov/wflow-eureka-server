### Wflow server app

##### Стэк: Spring boot, Eureka Server

_____

### Introduction
Данное приложение Eureka сервером для регистриции Eureka клиентов приложения Wflow-App

Основная серверная часть:

      https://github.com/Pentyugov/wflow

Клиентская часть:

      https://github.com/Pentyugov/zolloz-client-mat

Telegram bot для оповещения пользователя о назначенных и просроченных задачах:

      https://github.com/Pentyugov/wflow-app-bot

____

### Запуск

    mvn clean package

    java - jar ./target/wflow.jar

После запуска приложение запускается на порту 8761 и ожидает регистрации клиентов

Данные о состоянии сервера доступны по ссылке 

      http://localhost:8761