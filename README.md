# Sistema de Punto de Venta - Laravel + Livewire 3

Este proyecto es un **sistema de punto de venta** desarrollado con el framework **Laravel** y la librería **Livewire 3** para una experiencia de usuario dinámica y moderna.

## Características principales

El sistema incluye los siguientes módulos:

- 📁 **Categorías**: Crear, editar y eliminar categorías de productos.
- 📦 **Productos**: Gestión completa de inventario (altas, bajas, actualizaciones).
- 👤 **Usuarios**: Control de acceso y administración de cuentas de usuario.
- 🏢 **Sucursal**: Configuración y edición de la información de la tienda.
- 💰 **Ventas**: Registro de ventas en tiempo real, con cálculo de totales y control de productos vendidos.

## Tecnologías utilizadas

- **Laravel** – Framework principal para la lógica del servidor y estructura del proyecto.
- **Livewire 3** – Para componentes interactivos en el frontend sin necesidad de escribir JavaScript.
- **Blade** – Sistema de plantillas nativo de Laravel.
- **Base de datos** – Compatible con MySQL o SQLite (según configuración).

## Requisitos del sistema

- PHP 8.1 o superior  
- Composer  
- MySQL o SQLite  
- Node.js y NPM (para compilar assets opcionalmente)

## Instalación rápida

```bash
git clone https://github.com/tuusuario/tu-repo.git
cd tu-repo
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan storage:link
php artisan serve
