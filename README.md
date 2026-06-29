# Portafolio — Diego

Portafolio personal de Diego, desarrollador web en formación. Sitio estático con diseño moderno, responsive y orientado a destacar proyectos, habilidades y perfil profesional.

## Estructura del proyecto

```
portafolio/
├── index.html          # Página principal (inicio, habilidades, proyectos)
├── about.html          # Sobre mí
├── services.html       # Servicios
├── assets/
│   ├── css/
│   │   ├── base.css    # Variables, header, footer, botones (compartido)
│   │   ├── index.css   # Estilos de la página principal
│   │   ├── about.css   # Estilos de Sobre mí
│   │   └── services.css
│   └── images/         # Iconos e imágenes del portafolio
└── README.md
```

## Imágenes requeridas

Coloca estos archivos en `assets/images/`:

| Archivo | Uso |
|---------|-----|
| `sitio-web.png` | Ilustración del hero en inicio |
| `html-5.png` | Icono HTML |
| `css-3.png` | Icono CSS |
| `js.png` | Icono JavaScript |
| `piton.png` | Icono Python |
| `servidor-sql.png` | Icono SQL |

## Cómo ver el sitio

Abre `index.html` en tu navegador o usa un servidor local:

```bash
# Con Python
python -m http.server 8000

# Con Node.js (npx)
npx serve .
```

Luego visita `http://localhost:8000`.

## Páginas

- **Inicio** — Presentación, habilidades y proyectos destacados
- **Servicios** — Desarrollo web, UX/UI y aplicaciones
- **Sobre mí** — Perfil profesional, enfoque y valores

## Tecnologías

HTML5 · CSS3 · Diseño responsive · Inter (Google Fonts)

## Próximos pasos sugeridos

- Añadir enlaces reales a repositorios de GitHub en los proyectos
- Incluir sección de contacto (email, LinkedIn, GitHub)
- Desplegar en GitHub Pages, Netlify o Vercel
