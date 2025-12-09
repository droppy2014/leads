# CORS заголовки для набора доменов

Запуск: docker compose up

В соседнем терминале для проверки запустить: 

curl -I http://localhost:8080/

или

curl -H "Origin: https://leads.su" -I http://localhost:8080/