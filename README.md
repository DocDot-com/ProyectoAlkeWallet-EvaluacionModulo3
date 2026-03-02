# Alke Wallet – Evaluación Módulo 3

Este repositorio contiene el desarrollo de la evaluación ABP del módulo **Fundamentos de Bases de Datos Relacionales**, cuyo objetivo es implementar una base de datos relacional para una billetera digital llamada **Alke Wallet**.

## 🛠️ Tecnologías utilizadas
- SQLite
- SQL

## 📦 Estructura del proyecto
- `alkewallet.db` → base de datos SQLite
- `alkewallet.sql` → script SQL de creación y consultas
- `Evaluación ABP.docx` → informe del proyecto
- `diagrama_ER_alkewallet.png` → diagrama entidad–relación

## 🗃️ Modelo de datos
La base de datos está compuesta por las siguientes tablas:
- **usuario**: almacena los datos de los usuarios.
- **moneda**: almacena los tipos de moneda.
- **transaccion**: registra las transacciones entre usuarios.

Las tablas se relacionan mediante claves primarias y foráneas para asegurar la integridad referencial.

## ✅ Funcionalidades implementadas
- Creación de tablas (DDL)
- Inserción de datos (DML)
- Consultas SQL con JOIN
- Actualización de datos (UPDATE)
- Eliminación de registros (DELETE)

## 📌 Autor
- Daniel Hernández
