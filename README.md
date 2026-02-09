<div align="center">

# 💻 DWES - Desarrollo Web Entorno Servidor

### Proyectos y ejercicios de PHP, MySQL y Backend - Ciclo DAW

<p align="center">
  <img src="https://img.shields.io/badge/PHP-7.4+-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/MySQL-5.7+-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Apache-2.4+-D22128?style=for-the-badge&logo=apache&logoColor=white" alt="Apache">
  <img src="https://img.shields.io/badge/Laravel-8.x-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Academic-Project-blue?style=for-the-badge" alt="Academic">
</p>

<img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" alt="Backend Development Banner" width="400">

</div>

---

## 📖 Descripción

Este es el repositorio académico del módulo **DWES (Desarrollo Web Entorno Servidor)** del Ciclo Formativo de Grado Superior de **Desarrollo de Aplicaciones Web (DAW)**.

Contiene una colección completa de:
- ✨ Ejercicios prácticos de PHP y MySQL
- 🚀 Proyectos CRUD completos
- 🏗️ Implementaciones con Arquitectura MVC
- 🌐 APIs REST funcionales
- 🔐 Sistemas de autenticación
- 🎨 Proyectos con Laravel Framework

---

## ✨ Contenido del repositorio

### **Primera Evaluación (1eva/)**
- 📚 **Relación 1-4**: Ejercicios fundamentales de PHP
  - Sintaxis básica y variables
  - Estructuras de control
  - Funciones y arrays
  - Programación orientada a objetos
- 📝 **Examen de recuperación**: Ejercicios de evaluación
- 🔧 **Ejercicios de sintaxis y estructuras**: Prácticas adicionales

