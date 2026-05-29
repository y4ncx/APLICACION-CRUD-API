# 🏗️ Gestor de Edificios (ZenFi Architecture)

¡Bienvenido al repositorio oficial del **Gestor de Edificios**! Una aplicación móvil diseñada para la administración eficiente, consulta y gestión de datos de propiedad horizontal, construida con una arquitectura robusta y escalable.

## 🚀 Sobre el Proyecto
Esta aplicación permite gestionar información detallada de edificios, incluyendo pisos, unidades, servicios y costos de administración. Está pensada para facilitar el control operativo tanto para administradores como para propietarios.

## 🛠️ Stack Tecnológico
* **Desarrollo:** Kodular (Lógica basada en bloques).
* **Backend:** [Supabase](https://supabase.com/) (PostgreSQL).
* **API:** RESTful API generada automáticamente por Supabase.
* **Almacenamiento:** Base de datos relacional en la nube.
* **Autenticación:** Sistema de gestión de usuarios integrado.

## ✨ Características Principales
- [x] **CRUD Completo:** Crear, Leer, Actualizar y Eliminar edificios.
- [x] **Gestión de Usuarios:** Registro e inicio de sesión seguro.
- [x] **Búsqueda Inteligente:** Filtros dinámicos por ID y nombre.
- [x] **Interfaz Minimalista:** Diseñada para una experiencia de usuario fluida.



## 📋 Arquitectura de la Base de Datos (Supabase)
El proyecto utiliza tablas clave para mantener la integridad de los datos:
* `edificios`: Contiene las especificaciones técnicas y financieras.
* `usuarios`: Gestiona las credenciales y perfiles de acceso.

## 🔧 Instalación y Configuración
1. Importa el archivo `.aia` en Kodular Creator.
2. Configura tu `API_KEY` y `URL_BASE` en las variables globales.
3. Asegúrate de tener los permisos de Internet habilitados en el manifiesto.
4. Conecta tu base de datos en Supabase con los permisos de lectura/escritura definidos.

## 👨‍💻 Autor
**Jassir Said Yances**
*Software Developer*

---
*Hecho con Monster y bloques de lógica.*
