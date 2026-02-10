<div align="center">

# 💻 DWES - Desarrollo Web Entorno Servidor

### Proyectos y ejercicios de PHP, MySQL y Backend - Ciclo DAW
*Colección completa de ejercicios del módulo de Desarrollo Web en Entorno Servidor*

[![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com/)
[![Apache](https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white)](https://httpd.apache.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

</div>

---

## 📚 Tabla de Contenidos

- [📖 Descripción](#-descripción)
- [✨ Contenido](#-contenido-del-repositorio)
- [🗂️ Estructura](#️-estructura-del-proyecto)
- [🚀 Instalación](#-instalación)
- [📚 Proyectos destacados](#-proyectos-destacados)
- [🛠️ Tecnologías](#️-tecnologías)
- [💡 Conceptos aprendidos](#-conceptos-aprendidos)
- [👨‍💻 Autor](#-autor)

---

## 📖 Descripción

Repositorio académico del módulo **DWES (Desarrollo Web Entorno Servidor)** del Ciclo Formativo de Grado Superior en Desarrollo de Aplicaciones Web (DAW). Contiene ejercicios prácticos, proyectos CRUD, sistemas de autenticación y aplicaciones web completas con PHP, MySQL y Laravel.

---

## ✨ Contenido del repositorio

### 📁 Primera Evaluación (1eva/)
- 📚 Relación 1-4: Ejercicios fundamentales de PHP
- 📝 Examen de recuperación
- 🔧 Ejercicios de sintaxis y estructuras de control
- 🎯 POO básico

### 📁 Segunda Evaluación (2eva/)
- 🗄️ **Crud/**: Sistema CRUD con PHP y MySQL
- 🌐 **Crud-api/**: CRUD con API REST
- 🎨 **Crud-laravel/**: Proyecto Laravel completo
- 🔐 **Login/**: Sistema de autenticación
- 🏗️ **Login_mvc/**: Login con patrón MVC

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

## 🚀 Instalación

### Requisitos previos

```bash
✅ PHP 7.4 o superior
✅ MySQL 5.7 o superior
✅ Apache 2.4+
✅ Composer (para Laravel)
✅ XAMPP/WAMP/LAMP (recomendado)
```

### Pasos de instalación

```bash
# 1. Clonar repositorio
git clone https://github.com/albertogarciaquintana5-jpg/DWES-Servidor-PHP.git
cd DWES-Servidor-PHP

# 2. Configurar base de datos
mysql -u root -p
CREATE DATABASE dwes_db;

# 3. Para proyectos Laravel
cd 2eva/Crud-laravel
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate

# 4. Copiar a servidor web
# XAMPP: C:\xampp\htdocs\
# WAMP: C:\wamp64\www\
# Acceder a: http://localhost/DWES-Servidor-PHP
```

---

## 📚 Proyectos destacados

### 1️⃣ CRUD Básico (2eva/Crud/)
Sistema completo Create, Read, Update, Delete
- ✅ Conexión PHP + MySQL
- ✅ Formularios HTML
- ✅ Validación de datos
- ✅ Operaciones CRUD

### 2️⃣ CRUD con API REST (2eva/Crud-api/)
API RESTful con endpoints JSON
- ✅ GET, POST, PUT, DELETE
- ✅ Respuestas JSON
- ✅ Manejo de errores
- ✅ Arquitectura REST

### 3️⃣ Proyecto Laravel (2eva/Crud-laravel/)
Aplicación completa con framework
- ✅ Eloquent ORM
- ✅ Migraciones
- ✅ Blade templates
- ✅ Middleware

### 4️⃣ Sistema de Login (2eva/Login/ y Login_mvc/)
Autenticación de usuarios
- ✅ Hash de contraseñas
- ✅ Sesiones PHP
- ✅ Control de acceso
- ✅ Patrón MVC

---

## 🛠️ Tecnologías

| Tecnología | Uso |
|-----------|-----|
| ![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=php&logoColor=white) | Backend y lógica |
| ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | Base de datos |
| ![Laravel](https://img.shields.io/badge/-Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white) | Framework PHP |
| ![Apache](https://img.shields.io/badge/-Apache-D22128?style=flat-square&logo=apache&logoColor=white) | Servidor web |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Frontend |

---

## 💡 Conceptos aprendidos

**Backend:**
- ✅ Sintaxis PHP y POO
- ✅ PDO y MySQLi
- ✅ Prepared Statements
- ✅ Sesiones y Cookies
- ✅ Validación de formularios
- ✅ Arquitectura MVC
- ✅ APIs REST
- ✅ Framework Laravel

**Seguridad:**
- 🔒 Hashing de contraseñas
- 🔒 Prevención SQL Injection
- 🔒 Validación y sanitización
- 🔒 XSS Prevention
- 🔒 CSRF Tokens

**Base de datos:**
- 📊 Diseño de tablas
- 📊 Relaciones (1:1, 1:N, N:M)
- 📊 Consultas JOIN
- 📊 Migraciones

---

## 🎓 Contexto académico

- **Ciclo**: Desarrollo de Aplicaciones Web (DAW)
- **Módulo**: Desarrollo Web Entorno Servidor (DWES)
- **Nivel**: Grado Superior
- **Curso**: 2º DAW

---

## 🚦 Estado de los proyectos

| Proyecto | Estado |
|----------|--------|
| Ejercicios 1eva | ✅ 100% |
| CRUD Básico | ✅ 100% |
| CRUD API | ✅ 100% |
| Laravel CRUD | ✅ 100% |
| Login Simple | ✅ 100% |
| Login MVC | ✅ 100% |

---

## 👨‍💻 Autor

**Alberto García Quintana**
*Estudiante de DAW - Ciclo Superior*

- 📧 Email: albertogarciaquintana5@gmail.com
- 🔗 GitHub: [@albertogarciaquintana5-jpg](https://github.com/albertogarciaquintana5-jpg)
- 💼 LinkedIn: [Alberto García Quintana](https://linkedin.com/in/albertogarciaquintana)

---

<div align="center">

### ⭐ Si te resulta útil, ¡dale una estrella!

**Desarrollado con 💙 durante el ciclo DAW 🎓**

</div>
