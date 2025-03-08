# Desafio Flexbox

## Descripción
Este proyecto es una aplicación desarrollada con **HTML, CSS y Flexbox**. Su diseño está inspirado en interfaces de mensajería, permitiendo a los usuarios iniciar conversaciones y explorar perfiles de contactos de manera intuitiva.

## Tecnologías utilizadas
- **HTML5**: Para la estructura de la página.
- **CSS3**: Para el estilo y apariencia visual.
- **Flexbox**: Para la distribución y alineación de los elementos.
- **Google Fonts**: Para la tipografía.
- **Font Awesome**: Para los iconos.

## Características principales
- Barra lateral con la lista de contactos.
- Sección principal con información y guía para iniciar una conversación.
- Diseño responsivo utilizando Flexbox.
- Botón de "Nuevo Chat" para iniciar nuevas conversaciones.

## Estructura del proyecto
```
Networking-App/
│-- index.html
│-- assets/
│   │-- css/
│   │   │-- styles.css
│   │-- img/
│-- README.md
```

## Uso de Flexbox
Se implementó **Flexbox** para organizar la interfaz de usuario de manera eficiente:
- `.container`: Contenedor principal con `display: flex;` para dividir la barra lateral y la sección principal.
- `.sidebar`: Sección lateral con `flex-direction: column;` para alinear los elementos verticalmente.
- `.main-user`: Contenedor superior con `display: flex; justify-content: space-between;` para alinear avatar e iconos.
- `.user-item`: Cada contacto usa `display: flex; align-items: center;` para mantener la imagen y la información alineadas.
- `.main-content`: Sección central con `display: flex; align-items: center; justify-content: center;` para centrar el contenido.

## Instalación y uso
1. Clona el repositorio:
   ```sh
   git clone https://github.com/wiimri/flexbox.git
   ```
2. Abre `index.html` en tu navegador.

## Autor
Desarrollado por **Williams Arias** para **Full Stack JavaScript - G92** en **Desafío Latam**.