### **Segunda Evaluación (2eva/)**
- 🗄️ **Crud/**: Sistema CRUD completo con PHP y MySQL
- 🌐 **Crud-api/**: CRUD con API REST y respuestas JSON
- 🎨 **Crud-laravel/**: Proyecto completo con Laravel Framework
- 🔐 **Login/**: Sistema de autenticación de usuarios
- 🏗️ **Login_mvc/**: Login implementado con patrón MVC

---

## 🗂️ Estructura del Proyecto

```
DWES-Servidor-PHP/
├── 1eva/
│   ├── Examen recuperacion/
│   ├── Relacion4/
│   ├── relacion1/
│   ├── relacion2/
│   ├── relacion3/
│   └── index.html
├── 2eva/
│   ├── Crud/              # CRUD básico PHP+MySQL
│   ├── Crud-api/          # CRUD con API REST
│   ├── Crud-laravel/      # Proyecto Laravel
│   ├── Login/             # Sistema de login
│   └── Login_mvc/         # Login patrón MVC
└── README.md
```

---

## 🚀 Instalación y Configuración

### **Requisitos previos:**

```bash
✅ PHP 7.4 o superior
✅ MySQL 5.7 o superior
✅ Apache 2.4+
✅ Composer (para Laravel)
✅ XAMPP/WAMP/LAMP (recomendado)
```

### **Instalación:**

```bash
# 1. Clonar repositorio
git clone https://github.com/albertogarciaquintana5-jpg/DWES-Servidor-PHP.git
cd DWES-Servidor-PHP

# 2. Configurar base de datos
# Crear base de datos en MySQL
mysql -u root -p
CREATE DATABASE dwes_db;

# 3. Para proyectos Laravel
cd 2eva/Crud-laravel
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate

# 4. Configurar servidor
# Copiar carpeta a htdocs (XAMPP) o www (WAMP)
# Acceder a: http://localhost/DWES-Servidor-PHP
```

---

## 📚 Proyectos destacados

### 1️⃣ CRUD Básico (2eva/Crud/)
**Sistema completo de Create, Read, Update, Delete**
- ✅ Conexión PHP + MySQL
- ✅ Formularios HTML
- ✅ Validación de datos
- ✅ Operaciones CRUD completas

### 2️⃣ CRUD con API REST (2eva/Crud-api/)
**API RESTful con endpoints JSON**
- 🌐 GET, POST, PUT, DELETE
- 📦 Respuestas JSON
- ⚠️ Manejo de errores
- 🏗️ Arquitectura REST

### 3️⃣ Proyecto Laravel (2eva/Crud-laravel/)
**Aplicación completa con framework**
- 🗄️ Eloquent ORM
- 📊 Migraciones
- 🎨 Blade templates
- 🛣️ Rutas RESTful
- 🔒 Middleware

### 4️⃣ Sistema de Login (2eva/Login/ y Login_mvc/)
**Autenticación de usuarios**
- 🔐 Hash de contraseñas
- 📝 Sesiones PHP
- 🚪 Control de acceso
- 🏗️ Patrón MVC (versión MVC)

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Versión | Uso |
|-----------|---------|-----|
| ![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=php&logoColor=white) | 7.4+ | Backend y lógica |
| ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | 5.7+ | Base de datos |
| ![Laravel](https://img.shields.io/badge/-Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white) | 8.x | Framework PHP |
| ![Apache](https://img.shields.io/badge/-Apache-D22128?style=flat-square&logo=apache&logoColor=white) | 2.4+ | Servidor web |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | ES6 | Frontend |
| ![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white) | 5.x | CSS Framework |

---

## 💡 Conceptos aprendidos

### **Backend:**
- ✅ Sintaxis PHP y POO
- ✅ Conexión a bases de datos
- ✅ PDO y MySQLi
- ✅ Prepared Statements
- ✅ Sesiones y Cookies
- ✅ Validación de formularios
- ✅ Subida de archivos
- ✅ Arquitectura MVC
- ✅ APIs REST
- ✅ Framework Laravel
- ✅ Composer y dependencias

### **Seguridad:**
- 🔒 Hashing de contraseñas (password_hash)
- 🔒 Prevención SQL Injection
- 🔒 Validación y sanitización
- 🔒 XSS Prevention
- 🔒 CSRF Tokens

### **Base de datos:**
- 📊 Diseño de tablas
- 📊 Relaciones (1:1, 1:N, N:M)
- 📊 Consultas complejas (JOIN)
- 📊 Migraciones
- 📊 Seeding

---

## 🎓 Contexto académico

- **Ciclo**: Desarrollo de Aplicaciones Web (DAW)
- **Módulo**: Desarrollo Web Entorno Servidor (DWES)
- **Nivel**: Grado Superior
- **Curso**: 2º DAW
- **Horas**: 160 horas

---

## 📝 Evaluación

### **Primera evaluación:**
- 📌 Fundamentos de PHP
- 📌 Estructuras de control
- 📌 Funciones y arrays
- 📌 POO básico

### **Segunda evaluación:**
- 📌 PHP avanzado
- 📌 MySQL y PDO
- 📌 Proyectos CRUD
- 📌 MVC y Laravel
- 📌 APIs REST

---

## 🚦 Estado de los proyectos

| Proyecto | Estado | Completado |
|----------|--------|-----------|
| Ejercicios 1eva | ✅ Completo | 100% |
| CRUD Básico | ✅ Completo | 100% |
| CRUD API | ✅ Completo | 100% |
| Laravel CRUD | ✅ Completo | 100% |
| Login Simple | ✅ Completo | 100% |
| Login MVC | ✅ Completo | 100% |

---

## 📸 Screenshots

> 🚧 Las capturas se añadirán próximamente

---

## 🤝 Contribuir

Si eres estudiante de DAW y quieres aportar:
1. 🍴 Fork el repositorio
2. ➕ Añade tus ejercicios
3. 📝 Documenta tu código
4. 🔄 Crea un Pull Request

---

## 📄 Licencia

MIT License - Proyecto académico

---

## 👨‍💻 Autor

**Alberto García Quintana**  
*Estudiante de DAW - Ciclo Superior*

- 📧 Email: albertogarciaquintana5@gmail.com
- 🔗 GitHub: [@albertogarciaquintana5-jpg](https://github.com/albertogarciaquintana5-jpg)
- 💼 LinkedIn: [Alberto García Quintana](https://linkedin.com/in/albertogarciaquintana)

---

## 🔗 Recursos útiles

- 📖 [PHP Official Documentation](https://www.php.net/docs.php)
- 🎨 [Laravel Documentation](https://laravel.com/docs)
- 🗄️ [MySQL Documentation](https://dev.mysql.com/doc/)
- 🌐 [MDN Web Docs](https://developer.mozilla.org/)

---

<div align="center">

### ⭐ Si este repositorio te ha sido útil, considera darle una estrella

**Hecho con ❤️ por un estudiante de DAW**

</div>
