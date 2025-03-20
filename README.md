# Proyecto FastAPI con SQLModel y MySQL

Este proyecto es una API REST desarrollada con **FastAPI** y **SQLModel** que permite gestionar héroes en una base de datos MySQL. La API incluye operaciones CRUD (Crear, Leer, Actualizar y Eliminar) para los héroes.

## Requisitos

Antes de comenzar, asegúrate de tener instalados los siguientes requisitos:

- Python 3.10 o superior
- Docker (opcional, si usas MySQL en un contenedor)
- MySQL (local o en Docker)

## Instalación

1. Clona este repositorio:

   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd proyecto_db
2. Crea un entorno virtual e instálalo:
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
pip install -r requirements.txt

3. Configura la base de datos MySQL. Si usas Docker, puedes iniciar un contenedor con el siguiente comando:
docker run --name NOMBRE_CONTENEDOR -e MYSQL_ROOT_PASSWORD=CONTRASEÑA -e MYSQL_DATABASE=NOMBRE_DB -p 3306:3306 -d mysql:latest
Cambia NOMBRE_CONTENEDOR; CONTRASEÑA; NOMBRE_DB; por los datos con los que deseas crear con contenedor. 
