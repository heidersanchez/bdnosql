### Clase 01: Bases de Datos NoSQL

**Duración**: 3 horas  
**Objetivo**: Que los estudiantes comprendan cuándo y por qué elegir una base de datos NoSQL frente a una base de datos relacional, a través de casos prácticos y ejemplos del mundo real.

### Estructura de la Clase

#### 1. Introducción a Bases de Datos NoSQL (30 minutos)

**Objetivo**: Proveer una comprensión básica de las características de las bases de datos NoSQL.

- **Breve historia y evolución**: 
  - Surgimiento del concepto de NoSQL.
  - Diferencias principales con las bases de datos relacionales.
  
- **Características clave de NoSQL**:
  - No siguen un esquema fijo.
  - Escalabilidad horizontal.
  - Tipos de bases de datos NoSQL: 
    - Documentales (MongoDB, Couchbase).
    - Clave-Valor (Redis, DynamoDB).
    - Columnar (Cassandra, HBase).
    - Grafos (Neo4j).

**Actividad**:  
Realizar una pequeña encuesta en clase para identificar qué tipos de bases de datos han utilizado los estudiantes.

#### 2. ¿Cuándo usar NoSQL? (45 minutos)

**Objetivo**: Mostrar escenarios donde NoSQL es la opción más adecuada en lugar de una base de datos relacional.

- **Escalabilidad y rendimiento**: 
  - Ejemplo: Redes sociales (Facebook, Twitter).
  - Descripción: Explicar cómo el volumen de datos y la necesidad de disponibilidad a escala global hacen que las bases de datos NoSQL sean adecuadas. Comparar con las dificultades de escalar bases de datos relacionales en este tipo de aplicaciones.

- **Modelado de datos no estructurados**: 
  - Ejemplo: Sitios web de comercio electrónico (Amazon).
  - Descripción: El catálogo de productos en sitios de e-commerce varía mucho en estructura y es difícil de modelar con tablas relacionales. Una base de datos documental permite flexibilidad en los formatos de los productos.

- **Manejo de grandes volúmenes de datos**:
  - Ejemplo: IoT (Internet de las Cosas) y análisis en tiempo real.
  - Descripción: Explicar cómo bases de datos NoSQL como Cassandra manejan flujos masivos de datos a gran velocidad, en comparación con las limitaciones de bases relacionales en estas situaciones.

**Actividad**:  
Dividir la clase en pequeños grupos y asignarles un caso práctico. Cada grupo debe discutir y presentar si usarían una base de datos relacional o NoSQL y justificar su elección. Casos sugeridos:
   - Aplicación de mensajería instantánea.
   - Sistema de recomendaciones personalizadas.
   - Plataforma de streaming de video.
   
#### 3. Comparativa NoSQL vs. Relacional en Casos Prácticos (45 minutos)

**Objetivo**: Profundizar en las decisiones de diseño mediante un análisis comparativo en escenarios del mundo real.

- **Caso 1**: 
  - **Sistema de recomendaciones** (Amazon, Netflix).
  - **NoSQL utilizado**: Bases de datos documentales (MongoDB, Couchbase).
  - **Explicación**: Flexibilidad y escalabilidad para gestionar diferentes tipos de datos relacionados a los usuarios y sus preferencias.

- **Caso 2**: 
  - **Aplicaciones en tiempo real** (juegos multijugador online).
  - **NoSQL utilizado**: Bases de datos en memoria clave-valor (Redis).
  - **Explicación**: Bajísima latencia y altas tasas de lectura y escritura.

- **Caso 3**: 
  - **Análisis de grafos** (redes sociales, detección de fraudes).
  - **NoSQL utilizado**: Bases de datos de grafos (Neo4j).
  - **Explicación**: Relaciones complejas y jerárquicas entre entidades que serían difíciles de manejar en tablas relacionales.

**Actividad**:  
Mostrar código de ejemplo para una aplicación sencilla utilizando MongoDB y comparar con una estructura relacional, demostrando las ventajas y desventajas de cada enfoque.

#### 4. Hands-on: Implementación básica de un caso práctico con MongoDB (1 hora)

**Objetivo**: Los estudiantes crearán una pequeña aplicación usando MongoDB para experimentar la estructura y ventajas de NoSQL.

**Paso a paso**:
   - Instalar MongoDB (localmente o utilizando un servicio en la nube como MongoDB Atlas).
   - Crear una base de datos para una aplicación de catálogo de productos.
   - Insertar, actualizar y consultar datos no estructurados.
   - Mostrar cómo se manejan los datos no estructurados y la escalabilidad del sistema.

**Actividad**:  
Los estudiantes crearán un pequeño sistema de gestión de usuarios con MongoDB, insertando documentos con campos flexibles y realizando consultas básicas.

### Cierre y Discusión (15 minutos)

**Objetivo**: Reflexionar sobre los conceptos clave.

- Resumir las principales diferencias entre NoSQL y relacional.
- Abrir un espacio para preguntas y discusión.
- Hablar sobre el futuro de NoSQL y su integración con sistemas híbridos.

### Recursos

- **Documentación** de MongoDB: https://www.mongodb.com/docs/
- **Ejemplos de código**: Aplicaciones básicas con MongoDB, Redis y Neo4j.
- **Guías de instalación y configuración**.

---
