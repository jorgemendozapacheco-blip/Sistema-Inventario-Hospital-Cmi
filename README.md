# 🏥 Sistema Inteligente de Inventario - CMI José Carlos Mariátegui

![Estado](https://img.shields.io/badge/Estado-Terminado-success)
![Tecnología](https://img.shields.io/badge/Backend-PHP-blue)
![Base de Datos](https://img.shields.io/badge/DB-MySQL-orange)
![Dispositivos](https://img.shields.io/badge/Soporte-Lector_Código_Barras-red)

> **Desarrollado por:** [Jorge Eduardo Mendoza Pacheco](https://github.com/jorgemendozapacheco-blip)

## 🎬 Demo del Sistema

Haz clic en la imagen para ver el sistema funcionando (incluye escaneo de código de barras y gestión PECOSA):

<a href="https://www.youtube.com/watch?v=cUUAkM4pXTY" target="_blank">
 <img src="https://img.youtube.com/vi/cUUAkM4pXTY/maxresdefault.jpg" alt="Ver Video Demo del Sistema de Inventario" width="800" style="border: 2px solid #ddd; border-radius: 8px;" />
</a>



## 📄 Descripción del Proyecto

Este sistema web fue desarrollado para modernizar la gestión logística del **Centro Materno Infantil José Carlos Mariátegui**. 

El objetivo principal fue migrar de procesos manuales en Excel a una plataforma centralizada que permite el control total de suministros médicos y administrativos, integrando hardware externo (lectores de código de barras) y digitalización de documentos oficiales (PECOSA).

## 🚀 Características Principales (Vistas en el Video)

### 1. 🔐 Seguridad y Acceso
* **Login Seguro:** Sistema de autenticación encriptada para usuarios y administradores.
* **Gestión de Sesiones:** Protección de rutas y cierre de sesión seguro.

### 2. 📦 Gestión de Inventario
* **Importación Masiva:** Carga de inventarios completos desde archivos **Excel** en segundos (como se ve en el video).
* **CRUD Completo:** Agregar, editar y eliminar productos con interfaz intuitiva.
* **Alertas:** Indicadores visuales de estado.

### 3. 🔫 Tecnología de Escaneo (Barcode)
* **Integración de Hardware:** Uso de lectores de código de barras físicos para búsquedas instantáneas.
* **Escaneo Rápido:** Localización de productos en el almacén simplemente escaneando la etiqueta física.
* **Registro por Escaneo:** Alta de nuevos productos usando el lector.

### 4. 📄 Gestión Documental (PECOSA)
* **Digitalización:** Módulo dedicado para subir y administrar los Pedidos de Comprobante de Salida (PECOSA).
* **Visualización:** Vista previa de documentos (PDF/Imágenes) directamente en el navegador.
* **Trazabilidad:** Vinculación de documentos oficiales con los movimientos de inventario.

### 5. 📊 Dashboard y Reportes
* **Métricas en Tiempo Real:** Visualización de conteos de productos, categorías y alertas.
* **Power BI:** Integración para análisis de datos avanzados y gráficos de antigüedad de productos.

---

## 🛠️ Stack Tecnológico

| Componente | Tecnología |
| :--- | :--- |
| **Backend** | PHP 8.x (Nativo) |
| **Base de Datos** | MySQL / MariaDB |
| **Frontend** | HTML5, CSS3, Bootstrap 5 |
| **Servidor Local** | XAMPP (Apache) |
| **Hardware** | Lector de Código de Barras USB |

## 🔧 Instalación Local

Si deseas probar el código fuente:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/jorgemendozapacheco-blip/Sistema-Inventario-Hospital-Cmi.git](https://github.com/jorgemendozapacheco-blip/Sistema-Inventario-Hospital-Cmi.git)
    ```
2.  **Base de Datos:**
    * Importar el archivo `.sql` (ubicado en la carpeta `db/`) en phpMyAdmin.
3.  **Configuración:**
    * Configurar las credenciales en `db.php` o `conexion.php`.
4.  **Ejecución:**
    * Mover la carpeta a `C:/xampp/htdocs/` y abrir `http://localhost/nombre-carpeta`.

---
© 2025 - Jorge Mendoza Pacheco | Ingeniero de Sistemas
