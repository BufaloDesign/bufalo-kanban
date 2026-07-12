# Búfalo Studio | Panel de Revisión de Cliente

Este proyecto es un tablero Kanban minimalista y premium diseñado específicamente para la agencia de desarrollo web **Búfalo Studio**, pensado para ser utilizado en sesiones de revisión en vivo con clientes.

## 🎨 Características de Diseño (UI/UX)
* **Paleta Minimalista**: Basada en blanco puro (`#FFFFFF`) para fondos, negro intenso (`#000000`) para tipografías y acentos principales, y grises sutiles (`#F3F4F6`, `#E5E7EB`) para estructurar columnas y tarjetas.
* **Tipografía Outfit**: Estilo geométrico moderno y limpio importado de Google Fonts.
* **Foco en Experiencia**: Tarjetas con bordes redondeados y sombras suaves (estilo Apple/Notion), animaciones fluidas y micro-interacciones de hover.
* **Sección Destacada**: La columna de **Revisión del Cliente** está acentuada con un borde e indicador especial de color negro para centrar la atención del cliente de manera profesional.

## 🛠️ Funcionalidad Técnica
* **Drag and Drop Nativo**: Reordenamiento de tarjetas fluido tanto entre columnas como dentro de la misma columna usando la API nativa de JavaScript.
* **Persistencia Local (LocalStorage)**: Todas las tareas creadas, editadas o movidas se guardan de forma local en el navegador, asegurando que los cambios no se pierdan al actualizar la página.
* **Gestión de Tareas Completa**: Modal personalizado (diseñado desde cero con Tailwind CSS, sin usar ventanas emergentes genéricas de JavaScript) que permite:
  * Crear nuevas tareas asignando título, descripción y etiquetas opcionales.
  * Editar los textos de tareas existentes.
  * Eliminar tareas de forma intuitiva.
* **Personalización**: Permite hacer clic en el nombre del proyecto en la cabecera para cambiar el nombre y ajustarlo al cliente actual en sesión.
* **Responsivo**: Adaptable a cualquier pantalla de escritorio (como iMac) y con desplazamiento horizontal automático en pantallas de dispositivos móviles.

## 🚀 Cómo Empezar a Usarlo
Dado que es una aplicación de un solo archivo, es extremadamente fácil de ejecutar y compartir:

1. **Localmente**: Simplemente haz doble clic en el archivo [index.html](file:///data/data/com.termux/files/home/bufalo-kanban/index.html) para abrirlo en cualquier navegador web moderno.
2. **Despliegue Rápido (GitHub Pages)**:
   * Sube el archivo `index.html` a un repositorio público en GitHub.
   * Ve a *Settings > Pages* en el repositorio de GitHub.
   * Selecciona la rama `main` y guarda para desplegar el sitio en vivo de forma gratuita.

---
Diseñado y desarrollado para **Búfalo Studio** &copy; 2026.
