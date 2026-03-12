# Agendame Landing (HTML + CSS)

Landing page responsive con HTML, CSS y JS vanilla.

## Estructura

- `index.html`: marcado principal.
- `styles.css`: estilos globales, secciones, animaciones y media queries.
- `assets/`: imágenes, iconos y branding.

## Ejecutar local

```bash
cd /Users/sebastianmunoz/Desktop/agendame/agendame-landing
python3 -m http.server 4180
```

Abrir `http://localhost:4180`.

## Responsive

Breakpoints implementados:

- `@media (max-width: 1100px)`
- `@media (max-width: 900px)`
- `@media (max-width: 640px)`

## Notas

- Incluye menú móvil (toggle) en JS vanilla.
- Respeta `prefers-reduced-motion` para accesibilidad de animaciones.
