# Gestion-gym
# Gestión de Gimnasios 🏋️‍♂️

## Descripción del Proyecto
Este proyecto es un sistema de gestión de gimnasios diseñado para facilitar el manejo de clientes, membresías, planes, facturación y notificaciones. Combina una arquitectura backend en **Java Spring Boot** con un frontend construido en **Ionic** y **Vue.js**. La base de datos está configurada en **MySQL** mediante **XAMPP**.

## Características Principales 🌟
- **Gestión de clientes**: Registro, edición y eliminación de información de clientes.
- **Control de membresías**: Creación, asignación y seguimiento de las membresías activas.
- **Facturación**: Emisión de facturas automatizadas para las membresías adquiridas.
- **Notificaciones**: Sistema para enviar alertas o recordatorios a los clientes.
- **Planes de entrenamiento**: Gestión de los planes disponibles en el gimnasio.

## Tecnologías Utilizadas 🛠️

### Backend
- **Lenguaje**: Java  
- **Framework**: Spring Boot  
- **Entorno de desarrollo**: IntelliJ IDEA  

### Frontend
- **Framework**: Ionic + Vue.js  
- **Editor de código**: Visual Studio Code  

### Base de Datos
- **Sistema gestor**: MySQL  
- **Herramienta**: XAMPP  

## Arquitectura del Sistema 🏗️
El sistema utiliza una arquitectura basada en servicios:
- **Backend (API REST)**: Proporciona endpoints para la gestión de datos, creados con Java Spring Boot.
- **Frontend**: Aplicación web interactiva desarrollada con Ionic y Vue.js.
- **Base de datos**: Almacena las entidades principales y sus relaciones en MySQL.

## Entidades Principales 📊
### Cliente
- **Atributos**: Nombre, Apellido, Edad, Dirección, Email, Teléfono.  

### Membresía
- **Atributos**: Fecha de inicio, Fecha de fin, Tipo, Estado, Cliente asociado.  

### Factura
- **Atributos**: Número, Fecha, Total, Cliente asociado.  

### Plan
- **Atributos**: Nombre, Descripción, Duración, Precio.  

### Notificación
- **Atributos**: Mensaje, Tipo, Fecha, Cliente asociado.  

## Requisitos Previos 🔧

### Backend
- Java JDK 11 o superior  
- Maven  
- IntelliJ IDEA (opcional)  

### Frontend
- Node.js  
- Ionic CLI  
- Visual Studio Code  

### Base de Datos
- XAMPP (para MySQL y phpMyAdmin)  

## Instalación y Configuración 🛠️

### Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/nombre-del-repositorio.git
cd nombre-del-repositorio
