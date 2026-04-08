# Midnight Systems Portfolio

Portafolio en Astro con estilo cyberpunk glassmorphism.

## Configurar GitHub API real

La página principal puede cargar tus repositorios reales desde GitHub.

1. Crea un archivo `.env` en la raíz del proyecto.
2. Agrega estas variables:

```bash
PUBLIC_GITHUB_USERNAME=tu_usuario_github
GITHUB_TOKEN=ghp_opcional_si_quieres_mas_rate_limit
```

- `PUBLIC_GITHUB_USERNAME`: obligatorio para activar la sincronización.
- `GITHUB_TOKEN`: opcional, recomendado para evitar límites de rate en builds frecuentes.

## Scripts

- `pnpm dev`: inicia entorno local.
- `pnpm build`: compila producción.
- `pnpm preview`: sirve el build local.
