# Práctica SQL, ETL & DataWarehouse
## Bootcamp Big Data, Machine Learning &amp; IA_Keepcoding

Este repositorio contiene la resolución de una práctica avanzada de **SQL** y **Data Warehousing (DW)**. A lo largo de trece ejercicios, se abordan tareas clave relacionadas con el modelado de datos, creación de tablas y cálculos avanzados.

---

## 🎯 Objetivos de la práctica
1. Diseñar un modelo de datos robusto basado en requisitos reales.
2. Desarrollar habilidades avanzadas en SQL para el manejo de datos, cálculo de campos y limpieza de información.
3. Implementar funciones y estructuras que optimicen la gestión de datos en un entorno de Data Warehousing.

## 📊 Dataset utilizados
Los archivos CSV utilizados en esta práctica se encuentran disponibles en la carpeta [data](./data). Estos archivos contienen los datos necesarios para el desarrollo de las consultas SQL y la creación de tablas.

Archivos incluidos:
- `ivr_calls.csv`
- `ivr_modules.csv`
- `ivr_steps.csv`

## 📝 Documentación
Para más detalles sobre los ejercicios y objetivos de la práctica, consulta el archivo [Practica_Advanced_SQL](./docs/descripcion_practica.pdf), ubicado en la carpeta `docs`.

## 📈 Desarrollo de la práctica
### **1. Diagrama Entidad-Relación**
- Creación de un diagrama **Entidad-Relación (ER)** para modelar una base de datos orientada a **Keepcoding** (alumnos, bootcamps, módulos, profesores, etc.).
- 📄 [Ejercicio1 resuelto](https://github.com/IrisMejuto/Practice-SQL-and-DW/blob/main/02/02_KeepCoding_DDBB_Creation.sql)

### **2. Creación de Base de Datos**
- Desarrollo de un script en **PostgreSQL** para crear las tablas y restricciones basadas en el diagrama ER.
- 📄 [Ejercicio2 resuelto](https://github.com/IrisMejuto/Practice-SQL-and-DW/blob/main/02/02_KeepCoding_DDBB_Creation.sql)

### **3. Modelo Base de datos IVR (Interactive Voice Response) y Campos Calculados**
- Creación de la tabla **`ivr_detail`** basada en múltiples tablas de entrada (`ivr_calls`, `ivr_modules`, `ivr_steps`) y con diversos campos calculados.
- Generación de campos clave como:
  - **`vdn_aggregation`**
  - **`document_type` y `document_identification`**
  - **`customer_phone`**
  - **`billing_account_id`**
  - Flags como **`masiva_lg`, `info_by_phone_lg`** y otros.
-  📄 [Ejercicio3 resuelto](https://github.com/IrisMejuto/Practice-SQL-and-DW/blob/main/02/02_KeepCoding_DDBB_Creation.sql)
-  📄 [Ejercicio4 resuelto](https://github.com/IrisMejuto/Practice-SQL-and-DW/blob/main/02/02_KeepCoding_DDBB_Creation.sql)
-  📄 [Ejercicio5 resuelto](https://github.com/IrisMejuto/Practice-SQL-and-DW/blob/main/02/02_KeepCoding_DDBB_Creation.sql)
-  📄 [Ejercicio6 resuelto](https://github.com/IrisMejuto/Practice-SQL-and-DW/blob/main/02/02_KeepCoding_DDBB_Creation.sql)
-  📄 [Ejercicio7 resuelto](https://github.com/IrisMejuto/Practice-SQL-and-DW/blob/main/02/02_KeepCoding_DDBB_Creation.sql)
-  📄 [Ejercicio8 resuelto](https://github.com/IrisMejuto/Practice-SQL-and-DW/blob/main/02/02_KeepCoding_DDBB_Creation.sql)
-  📄 [Ejercicio9 resuelto](https://github.com/IrisMejuto/Practice-SQL-and-DW/blob/main/02/02_KeepCoding_DDBB_Creation.sql)
-  📄 [Ejercicio10 resuelto](https://github.com/IrisMejuto/Practice-SQL-and-DW/blob/main/02/02_KeepCoding_DDBB_Creation.sql)
-  📄 [Ejercicio11 resuelto](https://github.com/IrisMejuto/Practice-SQL-and-DW/blob/main/02/02_KeepCoding_DDBB_Creation.sql)

### **4. Tabla Resumen: ivr_summary**
- Construcción de la tabla **`ivr_summary`**, que incluye los indicadores más relevantes de las llamadas.
- 📄 [Ejercicio12 resuelto](https://github.com/IrisMejuto/Practice-SQL-and-DW/blob/main/02/02_KeepCoding_DDBB_Creation.sql)

### **5. Función de Limpieza de enteros**
- Implementación de la función **`clean_integer`**: convierte valores nulos a un placeholder predeterminado (-999999).
- 📄 [Ejercicio13 resuelto](https://github.com/IrisMejuto/Practice-SQL-and-DW/blob/main/02/02_KeepCoding_DDBB_Creation.sql)

## 🛠️ Lenguajes y Herramientas Utilizadas

- Lenguaje: SQL
- Sistema de gestión de bases de datos relacional: PostgreSQL






