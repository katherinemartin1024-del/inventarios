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

![image alt](https://github.com/katherinemartin1024-del/inventarios/blob/6a160570a4e62f8e80faef8105a1e8f546650b5b/Productos.png)


     Creación de la tabla Ventas
En esta captura se evidencia la creación de la tabla Ventas en SQL Server, la cual almacena la información de las transacciones realizadas en el sistema, esta tabla registra datos como la fecha de la venta y el usuario responsable de la operación, permitiendo llevar el control de las ventas realizadas dentro del sistema

![image alt](https://github.com/katherinemartin1024-del/inventarios/blob/6b8225c1fb991e4d2a17ef8ad544967e1b9d7a07/Ventas.png)


     Creación de la tabla Detalle_Venta
En la siguiente captura se evidencia la creación de la tabla Detalle_Venta en la cual se puede almacenar el detalle de cada transacción de venta, en esta tabla se registran los productos asociados a cada venta, junto con la cantidad y el precio unitario, permitiendo descomponer cada venta en sus elementos individuales
![image alt](https://github.com/katherinemartin1024-del/inventarios/blob/c65e2c58518aa431e6de824d64b3d194946bc6f0/Detalle_Venta.png)

     Creación de la tabla Usuarios
Esta tabla permite gestionar el acceso al sistema Sistema_Retail y almacena información relacionada con los usuarios del sistema, incluyendo datos como nombre de usuario, contraseña, rol y estado, lo que permite controlar la autenticación y los permisos de acceso dentro de la aplicación

![image alt](https://github.com/katherinemartin1024-del/inventarios/blob/29c082126d77a79600074f647c8d548b00e4739a/Usuarios.png)


     Creación de la tabla Diagrama de base de datos Sistema_Retail
En él se evidencian las tablas Usuarios, Productos, Ventas y Detalle_Venta, junto con sus relaciones mediante claves primarias y foráneas, dichas relaciones permiten conectar la información entre usuarios, productos y ventas dentro del sistema
![image alt](https://github.com/katherinemartin1024-del/inventarios/blob/969edd14e5d86fb9ac96e6a313d6d4a1ddbc986d/Diagrama%20base.png)


     Consulta Join
Dentro de esta consulta se utiliza JOIN para integrar información de varias tablas, permitiendo visualizar usuarios, productos y ventas registradas dentro del sistema en una sola consulta
![image alt](https://github.com/katherinemartin1024-del/inventarios/blob/1c98f7175225464bc1ffc5d3c8a7d85f0f13b38d/Consulta%20Join.jpg)
