# SGI Maquetación

[![Netlify Status](https://api.netlify.com/api/v1/badges/7be7c2b4-9747-4a57-bf41-db513d323e33/deploy-status)](https://app.netlify.com/sites/sgi-maquetacion/deploys)

Este proyecto es una maquetación web realizada con [Astro](https://astro.build/) y [TailwindCSS](https://tailwindcss.com/). Puedes ver la versión desplegada [aquí](https://sgi-maquetacion.netlify.app/).

## Descripción

El objetivo de este proyecto es crear una estructura web limpia y eficiente utilizando las tecnologías modernas de Astro y TailwindCSS. Este proyecto sirve como base para futuros desarrollos y prácticas de diseño.

## Tabla de Contenidos

- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Contribución](#contribución)
- [Licencia](#licencia)

## Instalación

Para comenzar a trabajar con este proyecto, sigue estos pasos:

1. Clona el repositorio:

    ```bash
    git clone https://github.com/tu-usuario/sgi-maquetacion.git
    cd sgi-maquetacion
    ```

2. Instala las dependencias:

    ```bash
    npm install
    ```

## Uso

Para iniciar el servidor de desarrollo, utiliza el siguiente comando:

```bash
npm run dev
```

Esto iniciará el servidor en `http://localhost:3000`. Puedes ver los cambios en tiempo real a medida que editas los archivos.

Para construir el proyecto para producción, ejecuta:

```bash
npm run build
```

Esto generará una versión optimizada de la aplicación en la carpeta `dist`.

## Estructura del Proyecto

La estructura del proyecto es la siguiente:

```
.
├── public
│   └── (archivos estáticos como imágenes, fuentes, etc.)
├── src
│   ├── components
│   │   └── (componentes de Astro y TailwindCSS)
│   ├── layouts
│   │   └── (layouts de páginas)
│   ├── pages
│   │   └── (páginas del sitio)
│   └── styles
│       └── (estilos globales y configuraciones de TailwindCSS)
├── package.json
├── astro.config.mjs
└── tailwind.config.js
```

## Contribución

Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios.
4. Haz un commit de tus cambios (`git commit -am 'Agrega nueva funcionalidad'`).
5. Sube tus cambios al repositorio (`git push origin feature/nueva-funcionalidad`).
6. Crea un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

