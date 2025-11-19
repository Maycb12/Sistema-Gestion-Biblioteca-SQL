# Sistema de Gestión de Biblioteca 

Este proyecto consiste en una base de datos relacional diseñada en **MySQL** para gestionar las operaciones básicas de una biblioteca.

## Tecnologías Utilizadas
* MySQL (Workbench)
* Lenguaje SQL (DDL, DML, DQL)

## Estructura del Proyecto
El sistema gestiona 4 entidades principales:
1. **Autores:** Registro de escritores.
2. **Libros:** Inventario con referencia a autores.
3. **Socios:** Usuarios registrados en la biblioteca.
4. **Préstamos:** Tabla transaccional que registra quién llevó qué libro y cuándo (Relación N:M).

## Funcionalidades Clave
* **Integridad Referencial:** Uso de `FOREIGN KEY` para vincular préstamos con libros y socios.
* **Control de Stock:** Actualización de disponibilidad de libros mediante `UPDATE`.
* **Consultas Avanzadas:** Reportes usando `INNER JOIN` para ver historiales de préstamos y libros pendientes de devolución.

## Cómo instalar
1. Descarga el archivo `Proyecto_Biblioteca.sql`.
2. Abre MySQL Workbench.
3. Ve a `File > Open SQL Script` y selecciona el archivo.
4. Ejecuta el script completo (Icono del rayo).
