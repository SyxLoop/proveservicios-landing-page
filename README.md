# Landing page de Proveedora de Servicios para Automotores S.A

En la landing page de ProveServicios S.A, se detallan la misión, visión, los servicios, las políticas y la forma de comunicarse con la compañia.


## Instalación del proyecto
```sh
pnpm install
```


## Estructura del proyecto

Dentro del proyecto se podrán observar las siguientes carpetas y archivos:

```text
/
├── public/
│   └── favicon.svg
├── src
│   ├── assets
│   │   └── astro.svg
│   ├── components
│   │   └── HeroSection.astro
|   |   └──Navbar.astro
│   ├── layouts
│   │   └── Layout.astro
│   ├── pages
│   |   └── index.astro
|   └──styles
|       └── global.css
└── package.json
```

## Comandos

Todos los comandos que se pueden ejecutar en el proyecto desde una terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Instala dependencias                            |
| `pnpm dev`             | Inicia un servidor local en `localhost:4321`      |
| `pnpm build`           | Construye el sitio en producción en la carpeta `./dist/`          |
| `pnpm preview`         | Previzualiza la build localmente antes de hacer deploy    |
| `pnpm astro ...`       | Ejecuta comandos CLI como `astro add`, `astro check` |
| `pnpm astro -- --help` | Obten ayuda usando el CLI de Astro CLI                     |
