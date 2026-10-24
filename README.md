# Montana Music Production — sitio web oficial

Repositorio público del sitio [montanamusicproduction.com](https://montanamusicproduction.com/). Incluye el sello musical, artistas, tienda oficial externa y los servicios del estudio de diseño digital.

## Estructura

| Archivo | Función |
| --- | --- |
| `index.html` | Portada, música, artistas, tienda oficial y acceso al estudio creativo |
| `creative-studio.html` | Página de servicios, paquetes, preguntas frecuentes y solicitud de cotización |
| `artistas.html` | Sección de artistas del sello |
| `artist.jpg`, `studio.jpg`, `emblem.jpg` | Recursos visuales |
| `CNAME` | Dominio personalizado `montanamusicproduction.com` |
| `sitemap.xml`, `robots.txt` | Descubrimiento e indexación para buscadores |

## Estudio creativo (diseño digital)

Marca: **Montana Creative Digital Studio**, iniciativa de **Montana Music Production LLC**. Se atienden solicitudes de logotipos, portadas musicales, gráficos para redes sociales y diseños de mercancía.

Paquetes publicados como referencias de precio: **Starter $69**, **Pro $229**, **Elite $449**, además de proyectos personalizados. Los entregables y las revisiones deben acordarse mediante cotización; no se cobra por solicitar una propuesta.

Página: https://montanamusicproduction.com/creative-studio.html

### Formulario de cotizaciones — HubSpot

- Plataforma: HubSpot, cuenta/portal **247656721**, región **na2**.
- ID de formulario: `5b7b0f2f-0137-48a6-a33a-1f9f6e8d73e7`.
- Enlace público: https://43g55d.share-na2.hsforms.com/2W3sPLwE3SKajOh-fbo1z5w
- Código incorporado en `creative-studio.html`: cargador del **nuevo editor** `https://js.hsforms.net/forms/embed/247656721.js` + `<div class="hs-form-frame" data-region="na2" ...>`.
- Existe enlace alternativo al formulario público, por si el iframe no se carga en el navegador del visitante.
- **Flujo comercial deseado:** solicitud de cliente → revisión y cotización → aprobación → factura/pago → ejecución del proyecto.

No cambiar este formulario por un formulario nuevo sin revisar antes el ID y los enlaces existentes. El formulario se confirmó como **PUBLISHED** el 24-oct-2026, pero **no se ha confirmado todavía una solicitud real de principio a fin**.

### Ajustes pendientes de comprobación manual en HubSpot

1. Verificar que el formulario incluya campos para **servicio solicitado**, **paquete de interés** y **descripción del proyecto**, además de nombre y correo. El conector actual **no permite leer ni editar el contenido de los campos** de formularios modernos.
2. Verificar que los datos de prueba se guarden como un contacto nuevo y que llegue una notificación a la persona que gestiona las consultas.
3. Cambiar el nombre interno automático del formulario a `Montana Creative Digital Studio - Cotizaciones`. No cambia el título que ve el público.
4. Revisar las opciones de protección contra spam y consentimiento con las políticas reales del negocio.
5. Verificar **despliegue HTTPS público** después de los cambios. La presencia de archivos en GitHub no demuestra por sí sola que la publicación web se haya actualizado.

## Tienda oficial de mercancía — no confundir

La tienda de prendas y accesorios es independiente del estudio de diseño:

https://montanaofficialstore-shop.fourthwall.com/

El enlace externo se conserva en `index.html`. **No** reemplazarlo por HubSpot ni mezclar compras de mercancía con solicitudes de diseño.

## Marca y traducción

**Montana** es el nombre de marca y debe permanecer igual en español e inglés. No traducirlo a **Mountain** ni introducir montañas como motivo gráfico. Los nombres propios llevan `translate="no"` o clase `notranslate` cuando corresponde.

## Comprobación básica tras una modificación

1. Confirmar que `index.html` apunta a `creative-studio.html`.
2. Confirmar que `creative-studio.html` usa el portal/formulario correctos y que el enlace público abre.
3. Asegurar que el enlace a Fourthwall permanece en `index.html`.
4. Verificar que `sitemap.xml` incluye la página del estudio.
5. Verificar visualización en móvil, formulario integrado y HTTPS en el dominio real.

*Este README documenta configuración y pendientes verificables. No presupone que Google haya indexado la web ni que se haya completado una solicitud real.*
