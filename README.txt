DYSOLUTIONS SERVICIO TÉCNICO DYSON EN VALLADOLID
================================================

Web de una sola página (HTML/CSS/JS estático + función serverless en Vercel)
para DySolutions, servicio técnico y reparación de equipos Dyson con recogida
y entrega en Valladolid y área metropolitana.

Dominio: https://valladolidserviciotecnico.com.es/
Marca: DySolutions Servicio Técnico Dyson en Valladolid
Nombre corto (og:site_name): DySolutions – Valladolid
Ficha de Google: https://maps.app.goo.gl/LRjZ3HQzw1HKwDYC6
Mapa: iframe de Google Maps de la ficha "DySolutions Servicio Técnico Dyson en Valladolid",
insertado tal cual en la sección de contacto (ancho 100% vía CSS).

DATOS DE CONTACTO
- WhatsApp: +34 649 97 01 28.
- Teléfono: +34 910 05 48 17.
- Recogida a domicilio: https://sis.redsys.es/tiendaWeb/item/NDk4OzI=
  (botón "Solicita tu recogida ahora" del hero, siempre en negro).
- Horario: lunes a viernes de 09:30 a 18:00.
- Política de privacidad: https://kelatos.com/privacy-policy/.

DIRECCIÓN: no se muestra dirección postal. La web indica "Valladolid y área
metropolitana" y servicio de recogida y entrega; el taller está en Madrid.
Si se confirma una dirección en Valladolid, añadirla al hero, footer y JSON-LD.

ESTRUCTURA
- index.html: toda la página (hero, ventajas, reparación rápida, confianza,
  servicios, por qué elegirnos, cómo trabajamos, contacto + mapa, FAQ, texto
  SEO, footer, cookies y JSON-LD).
- style.css: base de la plantilla.
- mobile-navigation.css, social-footer.css, cal-booking.css: ajustes compartidos.
- dysolutions.css: identidad visual de la marca (una sola capa, sin
  sobrescrituras en cascada).
- dysolutions-header-hero.css: cabecera grafito con logotipo blanco.
- dysolutions.js: menú móvil (se cierra al pulsar un enlace), formulario y
  preferencias de cookies (clave localStorage "dysolutions_cookie_preference").
- dysolutions-n8n-chat.js / .css: chatbot n8n con webhook compartido del grupo
  y botón de respaldo.
- api/contacto.js: envío del formulario por SMTP (variables SMTP_HOST,
  SMTP_PORT, SMTP_SECURE, SMTP_USER, SMTP_PASS y CONTACT_EMAIL en Vercel).
- img/: isotipo, patrón e ilustraciones SVG de la marca.
- robots.txt y sitemap.xml apuntan a https://valladolidserviciotecnico.com.es/.

PALETA: rojo técnico, carbón y titanio (estética de herramienta profesional).
- Primario rojo técnico #D62839 · oscuro #B01E2E · muy oscuro #7A1420
- Carbón (cabecera, footer, cookies, sección oscura, tarjeta de Google) #121417
- Rojo claro #FF5A68 para detalles sobre fondo oscuro (logotipo, destacados)
- Titanio #C3CAD5 en ilustraciones · fondos gris claro #F4F5F7
Excepciones: WhatsApp conserva su verde y YouTube su rojo corporativo.
