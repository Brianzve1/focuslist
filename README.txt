# FocusList

Versión 2: centro de control personal.

Incluye:
- Inicio / dashboard
- Tareas con sistema ABCDE y Sapo
- Hoy, mañana, próximos días y lista maestra
- Registro de ingresos, gastos, ahorros e inversiones
- Objetivos con progreso
- Hábitos
- Exportación de datos
- PWA para instalar en iPhone
- Funcionamiento offline mediante Service Worker

## Estructura

FocusList/
- index.html
- manifest.json
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png

## Importante

Los datos se guardan localmente en el navegador del dispositivo. La app no envía estos datos a un servidor.

Para instalarla en iPhone hay que publicarla con HTTPS (por ejemplo, GitHub Pages) y abrirla desde Safari.
