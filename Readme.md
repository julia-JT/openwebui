
Запуск:
Docker-compose up -d
Проверка что контейнеры в статусе Up
Docker ps -a

Далее загрузка и установка модели в этих контейнерах:
docker exec -it ollama ollama pull qwen2.5-coder:3b
