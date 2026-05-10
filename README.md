# Simple Web App — Генератор цитат

Простое веб-приложение на Flask, которое показывает случайные цитаты о программировании.

## Запуск через Docker

```bash
docker build -t quotes-app .
docker run -p 5000:5000 quotes-app
