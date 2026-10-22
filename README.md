# funnel-futurials

Presentación de FunnelFUTURIALS, publicada en https://funnel.futurials.com

- Un solo archivo estático: `index.html`. Sin build.
- Dos árboles en la misma página: escritorio y mobile. El script monta el que corresponde al dispositivo; nadie navega a ninguno de los dos.
- Identidad Futurials: Cormorant Garamond + DM Sans, acento único #F08000, wordmark con el ® nativo de Cormorant como en futurials.com.
- Motion con GSAP 3.13 (core + Observer) desde cdnjs.

## Deploy

Hostinger clona este repo en `public_html` del sitio `funnel.futurials.com` (cuenta `u990879393`).
Para publicar un cambio: push a `main` y volver a correr el deploy de Git del sitio desde el conector de Hostinger.
