# Ollama Docker

Este proyecto utiliza Docker Compose para configurar y ejecutar un contenedor con el modelo Llama2.

## Requisitos

- Docker
- Docker Compose

## Instrucciones

1. Clona este repositorio:

    ```bash
    git clone https://github.com/nanyhel/ollama_docker.git
    cd ollama_docker
    ```

2. Construye y levanta los servicios con Docker Compose:

    ```bash
    docker-compose up -d
    ```

3. Descarga el modelo Llama2 dentro del contenedor:

    ```bash
    docker exec -it ollama ollama run llama2
    ```

## Recursos adicionales

- [Ollama con Docker](https://ollama.com/blog/ollama-is-now-available-as-an-official-docker-image)
- [OpenWebUI](https://openwebui.com)

## Autores ✒️

* **Moisés Jiménez** - *Trabajo Inicial* - [nanyhel](https://github.com/nanyhel)

---
⌨️ con ❤️ por [nanyhel](https://github.com/nanyhel) 😊