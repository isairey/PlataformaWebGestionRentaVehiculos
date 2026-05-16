<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/744/744465.png" />

# 🚗 Vehicle Management System

### Plataforma web de gestión y renta de vehículos 🚀

<p align="center">
  <b>Vehicle Management System</b> es un sistema web desarrollado como proyecto académico para la materia de DBMS, orientado a la administración y renta de vehículos mediante una plataforma moderna y centralizada.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/VehicleManagement-CarRentalSystem-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/DBMS-AcademicProject-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/PHP-MySQL-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-WebApplication-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Vehicle Management System** es un sistema web enfocado en la administración de vehículos y reservas de automóviles, desarrollado como proyecto académico para la materia de Sistemas de Gestión de Bases de Datos (DBMS).

La plataforma permite gestionar vehículos, clientes, reservas y operaciones administrativas desde una interfaz intuitiva y organizada.

El sistema fue diseñado para:

- 🚗 Gestionar vehículos
- 👥 Administrar clientes
- 📅 Controlar reservas
- 💳 Gestionar pagos
- 📋 Supervisar alquileres
- 📊 Visualizar reportes
- 🔐 Gestionar accesos
- 🌐 Automatizar operaciones

---

# ✨ Características

## 🚘 Gestión de vehículos

- 🚗 Registro de automóviles
- 📍 Gestión de disponibilidad
- 🖼️ Administración de imágenes
- 💰 Configuración de tarifas
- 📋 Información detallada

---

## 👥 Gestión de usuarios

- 👤 Registro de clientes
- 🔐 Inicio de sesión
- 📄 Gestión de perfiles
- ⚡ Administración centralizada
- 📊 Historial de reservas

---

## 📅 Sistema de reservas

- 📆 Reservas en línea
- 📋 Gestión de contratos
- 💳 Administración de pagos
- ⚡ Confirmaciones rápidas
- 📄 Historial de alquileres

---

## 📊 Panel administrativo

- 📈 Dashboard administrativo
- 🚗 Gestión vehicular
- 👥 Administración de usuarios
- 📅 Supervisión de reservas
- 🔐 Gestión de permisos

---

# 👨‍💼 Módulos del sistema

## 🚗 Vehicle Module

Este módulo administra todos los vehículos registrados en la plataforma.

### Funcionalidades:

- ➕ Registro de automóviles
- 📍 Gestión de disponibilidad
- 💰 Configuración de precios
- 🖼️ Administración multimedia
- 📋 Gestión vehicular

---

## 👤 Customer Module

Este módulo es utilizado por los clientes del sistema.

### Funcionalidades:

- 🔍 Buscar automóviles
- 📋 Consultar detalles
- 📅 Realizar reservas
- 💳 Gestionar pagos
- 📄 Historial de rentas

---

## 📅 Reservation Module

Este módulo administra el proceso de alquiler y reservas.

### Funcionalidades:

- 📆 Reservas dinámicas
- 📋 Gestión de contratos
- ⚡ Confirmaciones automáticas
- 💳 Seguimiento de pagos
- 📊 Historial administrativo

---

## 🛠️ Admin Module

Este módulo funciona como administrador principal del sistema.

### Funcionalidades:

- 👥 Gestión de usuarios
- 🚗 Supervisión vehicular
- 📊 Dashboard administrativo
- 📅 Administración de reservas
- 🔐 Gestión general

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,bootstrap,js" />
</p>

- HTML5
- CSS3
- Bootstrap
- JavaScript

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=php" />
</p>

- PHP
- CRUD System
- Programación orientada a objetos
- Gestión de sesiones

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Relaciones SQL
- Persistencia de datos
- Gestión vehicular

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- Visual Studio Code
- XAMPP / WAMP

---

# 📂 Estructura del proyecto

```bash
PlataformaWebGestionRentaVehiculos/
│
├── admin/                    # Panel administrativo
├── customer/                 # Gestión de clientes
├── vehicles/                 # Gestión de automóviles
├── reservations/             # Reservas y alquileres
├── assets/                   # Recursos frontend
├── database/                 # Scripts SQL
├── includes/                 # Configuración general
├── uploads/                  # Imágenes de vehículos
├── index.php                 # Página principal
├── login.php                 # Inicio de sesión
├── register.php              # Registro de usuarios
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP 7+
- MySQL
- Apache
- XAMPP / WAMP
- Navegador moderno

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/PlataformaWebGestionRentaVehiculos.git
```

---

## 2️⃣ Mover archivos

Copiar proyecto hacia:

```bash
xampp/htdocs/PlataformaWebGestionRentaVehiculos/
```

---

## 3️⃣ Crear base de datos

Crear base:

```bash
vehicle_management
```

---

## 4️⃣ Importar SQL

Importar:

```bash
database/vehicle_management.sql
```

---

## 5️⃣ Configurar conexión

Editar:

```bash
includes/config.php
```

Agregar:

```php
define('DB_HOST','localhost');
define('DB_USER','root');
define('DB_PASS','');
define('DB_NAME','vehicle_management');
```

---

## 6️⃣ Ejecutar proyecto

Abrir:

```bash
http://localhost/PlataformaWebGestionRentaVehiculos/
```

---

# 📊 Funcionalidades principales

## 🚗 Gestión vehicular

- Administración de automóviles
- Gestión de disponibilidad
- Configuración de tarifas
- Control de reservas

---

## 👥 Administración de usuarios

- Registro y autenticación
- Gestión de perfiles
- Roles administrativos
- Historial de operaciones

---

## 📅 Gestión de reservas

- Reservas en línea
- Contratos digitales
- Confirmaciones rápidas
- Gestión de pagos

---





# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo web full stack
- Gestión vehicular
- Bases de datos relacionales
- CRUD administrativos
- Sistemas DBMS
- Arquitectura web
- Automatización de reservas

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 💳 Integración de pagos
- 🤖 Recomendaciones inteligentes
- 🌐 API REST moderna
- 🔔 Notificaciones en tiempo real
- 📍 Seguimiento GPS

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por sistemas vehiculares, bases de datos y plataformas administrativas 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto académico open source orientado al aprendizaje de DBMS y administración de vehículos en renta.

---

<div align="center">

### 🚗 Vehicle Management System — administración inteligente de vehículos y alquileres 🚀

</div>
