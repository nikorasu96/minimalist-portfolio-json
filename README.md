<div align="center">
<img src="/public/favicon.svg" height="90px" width="auto" /> 
<h2>
    Resumen minimalista maquetado para web y pdf
</h2>
<p>
Esquema del JSON de CV de <a href="https://jsonresume.org/schema/">jsonresume.org</a>
</p>

<p>
Basado en el diseño de <a href="https://github.com/BartoszJarocki/cv">Bartosz Jarocki</a>
</p>

<p>
Inspirado y desarrollado siguiendo el tutorial de <a href="https://github.com/midudev/minimalist-portfolio-json">midudev</a>
</p>

</div>

<div align="center">
    <a href="#🚀-empezar">
        Empezar
    </a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="#🧞-comandos">
        Comandos
    </a>
   
</div>

<p></p>

<div align="center">

![Astro Badge](https://img.shields.io/badge/Astro-BC52EE?logo=astro&logoColor=fff&style=flat)
![GitHub stars](https://img.shields.io/github/stars/nikorasu96/minimalist-portfolio-json?style=flat)
![GitHub issues](https://img.shields.io/github/issues/nikorasu96/minimalist-portfolio-json?style=flat)
![GitHub forks](https://img.shields.io/github/forks/nikorasu96/minimalist-portfolio-json?style=flat)
![GitHub PRs](https://img.shields.io/github/issues-pr/nikorasu96/minimalist-portfolio-json?style=flat)

</div>

<img src="/src/img/portada.png"></img>

## 🛠️ Stack

- [**Astro**](https://astro.build/) - El framework web de la nueva época.
- [**Typescript**](https://www.typescriptlang.org/) - JavaScript con sintaxis de tipado.
- [**Ninja Keys**](https://github.com/ssleptsov/ninja-keys) - Menu desplegable con atajos de teclado hecho en puro Javascript.

## 🚀 Empezar

### 1. Usa este [repo](https://github.com/nikorasu96/minimalist-portfolio-json) como _template_ de un proyecto de Astro

- Yo uso [pnpm](https://pnpm.io/installation) como gestor de dependencias y empaquetador.

```bash
# Activa pnpm en MacOS, WSL & Linux:
corepack enable
corepack prepare pnpm@latest --activate

# Inicializa el proyecto
pnpm create astro@latest -- --template midudev/minimalist-portfolio-json
```

### 2. Añade tu contenido:

Edita el archivo `cv.json` para crear tu propio Portafolio/CV imprimible.

### 3. Lanza el servidor de desarrollo:

```bash
# Disfruta del resultado
pnpm dev
```

1. Abre [**http://localhost:4321**](http://localhost:4321/) en tu navegador para ver el resultado 🚀

## 🧞 Comandos

|     | Comando         | Acción                                                                       |
| :-- | :-------------- | :--------------------------------------------------------------------------- |
| ⚙️  | `dev` o `start` | Lanza un servidor de desarrollo local en `localhost:4321`.                   |
| ⚙️  | `build`         | Comprueba posibles errores y hace un empaquetado de producción en `./dist/`. |
| ⚙️  | `preview`       | Vista previa en local `localhost:4321`                                       |

## Licencia

Este proyecto está bajo la licencia [MIT](/LICENSE.txt).  
Creado siguiendo el tutorial de [**midudev**](https://midu.dev), donde se explica cómo crear un portafolio minimalista con JSON y Astro.
