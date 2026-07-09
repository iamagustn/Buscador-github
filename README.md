# Buscador de Usuarios de GitHub

[Ver demo en vivo](https://fckagstn.github.io/Buscador-github/)

## Descripción

Este proyecto es una aplicación web que permite buscar usuarios de GitHub mediante su nombre de usuario. La aplicación consume la API pública de GitHub para obtener información del usuario y mostrarla de forma clara y organizada en una tarjeta con un diseño sencillo.

Su objetivo es practicar el consumo de APIs con JavaScript, el manejo de peticiones asíncronas y la creación dinámica de elementos en el DOM.

## Características

- Buscar un usuario de GitHub por su nombre de usuario.
- Validar que el campo de búsqueda no esté vacío.
- Mostrar un mensaje mientras se realiza la consulta a la API.
- Mostrar una tarjeta con la información del usuario encontrado.
- Visualizar:
  - Avatar del usuario.
  - Nombre.
  - Biografía.
  - Número de repositorios públicos.
  - Número de seguidores.
- Mostrar un mensaje cuando el usuario no existe.
- Manejar errores de conexión o fallos durante la consulta.

## Tecnologías usadas

- **HTML5**
- **JavaScript (ES6+)**
- **Tailwind CSS** (cargado mediante CDN)
- **GitHub REST API**
  - `https://api.github.com/users/`

## Cómo usarlo

1. Clona este repositorio o descarga el archivo del proyecto.
2. Abre el archivo `index.html` en cualquier navegador moderno.
3. Escribe el nombre de un usuario de GitHub en el campo de búsqueda.
4. Haz clic en el botón **Buscar**.
5. La aplicación mostrará la información del usuario si existe.

No es necesario instalar dependencias ni ejecutar un servidor, ya que el proyecto funciona directamente desde el navegador utilizando la API pública de GitHub.

## Mejoras conocidas / futuras

- Actualmente **Tailwind CSS** se carga mediante **CDN**, lo cual es una solución adecuada para proyectos de aprendizaje, prototipos y desarrollo rápido.
- Para una versión orientada a producción sería recomendable instalar Tailwind CSS mediante su sistema de compilación (`npm`) para generar únicamente las clases utilizadas, reducir el tamaño del CSS y mejorar el rendimiento de la aplicación.
- Permitir realizar la búsqueda al presionar la tecla **Enter**.