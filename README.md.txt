NOMBRE: nahuel serrano
Documentación del Trabajo Práctico

Tema: Productos, Distribuidora y Categorías

1. Introducción

Este proyecto consiste en una pagina web para la gestión contable de una distribuidora, enfocada en la administración y registro de órdenes de compra.

2. Objetivos

Permitir el registro y administración de órdenes de compra.

Facilitar la visualización de órdenes de manera pública.

Ofrecer herramientas a los administradores para gestionar productos, categorías y órdenes de compra.

Implementar opciones de búsqueda y filtrado por categorías.

Proporcionar seguridad mediante autenticación de usuarios.

3. Características Principales

Panel público: Permite la visualización de las órdenes de compra.

Panel de administración: Requiere inicio de sesión y permite:

Crear, editar y eliminar órdenes de compra y categorias

Administrar categorías de productos.

Gestionar los registros de productos.

Búsqueda y filtrado: Los usuarios pueden buscar ordenes de compra por categoría.

Autenticación de usuarios: Solo los administradores pueden modificar los datos de la plataforma.

5. Estructura de la Base de Datos

Tablas principales:

Usuarios

id (INT, PRIMARY KEY, AUTO_INCREMENT)

gmail (VARCHAR, UNIQUE)

password (VARCHAR))


Categorías

id (INT, PRIMARY KEY, AUTO INCREMENTAL)

TipoProducto (VARCHAR))



Órdenes de Compra

id (INT, PRIMARY KEY, AUTO INCREMENTAL)

nombre (VARCHAR)

apellido (varchar)

nombre_producto (varchar)

TipoProducto (int,FK)

descripcion(text)

imagen(varchar)
