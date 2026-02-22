# Meeti

Clon de Meetup construido con Bootstrap 5 y SASS. Este proyecto resume lo trabajado en el sitio: una landing moderna, limpia y totalmente responsive, con secciones completas, jerarquía visual clara y estilos organizados en una arquitectura SASS mantenible.

<p align="center">
  <img src="https://img.shields.io/badge/ESTADO-COMPLETADO-brightgreen?style=social&logo=Bootstrap" alt="Estado del proyecto">
  <img src="https://img.shields.io/badge/BOOTSTRAP-5.x-7952B3?style=social&logo=bootstrap" alt="Bootstrap 5">
  <img src="https://img.shields.io/badge/SASS-1.x-CC6699?style=social&logo=sass" alt="SASS">
</p>

---

## 🧭 Panorama

- Objetivo: practicar layout, grilla y componentes con Bootstrap 5 y SASS.
- Resultado: landing lista para portafolio con jerarquía visual clara.
- Estilos: SASS modular con salida compilada y versión optimizada.

## ✨ Caracteristicas clave

- Hero con llamada a la acción y mensaje principal para captar atención.
- Sección de funcionamiento y beneficios con explicación breve.
- Listado de eventos con cards y detalles visibles a simple vista.
- Bloque de descarga de app con tiendas destacadas.
- Footer con navegación y enlaces secundarios organizados.

## 🧰 Tecnologias

- HTML5
- Bootstrap 5
- SASS
- PurgeCSS

## 🗂️ Estructura del proyecto

```
.
├── build/
│   └── css/
│       ├── meeti.css
│       └── style.css
├── img/
├── js/
│   └── bootstrap.bundle.min.js
├── src/
│   └── scss/
│       ├── _custom.scss
│       ├── style.scss
│       ├── contenido/
│       │   ├── _eventos.scss
│       │   └── _index.scss
│       └── header/
│           ├── _header.scss
│           └── _index.scss
├── index.html
├── package.json
└── README.md
```

## ⚙️ Scripts

| Script                  | Descripción                | Salida                |
| ----------------------- | -------------------------- | --------------------- |
| `npm run compilar:sass` | Compila SASS en modo watch | `build/css/`          |
| `npm run build:sass`    | Optimiza CSS con PurgeCSS  | `build/css/meeti.css` |

> **Sugerencia:** usa el modo watch mientras editas estilos para ver cambios al instante.

## 🚀 Instalación y uso

1. Instala dependencias:
   ```bash
   npm install
   ```
2. Compila SASS en modo desarrollo:
   ```bash
   npm run compilar:sass
   ```
3. Abre `index.html` en el navegador.

> **Tip:** para la versión optimizada ejecuta `npm run build:sass`.

---

## ⭐ ¿Te Gustó?

Si este proyecto te ayudó a aprender Bootstrap, déjame una estrella ⭐ en GitHub.

Creado con ❤️ | Bootstrap 5 | 2026
