# 🐘 PostgreSQL: Guía de Referencia Esencial

¡Bienvenido/a a la documentación de PostgreSQL! 👋  
Este archivo resume todo lo que necesitas saber sobre **PostgreSQL**, el sistema de bases de datos relacional de código abierto más avanzado del mundo.

---

## 📌 ¿Qué es PostgreSQL?
**PostgreSQL** (también conocido como Postgres) es un sistema de gestión de bases de datos relacionales (RDBMS) de código abierto con más de 30 años de desarrollo activo. Destaca por su robustez, extensibilidad y cumplimiento con estándares SQL.

---

## ✔️ Características Principales

### 🔹 Funcionalidades Avanzadas
- **Tipos de datos personalizables**: Crea tus propios tipos de datos y operadores.
- **Soporte JSON nativo**: Almacena y consulta datos JSON/JSONB con operadores específicos.
- **Full Text Search**: Búsqueda avanzada de texto completo integrada.

### 🔹 Concurrencia y Rendimiento
- **MVCC (Multiversion Concurrency Control)**: Permite altos niveles de concurrencia sin bloqueos.
- **Particionamiento**: Soporte nativo para particionamiento de tablas.
- **Parallel Query**: Ejecución paralela de consultas para mejor rendimiento.

### 🔹 Extensibilidad
- **PL/pgSQL**: Lenguaje procedural propio (similar a PL/SQL de Oracle).
- **Extensiones**: Más de 150 extensiones disponibles (PostGIS para geodatos, pgcrypto para cifrado, etc.).

---

## ✅ Ventajas de PostgreSQL

| Beneficio | Descripción |
|-----------|-------------|
| **Estándar SQL** | Uno de los RDBMS más compatibles con el estándar SQL. |
| **Open Source** | Licencia PostgreSQL (similar a MIT/BSD), completamente gratuita. |
| **Escalabilidad** | Maneja grandes volúmenes de datos y usuarios concurrentes. |
| **Fiabilidad** | Sistema muy estable con protección contra corrupción de datos. |
| **Comunidad** | Comunidad activa y documentación excelente. |

---

## ❌ Desventajas y Limitaciones

| Limitación | Detalle |
|------------|---------|
| **Consumo de recursos** | Requiere más memoria y CPU que MySQL para configuraciones equivalentes. |
| **Complejidad** | Curva de aprendizaje más pronunciada para funciones avanzadas. |
| **Popularidad en web** | Menor adopción en aplicaciones web simples frente a MySQL. |
| **Replicación** | Configuración más compleja para clustering nativo. |

---

## 📊 PostgreSQL vs MySQL

| Característica | PostgreSQL | MySQL |
|---------------|------------|-------|
| **Modelo ACID** | ✅ Completo | ✅ (solo con InnoDB) |
| **Vistas materializadas** | ✅ | ✅ (v8.0+) |
| **Tipos de datos JSON** | ✅ (con operadores) | ✅ (menos funciones) |
| **Procedimientos almacenados** | PL/pgSQL | Sintaxis propietaria |
| **Índices GIN/GiST** | ✅ (para búsquedas complejas) | ❌ |

---

## 🚀 Primeros Pasos

### Instalación Básica
```bash
# En Ubuntu/Debian:
sudo apt update
sudo apt install postgresql postgresql-contrib

# Iniciar servicio:
sudo systemctl start postgresql