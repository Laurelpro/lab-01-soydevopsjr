# Lab 01 — Docker Fundamentals

Stack web con Flask + PostgreSQL orquestado con Docker Compose, desplegado en una VM reproducible con Vagrant.

## Tecnologías
- Docker + Docker Compose
- Python / Flask / Gunicorn
- PostgreSQL 16
- Vagrant + VirtualBox

## Cómo correrlo
```bash
git clone https://github.com/Laurelpro/lab-01-soydevopsjr.git
cd lab-01-soydevopsjr
cp .env.example .env
docker compose up -d --build
curl http://localhost:5000
```

## Lo que aprendí
- Crear entornos reproducibles con Vagrant
- Construir imágenes Docker con Dockerfile
- Orquestar múltiples contenedores con Docker Compose
- Redes, volúmenes y variables de entorno en Docker
