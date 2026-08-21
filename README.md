# Docker-Prueba

Proyecto de prueba para aprender Docker.

## Contenido

- `Dockerfile`: crea una imagen basada en Nginx Alpine.
- `index.html`: página web servida por el contenedor.

## Construir la imagen

```bash
docker build -t docker-prueba .
```

## Ejecutar el contenedor

```bash
docker run -d -p 8080:80 --name docker-prueba-container docker-prueba
```

## Abrir en el navegador

http://localhost:8080