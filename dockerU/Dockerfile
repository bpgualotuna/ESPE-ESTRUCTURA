# Usa una imagen base de Ubuntu
FROM ubuntu:20.04

# Instala las dependencias necesarias (puedes modificar según tus necesidades)
RUN apt-get update && apt-get install -y \
    build-essential \
    git \
    python3 \
    python3-pip \
    && rm -rf /var/lib/apt/lists/*

# Crea un directorio de trabajo
WORKDIR /app

# Copia tu código fuente al contenedor (opcional, puedes hacerlo más tarde)
COPY . .

# Exponer un puerto si es necesario (opcional)
EXPOSE 8000

# Comando por defecto (puedes cambiarlo según lo que necesites)
CMD ["bash"]
