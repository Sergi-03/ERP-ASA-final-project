ERP (Enterprise Resource Planning) - ASA Final Project
Descripción
Este es un proyecto colaborativo de desarrollo de un Sistema de Planificación de Recursos Empresariales (ERP), diseñado para gestionar diferentes procesos dentro de una empresa, como la administración de inventarios, ventas, compras, recursos humanos, contabilidad y más.

Este sistema es modular y escalable, con un frontend interactivo desarrollado en React.js y un backend robusto utilizando Flask con PostgreSQL como base de datos.

Características
Gestión de inventarios: Control de productos, proveedores, y niveles de stock.
Gestión de ventas: Registro de órdenes de venta, facturación y reportes.
Gestión de compras: Control de órdenes de compra, proveedores y pagos.
Gestión de recursos humanos: Administración de empleados, sueldos y ausencias.
Contabilidad: Registro de ingresos y egresos, balance de cuentas y reportes financieros.
Tecnologías
Este ERP está desarrollado utilizando las siguientes tecnologías:

Frontend:

React.js: Biblioteca para la construcción de interfaces de usuario dinámicas y reactivas.
Webpack: Herramienta de empaquetado de módulos para aplicaciones frontend.
Backend:

Flask: Micro-framework para el desarrollo de APIs RESTful en Python.
PostgreSQL: Sistema de gestión de bases de datos relacional.
SQLAlchemy: ORM utilizado en Flask para interactuar con la base de datos.
Gestión de dependencias:

Pipenv: Herramienta para la gestión de dependencias y entornos virtuales en Python.
Requisitos
Para ejecutar este proyecto, necesitarás tener instalados los siguientes programas en tu máquina:

Python 3.x: Para ejecutar el backend.
Node.js: Para ejecutar el frontend.
PostgreSQL: Para la base de datos.
Instalación
1. Clonar el repositorio
Clona el repositorio a tu máquina local:

bash
Copiar
git clone https://github.com/Sergi-03/ERP-ASA-final-project.git

2. Instalar dependencias
Accede a la carpeta del proyecto y realiza las siguientes acciones:

Backend (Flask):
Navega a la carpeta del backend:

bash
Copiar
cd backend
Instala las dependencias del backend utilizando pipenv:

bash
Copiar
pipenv install
Inicia el entorno virtual:

bash
Copiar
pipenv shell
Frontend (React):
Navega a la carpeta del frontend:

bash
Copiar
cd frontend
Instala las dependencias del frontend con npm:

bash
Copiar
npm install
3. Configurar la base de datos
Asegúrate de tener PostgreSQL instalado y configurado correctamente. Puedes modificar las configuraciones de la base de datos en los archivos de configuración según sea necesario.

4. Ejecutar el proyecto
Backend (Flask):
Para ejecutar el servidor del backend, dentro de la carpeta del backend, utiliza el siguiente comando:

bash
Copiar
python app.py
Frontend (React):
Para iniciar el servidor de desarrollo de React, dentro de la carpeta del frontend, ejecuta:

bash
Copiar
npm start
El frontend estará disponible en http://localhost:3000 y el backend en http://localhost:5000.

5. Acceder a la aplicación
Una vez que ambos servidores estén en funcionamiento, podrás acceder a la aplicación a través de tu navegador en las siguientes direcciones:

Frontend (React): http://localhost:3000
Backend (Flask API): http://localhost:5000
Contribución
Si deseas contribuir a este proyecto, sigue estos pasos:

Haz un fork de este repositorio.
Crea una rama para tu característica o corrección de error:
bash
Copiar
git checkout -b nombre-de-la-rama
Realiza tus cambios y haz commit de ellos:
bash
Copiar
git commit -m "Descripción de los cambios realizados"
Empuja tus cambios a tu repositorio remoto:
bash
Copiar
git push origin nombre-de-la-rama
Abre un pull request desde tu rama hacia la rama principal del repositorio.

Miembros del equipo
Miembro 1: [Alejandro, Full Stack]
Miembro 2: [Sergi, Full Stack]
Miembro 3: [Álvaro, Full Stack]

