# Klaro · Assets Feed

Repositorio público donde viven los assets que la API de Meta consume para publicar en `@klaro.app` y la Página de FB Klaro.

## Estructura

Convención de nombre: `YYYY-MM-DD-{pillar}-{slug}.{jpg|mp4}`

Ejemplos:
- `2026-05-12-A-pregunta-cal-032.jpg`
- `2026-05-13-A-pregunta-cal-032-cover.jpg`
- `2026-05-14-B-memoria-de-trabajo.mp4`

Pilares: `A` (pregunta del día) · `B` (cómo funciona tu mente) · `C` (detrás de Klaro) · `D` (comunidad).

## URL pública

Cada archivo en este repo es accesible vía:

```
https://raw.githubusercontent.com/Burrnny/klaro-assets-feed/main/<filename>
```

## Reglas

- **Solo JPEG para imágenes** (la Content Publishing API de Meta lo exige). PNG no funciona.
- Los videos son MP4, H.264, AAC, máx 100 MB, máx 15 min.
- Una vez publicado, **no borres** el asset hasta 24h después (Meta puede revisarlo).
- Este repo es público — no subas borradores que no quieras que se vean.
