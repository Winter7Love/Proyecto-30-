# Gestión de Tareas - Proyecto React

Este proyecto es una **aplicación web** para la **gestión de tareas**, creada con **React** y **Vite**. Está diseñada principalmente para ayudar a los estudiantes de ingeniería a organizar sus proyectos, laboratorios y otras actividades académicas. La aplicación permite agregar, editar, eliminar y marcar tareas como completadas. Además, incluye un sistema de filtrado y ordenación de tareas, lo que facilita una gestión eficiente de las actividades diarias.

## Comenzando 🚀

Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas.

Mira **Deployment** para conocer cómo desplegar el proyecto.

### Pre-requisitos 📋

Qué cosas necesitas para instalar el software y cómo instalarlas:

- **Node.js** y **npm** (gestor de paquetes).
- **Git** para clonar el repositorio.

Si no tienes **Node.js** y **npm** instalados, puedes descargar e instalar **Node.js** desde su sitio web oficial: [https://nodejs.org](https://nodejs.org).

### Instalación 🔧

Una serie de ejemplos paso a paso que te dice lo que debes ejecutar para tener un entorno de desarrollo ejecutándose.

1. Clona el repositorio en tu máquina:

    ```bash
    git clone https://github.com/usuario/proyecto-gestion-tareas.git
    cd proyecto-gestion-tareas
    ```

2. Instala las dependencias necesarias:

    ```bash
    npm install
    npm install @types/react @types/react-dom
    npm install react-router-dom @fortawesome/react-fontawesome @fortawesome/free-solid-svg-icons
    npm install react-bootstrap bootstrap
    npm install recharts react-icons
    ```

3. Inicia el servidor de desarrollo:

    ```bash
    npm run dev
    ```

La aplicación estará disponible en `http://localhost:3000`.

## Uso 📄

### Componentes principales:

- **NavBar**: Barra de navegación que permite acceder a las diferentes secciones de la aplicación.
- **Home**: Página de inicio con un resumen de las funcionalidades de la aplicación.
- **Tasks**: Página de gestión de tareas donde los usuarios pueden agregar, editar y eliminar tareas.
- **About**: Información sobre el propósito del proyecto y su equipo.
- **ContactForm**: Formulario de contacto para enviar consultas.

### Rutas de la aplicación:

- `/` → Página de inicio (Home)
- `/contactos` → Página de contacto (ContactForm)
- `/gestion-tareas` → Página de gestión de tareas (Tasks)
- `/acerca-de` → Página de información sobre el proyecto (About)
- `*` → Página de error 404

### Funcionalidades 🌟

- **Agregar tarea**: Permite al usuario agregar nuevas tareas, con detalles como título, descripción, fecha, prioridad y categoría.
- **Editar tarea**: Las tareas existentes pueden ser editadas.
- **Eliminar tarea**: Las tareas pueden ser eliminadas.
- **Filtrado de tareas**: Filtra las tareas por estado (pendientes, completadas).
- **Ordenación de tareas**: Permite ordenar las tareas por fecha o prioridad.
- **Persistencia local**: Las tareas se guardan en el almacenamiento local del navegador para persistencia entre sesiones.

### Contribuciones 🖇️

Las contribuciones son bienvenidas. Si tienes ideas, sugerencias o encuentras algún error, por favor abre un **issue** o envía un **pull request**.

1. Haz un fork de este repositorio.
2. Crea una rama para tu funcionalidad (`git checkout -b mi-nueva-funcionalidad`).
3. Haz commit de tus cambios (`git commit -am 'Agregando nueva funcionalidad'`).
4. Haz push a la rama (`git push origin mi-nueva-funcionalidad`).
5. Abre un Pull Request.

### Pruebas ⚙️

Las pruebas para este proyecto pueden incluir pruebas unitarias para la lógica de las tareas (si es necesario), y pruebas visuales para asegurar que los componentes se comporten correctamente en la interfaz de usuario.

### Despliegue 📦

Este proyecto está configurado para ser desplegado en plataformas como **Vercel** o **Netlify**. Simplemente conecta tu repositorio en la plataforma de despliegue y sigue las instrucciones para un despliegue rápido y fácil.

### Herramientas y Librerías utilizadas 🛠️

- **React**: Para la interfaz de usuario.
- **Vite**: Para la construcción rápida de la aplicación.
- **React Router Dom**: Para la gestión de rutas.
- **React Bootstrap**: Para los componentes visuales.
- **FontAwesome**: Para los iconos.
- **Recharts**: Para la visualización de datos (si se utiliza en futuras versiones).

### Autores ✒️

- **Jhon Ordoñez**: Desarrollo frontend y experiencia de usuario.
- **Emily Quispe**: Arquitectura de la aplicación y bases de datos.
- **Evelyn Capcha**: Diseño de flujos de trabajo para gestión de proyectos estudiantiles.

### Licencia 📄

Este proyecto está bajo la Licencia MIT - mira el archivo [LICENSE.md](LICENSE.md) para más detalles.
