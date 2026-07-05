# Proyecto — Landing page personal

Página web personal de **Edwin Alejandro González**, desarrollador de software especializado en automatización de procesos e integración de IA para empresas colombianas.

Es un sitio estático de una sola página (`pag_proyecto.html`), sin dependencias de build ni frameworks: HTML, CSS y JavaScript vanilla en un solo archivo.

## Contenido de la página

- **Hero** — presentación con efecto de máquina de escribir en una terminal simulada.
- **Sobre mí** (`#sobre-mi`) — perfil profesional y forma de trabajo.
- **Habilidades** (`#habilidades`) — 5 habilidades distintivas y stack técnico (Node.js, Python, GCP, Docker, SQL, APIs REST, LLMs, bots de WhatsApp).
- **Servicios** (`#servicios`) — bots con IA, integraciones y automatización de procesos, más el servicio insignia "Garaje de automatización".
- **Proyectos** (`#proyectos`) — casos reales: bot de WhatsApp con IA, facturación electrónica en salud, rescate de infraestructura en GCP, agente de trading algorítmico.
- **Blog** (`#blog`) — espacio para enlazar publicaciones técnicas.
- **Contacto** (`#contacto`) — formulario que arma un `mailto:` con los datos ingresados, más enlaces directos a correo, GitHub y WhatsApp.

## Características

- Modo claro/oscuro con detección automática de preferencia del sistema (`prefers-color-scheme`) y toggle manual.
- Animaciones de aparición al hacer scroll (`IntersectionObserver`).
- Diseño responsive (breakpoints en 760px y 460px).
- Sin backend: el formulario de contacto abre el cliente de correo del usuario con el mensaje prellenado.

## Cómo verlo localmente

Basta con abrir `pag_proyecto.html` en el navegador, o servirlo con cualquier servidor estático:

```bash
npx serve .
```

## Pendientes / personalización

- Conectar el formulario a un servicio como Formspree si se quiere recibir los mensajes directo en una bandeja en vez de vía `mailto`.
- Completar las tarjetas de proyectos y entradas de blog con enlaces reales.
