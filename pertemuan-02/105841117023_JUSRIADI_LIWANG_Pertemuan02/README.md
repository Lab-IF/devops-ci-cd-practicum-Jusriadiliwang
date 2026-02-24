# 🐳 Task 3 - Docker Compose Multi-Container

## 🎯 Tujuan
Menjalankan beberapa container sekaligus menggunakan Docker Compose.

## 🧱 Services yang Digunakan

| Service | Image | Port |
|----------|--------|------|
| web | nginx:alpine | 8083 |
| api | httpd:alpine | 8084 |
| db | postgres:15-alpine | 5432 |

## 🚀 Perintah Menjalankan

```bash
docker compose up -d