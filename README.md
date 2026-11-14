# Somos.M2 — demo web

Esta es una demostración visual e interactiva de Somos.M2. El catálogo, los precios, el carrito y los formularios son de muestra: no procesan pedidos, pagos ni datos comerciales reales.

## Abrir localmente

Abrí `index.html` en un navegador. No requiere instalación ni una compilación.

## Publicación

Está preparada para Cloudflare Pages: la raíz del proyecto se publica tal cual, sin comando de compilación ni carpeta de salida.

## Próxima transición a React + Bootstrap

Para preservar este diseño, la transición recomendada es gradual: crear una aplicación React con Vite, incorporar Bootstrap sólo como base de grilla, accesibilidad y componentes, y trasladar secciones y datos de a una vez. Antes de conectar el catálogo real, se deben definir autenticación, permisos y endpoints seguros; no se deben exponer credenciales ni habilitar cobros desde esta demo.
