# ☀️ Solaire of Astora | Frontend Web

> *"El sol es un astro maravilloso. ¡Ojalá yo pudiera ser tan incandescente!"* — Solaire de Astora

Este proyecto es una página web moderna, interactiva y de fantasía oscura desarrollada como parte de una mentoría práctica de Frontend con **Astro**. Está inspirada en la atmósfera inmersiva de *Dark Souls*, rindiendo homenaje al caballero Solaire de Astora.

---

## 🛠️ Tecnologías y Herramientas Utilizadas

* **[Astro](https://astro.build/)**: Framework web moderno enfocado en el rendimiento.
* **TypeScript (Strict Mode)**: Para garantizar un tipado estático seguro y robusto.
* **CSS3 Moderno**: 
  * Variables CSS (`:root`) para la gestión de paletas temáticas.
  * Sistemas **HEX**, **RGB/RGBA** y **HSL** para lograr brillos y sombras dinámicas.
  * **Flexbox** y **CSS Grid** para estructuras adaptables (*responsive*).
* **JavaScript (Vanilla)**: 
  * API nativa **Intersection Observer** para animaciones fluidas al hacer scroll.
* **Git & GitHub**: Control de versiones profesional aplicando *Conventional Commits*.

---

<p align="center">
  <img src="https://img.shields.io/badge/Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white" alt="Astro">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License MIT">
</p>

---

## ✨ Características Principales

1. **Sección Hero Inmersiva**: Video de fondo en bucle con una capa de contraste (*overlay*) y tipografías épicas.
2. **Efectos de Brillo (Glow)**: Uso avanzado de sombras (`text-shadow` y `box-shadow`) para simular fuentes de luz.
3. **Animaciones de Scroll**: Contenido que emerge suavemente de las sombras a medida que el usuario navega.
4. **Cuadrícula de Reliquias**: Tarjetas interactivas con efectos de elevación en 3D (`translateY`) mediante CSS Grid.
5. **Redirecciones Seguras**: Enlaces optimizados hacia plataformas externas con atributos de seguridad (`rel="noopener noreferrer"`).

---

## 🚀 Cómo Ejecutar el Proyecto Localmente

Asegúrate de tener instalado [Node.js](https://nodejs.org/) en tu computadora. Luego, ejecuta los siguientes comandos en tu terminal:

```bash
# 1. Clona el repositorio
git clone [https://github.com/tu-usuario/solaire-astora-web.git](https://github.com/tu-usuario/solaire-astora-web.git)

# 2. Entra a la carpeta del proyecto
cd solaire-astora-web

# 3. Instala las dependencias
npm install

# 4. Inicia el servidor de desarrollo
npm run dev

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
```

El sitio web estará disponible en http://localhost:4321.

Praise the Sun! ☀️

# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src
│   ├── assets
│   │   └── astro.svg
│   ├── components
│   │   └── Welcome.astro
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |


