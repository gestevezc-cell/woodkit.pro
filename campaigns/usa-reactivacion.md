# WOODKIT.PRO · Reactivación USA (test 14 días)

Objetivo: conseguir **conversaciones** (WhatsApp / formulario), no ventas directas. Con un ticket alto y poco volumen, el contacto es la señal fiable.

> Supuestos que he tomado (cámbialos si no encajan): plataforma Meta (Instagram + Facebook), 12 €/día × 14 días = 168 €, destino `https://woodkit.pro/en/usa`.

---

## 0. Bloqueadores: NO lanzar hasta tener los 4 en verde

- [ ] El formulario de `/contacto/` y `/en/contacto/` **llega de verdad** a tu correo (prueba desde el móvil, mira spam).
- [ ] `iwood-solutions.com/en/usa` redirige a `woodkit.pro/en/usa` sin error. Prueba también `/en/faq` y una ficha de producto.
- [ ] Botón de WhatsApp visible en móvil en `/en/usa`, con el número correcto.
- [ ] `/en/usa` dice claro: **coste de envío a USA, plazos, aranceles/impuestos y devoluciones**. Si no lo dice, el que llega desde un anuncio se va.

---

## 1. Estructura en Meta Ads Manager

**Campaña**
- Nombre: `WK_USA_Test_2026-10`
- Objetivo: **Engagement → Mensajes (WhatsApp)**. Si aún no tienes WhatsApp Business enlazado, usa **Tráfico** con destino `/en/usa` y mide clics al botón de WhatsApp.
- Presupuesto a nivel de conjunto de anuncios, no de campaña.

**Conjunto A · Surf** (6 €/día)
- Ubicación: Estados Unidos. Edad: 25-55. Idioma: inglés.
- Intereses: surfing, surfboards, longboarding, shaping, surf culture.

**Conjunto B · Maker / DIY** (6 €/día)
- Ubicación: Estados Unidos. Edad: 28-60. Idioma: inglés.
- Intereses: woodworking, DIY, boatbuilding, sustainable living.

**Ubicaciones:** Instagram Feed, Reels, Stories y Facebook Feed. Quita Audience Network.

**Anuncios (3 por conjunto)**
1. Vídeo corto (10-20 s) de construcción real: piezas, ensamblaje, tabla terminada. **Usa tu material propio, no stock.**
2. Foto de la tabla terminada en el agua o en la playa.
3. Carrusel: kit → montaje → resultado.

---

## 2. Textos (inglés, para validar antes de publicar)

Revisa que cada afirmación sea cierta para tu producto. Los he redactado a partir del lema y de la estructura de la web, sin ver los textos reales.

**Opción 1 · Estructura**
- Texto principal: `A structural surf system, not just a kit. Build your own paulownia surfboard, piece by piece. Questions before you buy? Message us.`
- Título: `Build your own surfboard`
- Botón: `Send message`

**Opción 2 · Peso y material**
- Texto principal: `Paulownia: light, strong, renewable. Shaped by you, designed to last. Talk to a builder before you decide.`
- Título: `Light. Strong. Yours.`
- Botón: `Send message`

**Opción 3 · Proceso**
- Texto principal: `From flat parts to a finished board. See how it goes together, and ask us anything.`
- Título: `See how it's built`
- Botón: `Learn more`

**Mensaje de bienvenida en WhatsApp (respuesta automática)**
`Hi! Thanks for reaching out to WOODKIT.PRO. Which board are you thinking about, and where are you shipping to? We'll reply personally.`

---

## 3. Enlaces con UTM (para medir en GA4)

```
https://woodkit.pro/en/usa?utm_source=meta&utm_medium=paid_social&utm_campaign=usa_test_2026-10&utm_content=A_surf_video1
```

Cambia `utm_content` por conjunto y anuncio (`A_surf_video1`, `B_maker_photo1`, etc.).

---

## 4. Cómo leer el resultado (día 7 y día 14)

| Momento | Qué mirar | Decisión |
|---|---|---|
| Día 3-4 | Que los anuncios se entreguen y los enlaces no den error | Si hay errores, para y arregla |
| Día 7 | Clics al enlace, mensajes, coste por mensaje | Apaga el conjunto con peor coste; mueve su presupuesto al mejor |
| Día 14 | Mensajes totales y cuántos son reales (no curiosos) | Ver regla siguiente |

**Regla de decisión (día 14):**
- Varios mensajes reales de compradores potenciales: el canal funciona, el siguiente paso es cerrar la venta por conversación.
- Clics pero cero mensajes: el problema está en `/en/usa` (oferta, envío, confianza), no en el anuncio.
- Casi sin clics: el problema es el anuncio o el público. Cambia el creativo primero.

**Ojo con GA4:** el tráfico directo de USA a la home (unas 100 visitas de 0-1 s) es en su mayoría bots. Mide solo con las visitas que traen `utm_source=meta`.

---

## 5. Pendiente de ti

1. Número de WhatsApp Business.
2. Confirmación de envío a USA: precio, plazo, quién paga aranceles.
3. Material propio (vídeos y fotos) para los anuncios.
4. Presupuesto final si no son 168 €.
