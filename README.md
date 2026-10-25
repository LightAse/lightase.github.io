# LightAse — Portfolio

Portfolio personal de Ian Fridman, con seis repositorios públicos de GitHub. Sitio estático en HTML, CSS y JavaScript sin frameworks ni servicios de backend.

## Contenido

- `index.html` — portfolio, cuatro proyectos destacados y dos proyectos adicionales.
- `assets/style.css` — diseño responsive.
- `apps/homelab-backups.html` — información específica de la aplicación OAuth de copias de seguridad (no enlazada desde la portada).
- `privacy.html` — política de privacidad de la aplicación.
- `terms.html` — términos de uso de la aplicación.
- `.nojekyll` — publicación estática de GitHub Pages.

## Proyectos en el portfolio

- [PsOldRemotePlay](https://github.com/LightAse/PsOldRemotePlay)
- [ghostfolio-iol-sync](https://github.com/LightAse/ghostfolio-iol-sync)
- [job-assist](https://github.com/LightAse/job-assist)
- [olist-data-warehouse](https://github.com/LightAse/olist-data-warehouse)
- [Ultra-Super-Snake](https://github.com/LightAse/Ultra-Super-Snake)
- [homebanking](https://github.com/LightAse/homebanking)

No figuran TrueSimCity, linux_tp_xd, ubuntu ni repositorios privados.

## Publicación

En **Settings → Pages**, elegir **Deploy from a branch**, rama `main`, carpeta `/ (root)`.

Cuando se publique:
- Portfolio: https://lightase.github.io/
- Página informativa OAuth: https://lightase.github.io/apps/homelab-backups.html
- Privacidad: https://lightase.github.io/privacy.html
- Términos: https://lightase.github.io/terms.html

Para Google Cloud, registrar la **página específica de la aplicación**, no el portfolio general. La comprobación de dominio o marca de Google es un trámite separado de publicar GitHub Pages y puede requerir un dominio verificable.

## Seguridad

La web es pública: no publicar claves SSH, secretos de restic, tokens OAuth, archivos de configuración privados, backups ni datos personales adicionales. La aplicación de backups y el VPS siguen siendo privados.
