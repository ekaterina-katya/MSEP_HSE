mkdir web-app #создание каталога
ls #содержимое 
cd web-app #перейти в другой каталог
mkdir app config logs backup scripts
ls
touch app/main.py config/app.conf logs/application.log scripts/start.sh README.md #создать файлы
nano config/app.conf #текстовый редактор

APP_NAME=web-app 
APP_VERSION=1.0 
HOST=0.0.0.0 
PORT=8080 
LOG_LEVEL=INFO 
DEBUG=false 
DATABASE_HOST=localhost 
DATABASE_PORT=5432

cat config/app.conf #вывести содержимое файла
nano README.md 

WEB APPLICATION 

Application: web-app 
Version: 1.0 
Port: 8080 

Configuration: 
config/app.conf 

Logs: 
logs/application.log 

Start script: 
scripts/start.sh

cat README.md

nano app/main.py

print("Web Application") 
print("Version: 1.0") 
print("Application started")

python3 main.py
cd ..
nano scripts/start.sh

%

./scripts/start.sh

#zsh: permission denied: ./scripts/start.sh

chmod +x ./scripts/start.sh #права доступа
./scripts/start.sh

#./scripts/start.sh: line 1: fg: no job control

cd ..
nano logs/application.log

'2026-09-22 10:00:01 INFO APPLICATION Application started' 
'2026-09-22 10:00:02 INFO DATABASE Connection established' 
'2026-09-22 10:01:15 INFO API GET /users 200' 
'2026-09-22 10:02:21 INFO AUTH User admin authenticated' 
'2026-09-22 10:03:11 WARNING API Response time 1800ms' 
'2026-09-22 10:04:05 INFO API GET /products 200' 
'2026-09-22 10:05:14 ERROR DATABASE Connection timeout' 
'2026-09-22 10:05:15 WARNING DATABASE Reconnecting' 
'2026-09-22 10:05:18 INFO DATABASE Connection established' 
'2026-09-22 10:06:44 ERROR AUTH Invalid token' 
'2026-09-22 10:07:11 INFO API POST /orders 201' 
'2026-09-22 10:08:17 WARNING API Response time 2200ms' 
'2026-09-22 10:09:31 ERROR DATABASE Query timeout' 
'2026-09-22 10:10:04 INFO AUTH User operator authenticated' 
'2026-09-22 10:11:42 ERROR API Internal server error'
mkdir web-app #создание каталога
ls #содержимое 
cd web-app #перейти в другой каталог
mkdir app config logs backup scripts
ls
touch app/main.py config/app.conf logs/application.log scripts/start.sh README.md #создать файлы
nano config/app.conf #текстовый редактор

APP_NAME=web-app 
APP_VERSION=1.0 
HOST=0.0.0.0 
PORT=8080 
LOG_LEVEL=INFO 
DEBUG=false 
DATABASE_HOST=localhost 
DATABASE_PORT=5432

cat config/app.conf #вывести содержимое файла
nano README.md 

WEB APPLICATION 

Application: web-app 
Version: 1.0 
Port: 8080 

Configuration: 
config/app.conf 

Logs: 
logs/application.log 

Start script: 
scripts/start.sh

cat README.md

nano app/main.py

print("Web Application") 
print("Version: 1.0") 
print("Application started")

python3 main.py
cd ..
nano scripts/start.sh

%

./scripts/start.sh

#zsh: permission denied: ./scripts/start.sh

chmod +x ./scripts/start.sh #права доступа
./scripts/start.sh

#./scripts/start.sh: line 1: fg: no job control

cd ..
nano logs/application.log

'2026-09-22 10:00:01 INFO APPLICATION Application started' 
'2026-09-22 10:00:02 INFO DATABASE Connection established' 
'2026-09-22 10:01:15 INFO API GET /users 200' 
'2026-09-22 10:02:21 INFO AUTH User admin authenticated' 
'2026-09-22 10:03:11 WARNING API Response time 1800ms' 
'2026-09-22 10:04:05 INFO API GET /products 200' 
'2026-09-22 10:05:14 ERROR DATABASE Connection timeout' 
'2026-09-22 10:05:15 WARNING DATABASE Reconnecting' 
'2026-09-22 10:05:18 INFO DATABASE Connection established' 
'2026-09-22 10:06:44 ERROR AUTH Invalid token' 
'2026-09-22 10:07:11 INFO API POST /orders 201' 
'2026-09-22 10:08:17 WARNING API Response time 2200ms' 
'2026-09-22 10:09:31 ERROR DATABASE Query timeout' 
'2026-09-22 10:10:04 INFO AUTH User operator authenticated' 
'2026-09-22 10:11:42 ERROR API Internal server error'

