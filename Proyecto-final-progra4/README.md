

# Sistema de Facturación - Proyecto Final

## Descripción
El **Sistema de Facturación** es una solución diseñada para agilizar la gestión de clientes, productos y facturas en una tienda agrícola. El proyecto combina los principios de la Programación Orientada a Objetos y una arquitectura modular para garantizar escalabilidad, mantenibilidad y claridad en el código.


Este proyecto implementa un sistema de facturación de una tienda agricola  en Python utilizando principios de Programación Orientada a Objetos y una arquitectura modular de tres capas: **Modelo**, **Controlador**, y **Vista** (UI).

## Estructura del Proyecto
- **Modelo**: Clases que representan las entidades del dominio (`Cliente`, `Producto`, `Factura`, etc.).
- **Controladores**: Gestionan la lógica de negocio y las operaciones CRUD.
- **Icrud**: Interfaz genérica para operaciones CRUD.
- **Pruebas**: Pruebas unitarias para garantizar la calidad del código.
- **UI**: Interfaz de usuario basada en consola para interactuar con el sistema.

## Funcionalidades
1. **Gestión de Clientes**:
   - Crear, leer, actualizar y eliminar clientes.
2. **Gestión de Productos**:
   - Crear, leer, actualizar y eliminar productos, informacion relevante de productos.
3. **Gestión de Facturas**:
   - Crear facturas asociadas a clientes.
   - Agregar productos a las facturas.
   - Consultar el total de una factura o el total acumulado de todas las facturas.
4. **Interfaz de Usuario**:
   - Menú de opciones para interactuar con el sistema.

## Requisitos
- Python 3.8+


## Instalación
1. Clona el repositorio:
   ```bash
   git clone https://github.com/usuario/proyecto-facturacion.git
