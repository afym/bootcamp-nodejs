# Conceptos de cliente

| **Concepto**     | **Definición simple**             | **Descripción**                            | **Herramientas**       | **Ejemplo**            |
| ---------------- | --------------------------------- | ------------------------------------------ | ---------------------- | ---------------------- |
| **Compilar**     | Convertir a código de bajo nivel  | Transforma un lenguaje a otro optimizado   | Webpack, Vite, esbuild | JS → bundle optimizado |
| **Transpilar**   | Convertir a otro lenguaje similar | Mantiene el mismo nivel de abstracción     | TypeScript, Babel      | TS → JS                |
| **Bundle**       | Unir archivos                     | Combina múltiples archivos en uno o pocos  | Webpack, Rollup        | app.js                 |
| **Minificar**    | Reducir tamaño                    | Elimina espacios y renombra variables      | Terser                 | JS más pequeño         |
| **Exportar**     | Exponer código                    | Hace accesible una función o módulo        | ES Modules             | `export function x()`  |
| **Importar**     | Usar código externo               | Consume módulos exportados                 | ES Modules             | `import { x }`         |
| **Build**        | Proceso de producción             | Genera archivos finales listos para deploy | Vite, Next, Angular    | `/dist`                |
| **Hydration**    | Activar HTML con JS               | Conecta HTML estático con lógica JS        | React, Vue             | SSR → app viva         |
| **Tree Shaking** | Eliminar código muerto            | Quita código no usado                      | Rollup, Webpack        | Bundle más pequeño     |
