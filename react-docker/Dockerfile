FROM node:20-alphine



RUN addgroup app && adduser -S -G app app


USER app

WORKDIR /app

COPY package*.json ./