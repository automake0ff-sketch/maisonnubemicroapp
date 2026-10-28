# MAISON NUBE — Custom Box

Microapp demostrativa para una cafetería y pastelería ficticia. Permite configurar una caja, calcular un importe orientativo, enviar una solicitud simulada, solicitar presupuesto corporativo y consultar un panel administrativo con datos de prueba.

## Ejecutar

```bash
npm install
npm run dev
```

Para validar una compilación de producción: `npm run build`.

## Personalización

- El catálogo, precios y disponibilidad están centralizados al inicio de `src/main.tsx`, en `products` y `boxTypes`.
- Los estados y solicitudes del panel también son datos locales ficticios (`demoRequests`).
- La paleta está en las variables de `src/styles.css`.

## Qué es real y qué es simulado

La navegación, configurador, cantidades, cálculo, validación de formulario, cambio ES/EN y panel son funcionales en el navegador. Las solicitudes no se envían ni se guardan; productos, precios e información mostrada son ficticios.

## Preparación para producción

Pendiente de integrar: backend seguro, persistencia, validación en servidor, control de acceso al panel, antispam, disponibilidad real, notificaciones y tratamiento legal de datos personales.

## Checklist manual

- [ ] Crear una caja y modificar cantidades.
- [ ] Navegar atrás y comprobar que se conservan los datos.
- [ ] Enviar con campos requeridos vacíos y comprobar validación nativa.
- [ ] Completar una solicitud y revisar el mensaje de demo.
- [ ] Filtrar el panel administrativo.
- [ ] Comprobar la experiencia móvil con las herramientas del navegador.
