# Laboratory Management System – Angular

Aplicación web para la **gestión interna de un laboratorio clínico**, desarrollada como proyecto en equipo durante mis prácticas de **Desarrollo de Aplicaciones Web (DAW)**.

Este sistema permite gestionar muestras, inventario y usuarios, utilizando **Angular** para el frontend y **Supabase** como backend (autenticación + base de datos).

> 💡 Este repositorio es un fork del proyecto original del equipo, enfocado en mostrar mi aportación técnica y la arquitectura general de la aplicación.

---

## 🚀 Funcionalidades principales

- 🔐 Autenticación de usuarios vía Supabase  
- 🧪 Gestión de muestras: crear, editar, listar y eliminar (CRUD completo)  
- 📦 Gestión de inventario y material del laboratorio  
- 👥 Gestión de usuarios internos  
- 📄 Formularios reactivos con validaciones  
- 🔄 Servicios Angular para comunicación con Supabase  
- 📊 Listados con filtros básicos y estructura modular  

---

## 🛠️ Tecnologías utilizadas

| Categoría | Tecnologías |
|----------|-------------|
| **Framework** | Angular 17+ |
| **Lenguaje** | TypeScript |
| **UI / Estilos** | CSS, Angular Material, Font Awesome |
| **Backend / BaaS** | Supabase |
| **Herramientas** | Git, GitHub, Angular CLI |

---

## 🧩 Arquitectura y estructura del proyecto

```txt
src/
 ├─ app/
 │   ├─ core/           # Servicios generales, guards, interceptores
 │   ├─ modules/        # Módulos funcionales: muestras, inventario, usuarios...
 │   ├─ shared/         # Componentes reutilizables
 │   ├─ app-routing/    # Configuración de rutas
 │   └─ app.component.* # Componente principal
 ├─ assets/             # Imágenes y recursos
 └─ environments/       # Configuración de entornos (dev/prod)
