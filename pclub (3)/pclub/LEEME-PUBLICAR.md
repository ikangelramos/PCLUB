# PCLUB · Lista de comprobación antes de publicar

## 1. Datos obligatorios (`assets/config.js`)
- [ ] `PCLUB_LEGAL.owner` y `PCLUB_LEGAL.nif`: titular y NIF/CIF **reales** (aviso legal y privacidad).
- [ ] `PCLUB_FORMS.endpoint`: ya apunta a FormSubmit. **Activa el correo**: envía un formulario de prueba y pulsa el enlace de confirmación que llegará a ik.angelramos@hernanilanh.eus.
- [ ] `PCLUB_SITE.reviews`: **borra las opiniones de ejemplo** y pon opiniones reales (o déjalo vacío). Añade `googleReviewsUrl` cuando tengas la ficha de Google.

## 2. Contenido a confirmar (lo inventado como propuesta)
- [ ] Precios de packs, bonos, combos y pack cumpleaños (página Ofertas).
- [ ] Fechas, precios y premios de torneos y noches LAN.
- [ ] Tarjeta de fidelidad (sellos y premios) y política de cancelación (2 h de aviso).
- [ ] Alquiler, plantilla y demás costes del Excel de presupuesto.
- [ ] Fotos: sustituir las de internet por fotos propias (y con permiso de las personas que salgan).

## 3. Al subir el sitio
- [ ] Subir la carpeta `pclub/` completa a un hosting (Cloudflare Pages, Netlify, GitHub Pages…).
- [ ] Configurar `404.html` como página de error del hosting.
- [ ] Cambiar `og:image` a URL absoluta (p. ej. `https://tudominio/assets/og.png`).
- [ ] Cambiar la URL del QR de `material/PCLUB_cartel_y_tarjetas.pdf` si el dominio no es pclub.eus.
- [ ] Crear `sitemap.xml` y `robots.txt` con el dominio definitivo; dar de alta Google Business Profile.
- [ ] Alojar las tipografías en local (quitar Google Fonts) si queréis evitar el envío de IP a Google.

## 4. Pruebas
- [ ] Móvil y escritorio, en los 5 idiomas (menú, selector de idioma, formularios).
- [ ] Enviar: contacto, reserva, inscripción a torneo y bono regalo. Comprobar que llegan los correos.
- [ ] Probar el selector de sala privada/zona abierta y el nº de personas en el precio estimado.
- [ ] Teclado: recorrer el sitio solo con Tab; comprobar el foco visible.

## 5. (Opcional) Gestionar reservas en Trello
Crea un tablero «PCLUB · Reservas» con estas listas: **Solicitudes nuevas → Confirmadas → Completadas → Canceladas**.
1. En Trello: menú del tablero → *Más* → *Configuración de correo electrónico a tablero*. Copia la dirección y elige la lista «Solicitudes nuevas».
2. En tu correo (ik.angelramos@hernanilanh.eus) crea una regla que reenvíe a esa dirección los mensajes que lleguen de FormSubmit.
3. Cada solicitud (reserva, torneo, bono regalo) aparecerá como una tarjeta; arrástrala entre listas según avance.
