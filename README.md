[README.md](https://github.com/user-attachments/files/29289521/README.md)
# Twind Banner Creator

Herramienta interna de diseño de banners promocionales para el equipo de Twind.

## ¿Qué hace?

- Crea banners para anuncios, promociones, cabeceras de email y posts de blog
- Fondos, pills y tipografías de la marca Twind
- Control total por capa: posición, tipografía, tamaño, color, opacidad
- Bordes redondeados configurables
- **Asistente IA** que genera copy y diseño automáticamente
- Exporta en **PNG** y **HTML** listo para pegar

## Cómo usar

Abre `index.html` directamente en el navegador — no requiere servidor, build ni dependencias.

```bash
# Opción 1: abrir directo
open index.html

# Opción 2: servidor local (recomendado para Chrome)
npx serve .
# o
python3 -m http.server 8080
```

## Deploy

### GitHub Pages (gratis)

1. Sube el repo a GitHub
2. Ve a Settings → Pages → Source: `main` branch → `/root`
3. URL pública: `https://tuorg.github.io/twind-banner-creator`

### Netlify / Vercel (gratis)

Arrastra la carpeta al dashboard de Netlify o conecta el repo.

## Estructura

```
twind-banner-app/
├── index.html          ← App completa (self-contained)
├── README.md
├── .gitignore
└── LICENSE
```

## Para el equipo

La app está autocontenida en un único `index.html` — incluye fuentes, assets e imágenes en base64. No hay dependencias externas salvo la llamada a la API de Anthropic para el asistente IA (requiere conexión a internet).

## API Key

El asistente IA usa la API de Anthropic y funciona automáticamente desde claude.ai. Si lo despliegas fuera de claude.ai necesitarás configurar la API key.

---

Hecho con ❤️ por el equipo de Twind.
