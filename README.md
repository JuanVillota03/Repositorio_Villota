# Sistema de Gestión y Venta de Boletas para Conciertos

## Descripción

Aplicación web desarrollada en Laravel para la administración y venta de boletas de conciertos. El sistema permite gestionar usuarios, controlar la disponibilidad de asientos, realizar ventas individuales y masivas, generar tickets y administrar recaudos.

## Características

* Gestión de usuarios y roles.
* Venta individual de boletas.
* Venta masiva de boletas.
* Consulta de reservas.
* Generación y descarga de tickets.
* Envío de tickets por correo electrónico.
* Administración de asientos disponibles y vendidos.
* Control y registro de recaudos.
* Panel administrativo protegido mediante autenticación..

## Tecnologías Utilizadas

* PHP 7.3+
* Laravel 8
* MySQL
* Bootstrap
* JavaScript
* DOMPDF (Generación de PDF)
* Milon Barcode (Generación de códigos de barras)

## Estructura Principal del Proyecto

```text
app/
bootstrap/
config/
database/
public/
resources/
routes/
storage/
tests/
```

## Instalación

### 1. Clonar el repositorio

```bash
git clone <url-del-repositorio>
cd concierto-master
```

### 2. Instalar dependencias

```bash
composer install
```

### 3. Configurar variables de entorno

Copiar el archivo de ejemplo:

```bash
cp .env.example .env
```

Configurar los datos de conexión a la base de datos en el archivo `.env`.

### 4. Generar clave de la aplicación

```bash
php artisan key:generate
```

### 5. Ejecutar migraciones

```bash
php artisan migrate
```

### 6. Ejecutar seeders (opcional)

```bash
php artisan db:seed
```

### 7. Iniciar el servidor

```bash
php artisan serve
```

La aplicación estará disponible en:

```text
http://localhost:8000
```

## Módulos Principales

### Clientes

* Reserva de asientos.
* Consulta de reservas.
* Descarga de tickets.
* Recepción de tickets por correo.

### Administración

* Gestión de usuarios.
* Gestión de ventas.
* Control de asientos.
* Recaudo de pagos.
* Reportes y seguimiento.

## Rutas Relevantes

| Ruta                  | Descripción                  |
| --------------------- | ---------------------------- |
| /                     | Página principal de reservas |
| /consult-reservation  | Consulta de reservas         |
| /form-login           | Inicio de sesión             |
| /system/dashboard     | Panel administrativo         |
| /system/sales         | Gestión de ventas            |
| /system/users         | Gestión de usuarios          |
| /system/collect-money | Gestión de recaudos          |

## Autor

Juan Esteban Villota

## Licencia

<<<<<<< HEAD
Proyecto desarrollado con fines académicos y de aprendizaje.
=======
Proyecto desarrollado con fines académicos y de aprendizaje.
>>>>>>> 41bf9c23844b5a010ee098384da62e9a580b709c
