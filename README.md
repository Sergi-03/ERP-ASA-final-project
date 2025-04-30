# ERP-ASA Final Project

Este es un proyecto colaborativo de desarrollo de un Sistema de Planificación de Recursos Empresariales (ERP), diseñado para gestionar diferentes procesos dentro de una empresa, como la administración de inventarios, ventas, compras, recursos humanos, contabilidad y más.

## Características

- **Gestión de inventarios**: Control de productos, proveedores y niveles de stock.
- **Gestión de ventas**: Registro de órdenes de venta, facturación y reportes.
- **Gestión de compras**: Control de órdenes de compra, proveedores y pagos.
- **Gestión de recursos humanos**: Administración de empleados, sueldos y ausencias.
- **Contabilidad**: Registro de ingresos y egresos, balance de cuentas y reportes financieros.

## Tecnologías

Este ERP está desarrollado utilizando las siguientes tecnologías:

- **Frontend**:
  <img width="1280" alt="Captura de pantalla 2025-04-30 a las 14 06 46" src="https://github.com/user-attachments/assets/e9cc0396-11e2-450e-9633-7d17e91694ee" />
  <img width="1280" alt="Captura de pantalla 2025-04-30 a las 14 12 27" src="https://github.com/user-attachments/assets/48392cc5-9103-408b-980f-1dfe20ca4bdd" />
  <img width="1280" alt="Captura de pantalla 2025-04-30 a las 14 12 10" src="https://github.com/user-attachments/assets/7930be67-ac64-4585-825a-b6326c02a74b" />
  <img width="1280" alt="Captura de pantalla 2025-04-30 a las 14 06 50" src="https://github.com/user-attachments/assets/64494211-567f-4f2f-abb0-4bc89bc7e645" />


  - React.js: Biblioteca para la construcción de interfaces de usuario dinámicas y reactivas.
  - Webpack: Herramienta de empaquetado de módulos para aplicaciones frontend.

- **Backend**:
  <img width="1280" alt="Captura de pantalla 2025-04-30 a las 14 11 15" src="https://github.com/user-attachments/assets/4145a605-d640-4766-a373-cee3522610e3" />
  <img width="1280" alt="Captura de pantalla 2025-04-30 a las 14 07 49" src="https://github.com/user-attachments/assets/c86c5c79-543a-4e68-9f9b-a454e05ae625" />


  - Flask: Micro-framework para el desarrollo de APIs RESTful en Python.
  - PostgreSQL: Sistema de gestión de bases de datos relacional.
  - SQLAlchemy: ORM utilizado en Flask para interactuar con la base de datos.

- **Gestión de dependencias**:
  - Pipenv: Herramienta para la gestión de dependencias y entornos virtuales en Python.

## Uso

### 1. Clonar el repositorio
```bash
git clone https://github.com/Sergi-03/ERP-ASA-final-project.git
cd ERP-ASA-final-project
```

### 2. Configurar el entorno virtual y dependencias
```bash
pipenv install
pipenv shell
```
### 3. Configura la base de datos
```bash
flask db init
flask db migrate -m "Initial migration."
flask db upgrade
```

### 4. Ejecutar el backend
```bash
flask run
```

### 5. Iniciar el frontend
```bash
cd frontend
npm install
npm start
```

## Colaboradores

- [Alejandro](https://github.com/AlejandroGC19)
- [Sergi](https://github.com/Sergi-03)
- [Álvaro](https://github.com/RGAlvaro)

## Contacto

Si tienes preguntas o comentarios, no dudes en contactarme en: [ssegarragarcia@gmail.com]
