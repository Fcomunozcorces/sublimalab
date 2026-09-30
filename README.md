# Sublima Lab — landing (maqueta)

Sitio estático de una página. Sin build: Netlify publica la raíz tal cual.

## Publicar en Netlify
1. Subir esta carpeta a un repositorio de GitHub (rama `main`).
2. En Netlify: **Add new site → Import an existing project → GitHub**, elegir el repo. Build command vacío, publish directory `.` (ya viene en `netlify.toml`).
3. El formulario ya está preparado para **Netlify Forms** (`data-netlify="true"`): los leads aparecen en Netlify → Forms → `cotizacion`. Activar la notificación por correo en *Form notifications*.
4. Dominio: en Netlify → Domain management, conectar `sublimalab.cl` (registrar antes en NIC Chile).

## Pendientes antes de lanzar
- Reemplazar `[NUMERO]` del enlace de WhatsApp en `index.html` (formato `https://wa.me/569XXXXXXXX`).
- Reemplazar `[COMUNA]` y `Resolución sanitaria N° [PENDIENTE]`.
- Sustituir las fotos de banco (`assets/img/fruta.jpg`, `mascotas.jpg`, `dulces.jpg`) por fotos propias cuando existan.
- Revisar precios en la sección Precios: son los de la propuesta, no una lista oficial.

## Estructura
- `index.html` — página completa (estilos inline, editable en cualquier editor).
- `gracias.html` — página de confirmación del formulario.
- `assets/style.css` — base y comportamiento responsive.
- `assets/img/` — logo, favicon y fotos.

## Licencias de imágenes
- `outdoor.jpg`: fotografía de Gufo Foods (Carmen Wetzel); uso autorizado por Gufo.
- `fruta.jpg` (Alexander Schimmeck), `dulces.jpg` (Eddie Pipocas), `mascotas.jpg` (Ayla Verschueren): Unsplash, licencia libre para uso comercial, atribución no obligatoria.

## Migrar a Shopify más adelante
Cada `<section>` corresponde a una sección de tema (Dawn): hero, multicolumna, precios, tabla, FAQ y formulario. El formulario se reemplaza por Shopify Forms o Klaviyo.
