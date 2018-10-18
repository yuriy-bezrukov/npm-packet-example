ReadmE


- Это делать не надо, уже готово

npm adduser --registry  http://192.168.51.79:1234

login

password

bezrukov@mir-omsk.ru

- Остальное делаем 



-Добавляем локальный репозиторий 

npm --registry  http://192.168.51.79:1234


- Логинимся

npm login

password

bezrukov@mir-omsk.ru



- Проверяем, что мы под пользователем "login"

npm whoami


- Публикуем пакет (rootProjectFolder - это папка с минимум тремя файлами index.js \ package.json \ README.md)

cd /rootProjectFolder

npm publish


- Обновляем пакет. Обновляем версию в package.json, выполняем команду 

cd /rootProjectFolder

npm publish


- Пакет на локальном сервере, можно перейти на сайт и посмотреть 
