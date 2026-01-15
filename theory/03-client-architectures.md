# Arquitecturas de cliente

| **Arquitectura**          | **Tipo de renderizado** | **Descripción**                     | **Herramientas**             | **Casos de uso**        |
| ------------------------- | ----------------------- | ----------------------------------- | ---------------------------- | ----------------------- |
| **SPA** (Single Page App) | CSR                     | Una sola página que cambia por JS   | React, Vue, Angular          | Dashboards, SaaS        |
| **MPA** (Multi Page App)  | SSR tradicional         | Cada página es una request nueva    | PHP, Rails, Django           | Webs clásicas           |
| **SSG App**               | SSG                     | HTML estático generado en build     | Astro, Hugo, Next            | Blogs, docs             |
| **Hybrid App**            | SSR + CSR               | Mezcla renderizado server y cliente | Next.js, Nuxt                | Apps modernas           |
| **Islands App**           | SSG + JS parcial        | HTML estático + componentes JS      | Astro                        | Marketing + interacción |
| **PWA**                   | CSR / Hybrid            | Web app instalable                  | React, Vue + Service Workers | Apps offline            |
| **Micro-frontend**        | Variable                | UI dividida en múltiples apps       | Module Federation            | Grandes organizaciones  |
| **Web Components App**    | Variable                | Componentes nativos del navegador   | Lit, Stencil                 | Sistemas compartidos    |
