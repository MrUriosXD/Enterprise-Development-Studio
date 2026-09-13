# Enterprise Development Studio

> Entorno web de desarrollo para editar, visualizar y probar proyectos desde una interfaz centralizada.

## 📌 Descripción

**Enterprise Development Studio** es un entorno de desarrollo web experimental creado para centralizar tareas habituales de creación y prueba de interfaces en una única herramienta.

El proyecto combina un editor de código con una vista previa integrada, controles de visualización y herramientas orientadas a facilitar el desarrollo frontend directamente desde el navegador.

## ✨ Características

- 🧑‍💻 **Editor integrado** para trabajar directamente con el código.
- 🔢 **Numeración de líneas** y resaltado visual de la línea activa.
- 👁️ **Vista previa integrada** para comprobar el resultado del código.
- 📱 **Simulación responsive** con modos **Desktop, Tablet y Mobile**.
- 🔄 **Orientación vertical y horizontal** para dispositivos compatibles.
- ↔️ **Paneles redimensionables** para ajustar el espacio entre editor y vista previa.
- 🔍 **Búsqueda dentro del editor**.
- 🖥️ **Modo de vista previa a pantalla completa**.
- 🌙 **Tema oscuro y tema claro**.
- 🌐 **Selector de idioma/interfaz**.
- 📐 **Indicador de dimensiones** durante la previsualización.
- 🔔 **Sistema de notificaciones** para acciones y estados.
- 🎨 **Interfaz inspirada en herramientas modernas de desarrollo**.

## 🖥️ Interfaz

La aplicación está organizada en dos áreas principales:

```text
┌──────────────────────────────────────────────────────────────┐
│                     Barra de herramientas                    │
├──────────────────────────────┬───────────────────────────────┤
│                              │                               │
│        Editor de código      │       Vista previa            │
│                              │                               │
│        1  <!DOCTYPE...      │       ┌───────────────┐       │
│        2  <html>             │       │   Website     │       │
│        3  ...                │       │   Preview     │       │
│                              │       └───────────────┘       │
│                              │                               │
├──────────────────────────────┴───────────────────────────────┤
│                         Barra de estado                      │
└──────────────────────────────────────────────────────────────┘
```

El separador central permite modificar dinámicamente el tamaño de cada panel para trabajar con una distribución más cómoda.

## 📱 Modos de visualización

La vista previa permite comprobar el resultado en diferentes tamaños de pantalla:

| Modo | Resolución de referencia |
|---|---:|
| 🖥️ Desktop | Adaptativa |
| 📱 Tablet | 768 × 1024 px |
| 📱 Tablet horizontal | 1024 × 600 px |
| 📱 Mobile | 375 × 667 px |
| 📱 Mobile horizontal | 667 × 375 px |

## 📂 Estructura

Actualmente el proyecto mantiene una estructura mínima:

```text
Enterprise-Development-Studio/
├── index.html    # Aplicación web principal
└── README.md     # Documentación del proyecto
```

La aplicación está actualmente concentrada en `index.html`, incluyendo la interfaz, estilos y lógica necesaria para el funcionamiento del entorno.

## 🚀 Uso

La versión actual no requiere instalación ni dependencias externas.

1. Clona o descarga el repositorio.
2. Abre `index.html` en un navegador moderno.
3. Utiliza el editor para trabajar con el código.
4. Comprueba el resultado desde la vista previa.
5. Cambia entre los diferentes modos de dispositivo según sea necesario.

También puede ejecutarse mediante cualquier servidor web local.

## 🛠️ Tecnologías

- **HTML5** — estructura de la aplicación.
- **CSS3** — interfaz, temas, paneles y diseño responsive.
- **JavaScript** — interacción del editor, vista previa y herramientas del entorno.

## 🎯 Objetivos

- Centralizar herramientas de desarrollo en una interfaz propia.
- Crear una base extensible para futuras funciones.
- Facilitar las pruebas rápidas de interfaces web.
- Mantener una experiencia similar a un pequeño IDE dentro del navegador.
- Evolucionar progresivamente hacia un entorno de desarrollo más completo.

## 📌 Estado

**🟡 En desarrollo — fase experimental**

El proyecto se encuentra en una etapa inicial. La arquitectura y las funcionalidades pueden cambiar a medida que se incorporen nuevas herramientas.

## 🔮 Próximas posibilidades

- 📁 Gestión de proyectos y archivos.
- 💾 Guardado y carga de proyectos.
- 🗂️ Explorador de archivos integrado.
- 🧩 Sistema de módulos o extensiones.
- ⚙️ Configuración avanzada del entorno.
- 🧪 Herramientas adicionales para pruebas y depuración.
- 📦 Exportación de proyectos.

## 📄 Licencia

La licencia del proyecto se definirá cuando alcance una versión estable.

---

**Enterprise Development Studio** · Desarrollo experimental de un entorno web de desarrollo centralizado.
