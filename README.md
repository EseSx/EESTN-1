# EESTN-1
Este repositorio contiene el **código fuente del front-end** de la página web de la escuela.

## Contenidos
- [Descripción](#descripción)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura de carpetas](#estructura-de-carpetas)
- [Contribución](#contribución)

## Descripción
Este proyecto es una **página institucional** para la **Escuela de Educación Secundaria Técnica N°1**, iniciada en el año 2025 por el curso de 7° 5ta de ese momento.  

El objetivo del proyecto es mantenerse **vigente y en desarrollo por el mayor tiempo posible**, funcionando como un medio para:

- Publicar noticias.
- Promocionar la escuela.

**Tecnologías principales:** React, CSS.

## Instalación
1. Clonar el repositorio:
   
   ```bash
   git clone https://github.com/EseSx/EESTN-1.git
   ```
2. Instalar dependencias:
   ```bash
   npm install
   ```
3. Ejecutar la app:
   ```bash
   npm start

## Uso
- Al abrir el proyecto en **localhost** desde el navegador, podrás explorar las diversas páginas, visualizando e interactuando con todos los componentes.
- **Secciones principales:**
  - **Home:** Inicio, Historia de la escuela, Orientaciones, Noticias.
  - **Páginas informativas:** Cada orientación de la escuela.
  - **Expotec:** Sección dedicada a la exposición realizada cada año por la escuela y los propios alumnos.
  - **Admin:** Panel para gestionar noticias.

## Estructura de carpetas
```text
Escuela_Tecnica_N°1/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Carrusel.jsx // Este componente tiene un Prop que recibe las imágenes de cada página.
│   │   ├── Encabezado.jsx // Este componente contiene el encabezado que se va a usar en varias páginas.
│   │   └── MenuDesplegable.jsx // Este componente contiene el menú desplegable usado en la mayor parte de las páginas.
│   │   └── Noticias.jsx // Este componente contiene el extenso apartado de noticias y su lógica, que se va a usar en la página principal.
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── CicloBasico.jsx
│   │   ├── Programacion.jsx
│   │   ├── Electromecanica.jsx
│   │   ├── Quimica.jsx
│   │   └── EPS.jsx
│   ├── styles/
│   │   ├── App.css
│   │   ├── Noticias.css
│   │   └── Header.css
│   ├── App.jsx
│   └── index.jsx
├── package.json
└── README.md
```

## Contribución
1. Hacer un fork del repositorio.
2. Crear una rama nueva:
   ```bash
   git checkout -b nombre-rama
3. Hacer commits claros y descriptivos.
4. Abrir un Pull Request.
