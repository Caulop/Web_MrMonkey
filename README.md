# Mr Monkey Burger — Sabor Salvaje 🍔

Sitio web oficial de **Mr Monkey Burger**: hamburguesería urbana de smash burgers con domicilio, para llevar y locales.

## Stack

- HTML5 semántico con CSS custom properties (sin frameworks)
- Tipografías: Permanent Marker · Barlow Condensed · Caveat Brush · Inter (Google Fonts)
- Animaciones con Intersection Observer API (sin dependencias externas)
- Diseño mobile-first, accesible (skip-link, focus-visible, aria)

## Estructura

```
Web_MrMonkey/
├── index.html          # Página principal
├── img/                # Assets gráficos
│   ├── logo.png
│   ├── mascot.png
│   ├── hero-burger.png
│   ├── burger-1.png · burger-2.png · burger-3.png
│   ├── chef.png
│   └── bag.png
└── docs/               # Sistema de diseño
    ├── BRAND.md        # Identidad, voz y tono
    ├── DESIGN.md       # Directrices generales
    ├── tokens.md       # Tokens de color, tipografía, espaciado
    ├── components.md   # Componentes UI
    ├── layout.md       # Sistema de layout
    ├── motion.md       # Principios de animación
    ├── animaciones.md  # Especificaciones de animación
    ├── iconography.md  # Sistema de iconos
    ├── illustration.md # Estilo ilustración
    ├── photography.md  # Directrices fotográficas
    ├── social.md       # Plantillas redes sociales
    ├── print.md        # Piezas impresas
    ├── EDGE_CASES.md   # Casos borde y accesibilidad
    ├── referencias.md  # Referencias y benchmarks
    └── prompt.md       # Prompts de IA para el proyecto
```

## Sistema de diseño

El proyecto incluye un design system completo documentado en Markdown:

| Documento | Contenido |
|---|---|
| `BRAND.md` | Identidad, pilares, voz y tono |
| `tokens.md` | Variables CSS, paleta, escala tipográfica |
| `components.md` | Botones, cards, nav, formularios |
| `motion.md` + `animaciones.md` | Curvas, duraciones, keyframes |
| `EDGE_CASES.md` | Accesibilidad, estados vacíos, errores |

## Paleta principal

| Token | Valor | Uso |
|---|---|---|
| `--black` | `#0d0d0d` | Fondo base |
| `--orange` | `#ff4a12` | Acento principal |
| `--paper` | `#e9e6df` | Secciones claras |
| `--white` | `#ffffff` | Texto sobre oscuro |

## Correr localmente

Abre `index.html` directamente en el navegador — no requiere servidor ni build step.

```bash
# Con VS Code Live Server
code .
# Luego Go Live desde la barra de estado

# O con Python (cualquier versión)
python -m http.server 3000
```

## Marca

- **Nombre:** Mr Monkey Burger · *Wildly Delicious*
- **Mascota:** mono con casco de calavera, rayos y corona (estilo grafiti)
- **Lema:** Eat wild · Fuerza · Sabor · Actitud
- **Voz:** directa, callejera, español de Colombia

---

*Desarrollado con Claude Code · Diseño propio*
