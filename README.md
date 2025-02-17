# 📌 Bases de Datos NoSQL

## 📜 **Origen**
El concepto de **NoSQL** surgió a finales de los años 90, cuando **Carlo Strozzi** lo utilizó para describir una base de datos de código abierto que no usaba SQL pero seguía un modelo relacional. Sin embargo, fue en **2009** cuando el término ganó popularidad gracias a **Eric Evans**, de Rackspace, quien lo empleó para definir una nueva generación de bases de datos **no relacionales y distribuidas**.

## 🔹 **Definición de NoSQL**
**NoSQL** significa **"Not Only SQL"** (**No solo SQL**). Es un enfoque de bases de datos diseñado para almacenar y gestionar datos **sin estructuras tabulares tradicionales**, como las bases de datos relacionales. Se utilizan especialmente para **grandes volúmenes de datos no estructurados o semiestructurados**, brindando **escalabilidad y flexibilidad**.

## 🏗 **Arquitectura de NoSQL**

✔ **Modelos de datos flexibles y dinámicos:** Permiten almacenar datos en estructuras como **documentos, grafos y columnas**, en lugar del modelo tabular tradicional.

✔ **Escalabilidad horizontal:** Distribuyen los datos en múltiples servidores, mejorando el rendimiento y la capacidad de almacenamiento.

✔ **Consistencia eventual y tolerancia a particiones:** Garantizan que las lecturas devolverán la última versión confirmada del dato, aunque puedan existir inconsistencias temporales.

---

## 📂 **Tipos de Bases de Datos NoSQL**
Se clasifican en **cuatro tipos principales:**

### 🔑 **1. Clave-Valor**
Son el modelo más simple y eficiente para consultas rápidas. Cada dato es almacenado como un **par clave-valor**, lo que permite **altas velocidades de lectura y escritura**.
- **Ejemplos:** Cassandra, BigTable, HBase

![image](https://github.com/user-attachments/assets/26c4eec9-27f6-4e63-b023-491ac94c6c09)

---

### 📄 **2. Documentos**
Los datos se almacenan como documentos **JSON o BSON**, permitiendo estructuras flexibles y dinámicas.
- **Ejemplos:** MongoDB, CouchDB

![image](https://github.com/user-attachments/assets/30613374-d12b-40c5-bbdf-7437cc852497)

---

### 📊 **3. Columna Ancha**
Almacenan datos en **columnas en lugar de filas**, optimizando el rendimiento para consultas analíticas y mejorando la compresión de datos.
- **Ejemplos:** Apache Cassandra, HBase

---

### 🕸 **4. Grafos**
Se basan en nodos y relaciones para representar datos altamente interconectados, permitiendo análisis complejos de relaciones.
- **Ejemplos:** Neo4j, InfoGrid, Virtuoso

![image](https://github.com/user-attachments/assets/b1225133-c4e3-4a59-a28b-94e016f5aef4)

---

## 📌 **Casos de Uso Comunes**
- **Personalización de experiencias de usuario**
- **Gestión de perfiles y contenido**
- **Análisis en tiempo real**
- **Aplicaciones móviles y IoT (Internet de las Cosas)**

## ✅ **Ventajas de NoSQL**
✔ **Alta escalabilidad** horizontal.  
✔ **Flexibilidad en modelos de datos**.  
✔ **Mayor velocidad en operaciones de lectura/escritura**.  
✔ **Mejor manejo de grandes volúmenes de datos**.

## ❌ **Desventajas de NoSQL**
❌ **Menos consistencia transaccional** que SQL.  
❌ **Falta de estandarización** en lenguajes de consulta.  
❌ **Curva de aprendizaje** en algunos modelos de datos.

---

## 🗄 **MongoDB**
![image](https://github.com/user-attachments/assets/70fdda11-b32f-436f-925b-802488cd17a4)

MongoDB es una **base de datos orientada a documentos**, creada por **10gen**. Se destaca por:
- **Esquema flexible**, permitiendo documentos con estructuras distintas.
- **Uso de BSON**, una evolución de JSON que permite almacenar datos binarios.
- **Escrito en C++**, optimizado para rapidez y eficiencia.
- **Amplia adopción** en aplicaciones modernas.

---

## 📚 **Recursos Adicionales**
- 🔗 [MongoDB University](https://sites.google.com/mongodb.com/certification-program-spain/university?authuser=0)
- 📹 [Introducción a NoSQL - CódigoFacilito](https://www.youtube.com/watch?v=DPdAfgmkNuE&ab_channel=codigofacilito)
- 🔗 [Página oficial de MongoDB](https://www.mongodb.com/resources)

🚀 **¡Explora NoSQL y descubre cómo mejorar la escalabilidad de tus aplicaciones!**
