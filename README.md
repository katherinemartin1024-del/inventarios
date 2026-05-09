# Proyecto Inventarios
Sistema Retail - Prototipo TRL5

## 🔗 Enlace al prototipo en Figma
[Ver prototipo navegable en Figma](https://www.figma.com/design/VGxauz2KjKWUqHGCAeh1zn/Proyecto?node-id=0-1&t=q9S6avHSCk02WYm5-1)

## 📑 Descripción
Este repositorio contiene la documentación y evidencias del sistema de gestión comercial y control automatizado de inventarios para microempresas del sector retail.  
El prototipo fue diseñado en Figma y cumple con el nivel de maduración tecnológica TRL5, mostrando pantallas móviles de:
- Login
- Dashboard
- Inventario
- Ventas
- Reportes
- Usuarios



## 1.Base de datos del sistema
El sistema Sistema Retail implementa una base de datos relacional en SQL Server, la cual permite la gestión estructurada de usuarios, productos, ventas y detalle de ventas

## 2.Modelo de datos
- Usuarios
- Productos
- Ventas
- Detalle_Venta

## 3.Relaciones
* Usuarios → Ventas (1:N) 
* Ventas → Detalle_Venta (1:N) 
* Productos → Detalle_Venta (1:N)

## 4.Implementación
Se utilizaron sentencias SQL para la creación de tablas y relaciones mediante claves primarias y foráneas, garantizando la integridad referencial del sistema


## 5.Evidencias
     Creación de la tabla Productos
En la siguiente captura se evidencia la creación de la tabla Productos en Sql server, esta tabla almacena la información del inventario, incluyendo campos como IdProducto, Nombre, Precio y Stock, lo que permite la gestión de los productos del sistema de manera estructurada

![image alt] (https://github.com/katherinemartin1024-del/inventarios/blob/5f64d672318d2e6776436a26ba710775fb41ff00/Productos.png)


     Creación de la tabla Ventas
En esta captura se evidencia la creación de la tabla Ventas en SQL Server, la cual almacena la información de las transacciones realizadas en el sistema, esta tabla registra datos como la fecha de la venta y el usuario responsable de la operación, permitiendo llevar el control de las ventas realizadas dentro del sistema





