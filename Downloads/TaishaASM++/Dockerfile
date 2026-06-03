FROM ubuntu:24.04

# Обновляем пакетный менеджер и устанавливаем инструменты сборки
RUN apt-get update && apt-get install -y \
    build-essential \
    gcc-multilib \
    nasm \
    && rm -rf /var/lib/apt/lists/*

# Указываем рабочую директорию внутри контейнера
WORKDIR /app