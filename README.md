# Apache Cassandra: Base de Datos Distribuida NoSQL

## 📌 Descripción
**Apache Cassandra** es una base de datos distribuida, altamente escalable y de código abierto, diseñada para manejar grandes volúmenes de datos estructurados y no estructurados en múltiples servidores sin un punto único de fallo. Pertenece a la categoría **NoSQL** y sigue un modelo de almacenamiento **column-oriented** (orientado a columnas).

## ✨ Características Principales
- **Arquitectura Distribuida**: Sin nodo maestro (masterless), todos los nodos son iguales.
- **Alta Disponibilidad**: Replicación automática y tolerancia a fallos (CAP Theorem: AP).
- **Escalabilidad Horizontal**: Añade nodos fácilmente para aumentar capacidad.
- **Lenguaje de Consulta**: **CQL** (Cassandra Query Language), similar a SQL.
- **Flexibilidad en Esquema**: No requiere un esquema fijo (schemaless).
- **Rendimiento**: Optimizado para escrituras rápidas y lecturas eficientes.

## ✅ Ventajas
- **Resistente a Fallos**: Datos replicados en múltiples nodos.
- **Baja Latencia**: Ideal para aplicaciones en tiempo real.
- **Multiplataforma**: Soporta múltiples centros de datos y nubes.
- **Open Source**: Comunidad activa y sin costos de licencia.
- **Linealmente Escalable**: Mejora de rendimiento al añadir nodos.

## ❌ Desventajas
- **Sin JOINs ni Subconsultas**: Limitaciones en consultas complejas (denormalización necesaria).
- **Consistencia Eventual**: Configurable, pero puede no ser ideal para todos los casos.
- **Curva de Aprendizaje**: Diferencias significativas respecto a bases SQL tradicionales.
- **Alto Uso de Recursos**: Requiere planificación de hardware para optimización.

## 🛠 Casos de Uso Comunes
- Sistemas de **mensajería en tiempo real** (ej: chats).
- Almacenamiento de **datos de sensores** (IoT).
- Plataformas de **e-commerce** (carritos de compra).
- **Análisis de big data** con alta velocidad de escritura.

## 🔗 Recursos Oficiales
- [Sitio Web](https://cassandra.apache.org/)
- [Documentación](https://cassandra.apache.org/doc/latest/)
- [GitHub](https://github.com/apache/cassandra)
