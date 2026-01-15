# Modelos de render para cliente

| **Sigla**                | **Nombre**                      | **Definición corta**          | **Explicación**                                                             | **Uso típico**                             |
| ------------------------ | ------------------------------- | ----------------------------- | --------------------------------------------------------------------------- | ------------------------------------------ |
| **SSR**                  | Server-Side Rendering           | HTML generado en el servidor  | El servidor genera el HTML completo en cada request y lo envía al navegador | SEO fuerte, contenido dinámico por usuario |
| **CSR**                  | Client-Side Rendering           | HTML generado en el navegador | El servidor envía JS vacío o mínimo y el navegador construye la UI          | Apps interactivas, dashboards              |
| **SSG**                  | Static Site Generation          | HTML generado en build time   | El HTML se genera una vez durante el build y se sirve como archivo estático | Blogs, landing pages                       |
| **ISR**                  | Incremental Static Regeneration | HTML estático regenerable     | Combina SSG + regeneración automática bajo demanda                          | Contenido semi-dinámico                    |
| **Streaming SSR**        | SSR por partes                  | HTML enviado en fragmentos    | El servidor envía el HTML progresivamente mientras se procesa               | Apps grandes, UX rápida                    |
| **Partial Hydration**    | Hidratación parcial             | Solo partes usan JS           | No todo el HTML se hidrata con JS, solo lo necesario                        | Performance web                            |
| **Islands Architecture** | Islas interactivas              | UI estática + islas JS        | HTML estático con pequeños componentes interactivos                         | Marketing sites modernos                   |
