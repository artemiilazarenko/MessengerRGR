# MessengerRGR
Установить MySQL и MySQL Workbench
Создать базу данных Messenger в коннекторе CREATE DATABASE Messenger;
В проекте в файле application.properties в строчках 
spring.datasource.url=jdbc:mysql://${MYSQL_HOST:localhost}:3307/Messenger?useUnicode=true&useJDBCCompliantTimezoneShift=true&useLegacyDatetimeCode=false&serverTimezone=UTC
указать хост коннектора ${MYSQL_HOST:localhost}:3307
и в строке spring.datasource.password=1234 указать пароль от своего коннектора
