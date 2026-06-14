# TFL.show — Landing Page

Landing estática para **TFL.show — The Fans Legend**. Desplegada en Vercel (`prompt-forge.com`).

## Contenido

- Hero con countdown al evento (Nov 2026)
- Paquetes de membresía (modal demo CCBill)
- Modelos, fases del concurso y CTAs
- Widget de captación de leads Agentix Vanguard (`data-tenant="tfl-show"`)

## Estructura

```
├── index.html    # Página principal (HTML + CSS + JS inline)
├── vercel.json   # Configuración Vercel (static)
├── .gitignore
└── README.md
```

## Despliegue en Vercel

### Desde GitHub

1. Repo: [promt-forge-com/landingpage](https://github.com/promt-forge-com/landingpage)
2. En [vercel.com](https://vercel.com) → **Add New Project** → importa el repositorio.
3. **Root Directory:** raíz del repo (donde está `index.html`).
4. **Deploy** — sin build; sitio estático.

### Vercel CLI

```bash
npm i -g vercel
vercel login
vercel --prod
```

## Prueba local

```bash
python3 -m http.server 8000
# http://localhost:8000
```
