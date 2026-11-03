# Reglas del Proyecto — Portafolio Profesional de David Guevara

1. **Framework**: Astro 5+ (Zero-JS innecesario, HTML estático ultra-rápido).
2. **Firma de Código (HTML5 100% Semántico)**:
   - Prohibido usar etiquetas `<div>` genéricas.
   - Todo nodo del DOM debe usar etiquetas semánticas apropiadas (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<figure>`, `<figcaption>`, `<picture>`, `<menu>`, `<ul>`, `<ol>`, `<dl>`, `<dt>`, `<dd>`, `<time>`, `<address>`, `<mark>`, `<small>`, `<code>`, `<kbd>`, `<footer>`).
3. **Efectos Parallax Híbridos (60fps)**:
   - CSS Scroll-Driven Animations + motor ligero con `requestAnimationFrame` y `translate3d`, respetando `prefers-reduced-motion: reduce`.
4. **Identidad Visual**:
   - Fondo Oscuro Carbón (`#0a0a0f`) con acentos Esmeralda (`#10b981`) y Cian Neón (`#06b6d4`) — estilo Linear / Vercel Tech.
   - Fuentes: **Space Grotesk** (títulos), **Plus Jakarta Sans** (cuerpo), **JetBrains Mono** (detalles técnicos y telemetría).
5. **Perfil y Firma de Autor**:
   - **Ing. David Guevara**: Ingeniero en Sistemas, Preespecialización en Cloud Computing y Certificado por Academia Kodigo como Web Developer Jr.
   - Incluir siempre la firma semántica de **David Guevara** en el `<footer>` y en los metadatos del documento.
