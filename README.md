# 🗃️ Cheat Sheets de Bases de Datos SQL y NoSQL

¡Bienvenido/a al repositorio de referencia rápida para bases de datos! 👋  
Este proyecto contiene **hojas de trucos (cheat sheets)** esenciales para trabajar con bases de datos relacionales (SQL) y no relacionales (NoSQL). 

---

## Tareas para Nelson: Bases de Datos NoSQL
- ✅ Crear una rama para base de datos NoSQL (MongoDB, Redis, Cassandra)
- ✅ Cada rama de las base de datos NoSQL debe contener: un README.md el cual contenga
una breve explicacion de esa base datos, caracteristicas, ventajas y desventajas. Y adjuntar
el archivo de pdf con su cheatsheet en formato de pdf.    

---

## Tareas para Jorge: Bases de Datos SQL
- ✅ Crear una rama para base de datos NoSQL (MySQL, PostgreSQL, Oracle)
- ✅ Cada rama de las base de datos SQL debe contener: un README.md el cual contenga
una breve explicacion de esa base datos, caracteristicas, ventajas y desventajas. Y adjuntar
el archivo de pdf con su cheatsheet en formato de pdf.   

## 📌 ¿Qué encontrarás aquí?
- ✅ Comandos y sintaxis clave para SQL (MySQL, PostgreSQL, Oracle)  
- ✅ Operaciones esenciales en NoSQL (MongoDB, Redis, Cassandra)  
- ✅ Comparativas entre tecnologías  
- ✅ Ejemplos prácticos listos para usar  

---

# 📚 Fundamentos de Bases de Datos

## 1. Bases de Datos SQL (Relacionales)
**Definición**:  
Sistemas que almacenan datos en tablas relacionadas mediante claves primarias/foráneas, usando el lenguaje SQL (Structured Query Language).

### ✔️ Características Principales
- [ ] Esquema rígido y predefinido (tablas, columnas, tipos de datos)  
- [ ] ACID (Atomicidad, Consistencia, Aislamiento, Durabilidad)  
- [ ] Escalabilidad vertical (aumentar capacidad de servidor)  
- [ ] Ejemplos: MySQL, PostgreSQL, Oracle, SQL Server  

### ✅ Ventajas
- [ ] Integridad de datos garantizada  
- [ ] Consultas complejas con JOINs  
- [ ] Madurez y amplia documentación  

### ❌ Desventajas
- [ ] Menor flexibilidad para cambios en el esquema  
- [ ] Dificultad para escalar horizontalmente  
- [ ] Puede ser excesivo para datos no estructurados  

---

## 2. Bases de Datos NoSQL (No Relacionales)
**Definición**:  
Sistemas flexibles que almacenan datos en formatos no tabulares (documentos, grafos, clave-valor, etc.).

### ✔️ Características Principales
- [ ] Esquema dinámico o sin esquema  
- [ ] BASE (Basically Available, Soft state, Eventually consistent)  
- [ ] Escalabilidad horizontal (distribución en múltiples servidores)  
- [ ] Tipos principales:  
  - **Documentos**: MongoDB, CouchDB  
  - **Clave-Valor**: Redis, DynamoDB  
  - **Grafos**: Neo4j  
  - **Columnas**: Cassandra  

### ✅ Ventajas
- [ ] Alta flexibilidad para datos cambiantes  
- [ ] Rendimiento en grandes volúmenes de datos  
- [ ] Escalabilidad masiva  

### ❌ Desventajas
- [ ] Sin garantías ACID completas (en la mayoría)  
- [ ] Menor estandarización (sintaxis varía por motor)  
- [ ] Consultas complejas pueden ser difíciles  

---

## 🔄 SQL vs NoSQL: ¿Cuándo usar cada una?
| Criterio          | SQL              | NoSQL             |
|-------------------|------------------|-------------------|
| **Estructura**    | Datos estructurados | Datos semiestructurados/no estructurados |
| **Escalabilidad** | Vertical         | Horizontal        |
| **Consistencia**  | Fuerte           | Eventual (en muchos casos) |
| **Mejor para**    | Transacciones financieras, sistemas legacy | Big Data, IoT, aplicaciones en tiempo real |

---

## 🚀 Cómo usar este repositorio
1. [ ] Explora las carpetas `/SQL` y `/NoSQL`  
2. [ ] Descarga los cheat sheets en PDF o Markdown  
3. [ ] ¡Practica con los ejemplos incluidos!  

> 💡 **Tip**: Usa los checkboxes (☑️) para marcar los conceptos que ya dominas.

---

## 📬 Contribuciones
¡Se aceptan contribuciones! Si quieres agregar más ejemplos o corregir información:  
1. Haz fork al repositorio  
2. Crea una rama con tu cambio (`git checkout -b mejora-sql`)  
3. Envía un Pull Request  

📜 **Licencia**: MIT © 2023