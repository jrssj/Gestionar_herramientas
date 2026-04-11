# 🛠️ Sistema de Gestión de Herramientas 

Este proyecto es una aplicación modular desarrollada en Python diseñada para organizar el flujo de trabajo de préstamos e inventario. El sistema utiliza una arquitectura basada en módulos funcionales.

## 📁 Estructura del Proyecto

El código se organiza en archivos independientes para facilitar el mantenimiento y la escalabilidad:

### 👤 Gestión de Personas (`gestionar_personas.py`)
Maneja la lógica del personal interno del sistema.
* `registrar_persona()`: Añade nuevos usuarios.
* `eliminar_persona()`: Remueve registros del sistema.
* `actualizar_persona()`: Modifica datos existentes.
* `listar_personas()`: Muestra el catálogo completo de personal.

### 👥 Gestión de Clientes (`gestionar_cliente.py`)
Controla la información de los beneficiarios externos.
* Posee una estructura homóloga a la de personas (Registro, Eliminación, Actualización y Listado).

### 🔧 Gestión de Herramientas (`gestionar_herramienta.py`)
Administra el inventario físico.
* Incluye funciones estándar de CRUD (Crear, Leer, Actualizar, Borrar).
* **Función Especial:** `cantidad_herramientas()` para obtener métricas rápidas del stock.

### 📑 Gestión de Préstamos (`gestionar_prestamos.py`)
El módulo encargado de vincular las herramientas con los clientes y las personas responsables.

---

## 🌿 Flujo de Trabajo (Git)

Para el desarrollo de este proyecto se utiliza el siguiente esquema de ramas:

1.  **`main`**: Contiene la versión estable y funcional.
2.  **`feature/rama_funcionalidad`**: Rama dedicada a la creación y prueba de nuevos módulos antes de ser integrados al núcleo.

---

## 💻 Ejecución

Para probar la estructura actual, puedes ejecutar cualquiera de los módulos individualmente para verificar la respuesta de las funciones:
## 📫 Contacto

¿Dudas o sugerencias? Puedes escribirme a:

- 📧 jr8465207@gmail.com


